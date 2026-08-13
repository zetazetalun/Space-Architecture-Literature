# From Rocks to Walls: a Model-free Reinforcement Learning Approach to Dry Stacking with Irregular Rocks

**André Menezes, Pedro Vicente, Alexandre Bernardino, Rodrigo Ventura**
Institute for Systems and Robotics, Instituto Superior Técnico, Universidade de Lisboa, Portugal

## Abstract
In-situ resource utilization (ISRU) is a key aspect for an efficient human exploration of extraterrestrial environments. A cost-effective method for the construction of preliminary structures is dry stacking with locally found unprocessed rocks. This work focus on learning this task from scratch. Former approaches rely on previously acquired models of rocks, which may be hard to obtain in the context of a mission. In alternative, we propose a model-free, data driven approach. We formulate the problem as the task of selecting the position to place each rock on top of the currently built structure. The rocks are presented to the robot in sequence. The goal is to assemble a wall that approximates a target volume, given the 3D perception of the currently built structure, the next object and the target volume. An agent is developed to learn this task using reinforcement learning. The deep Q-networks (DQN) algorithm is used, where the Q-network outputs a value map corresponding to the expected return of placing the object in each position of a top-view depth image. The learned policy outperforms engineered heuristics, both in terms of stability of the structure and similarity with the target volume. Despite the simplification of the task, the policy learned with this approach could be applied to a realistic setting as the high level planner in an autonomous construction pipeline.

## 1. Introduction
For a long term human exploration of extraterrestrial environments, such as the Moon and Mars, it is essential to use native materials as replacement to resources otherwise brought from Earth at great expense. This is commonly referred to as in-situ resource utilization (ISRU) and, amongst other applications, is useful for the construction of planetary infrastructures. Initial settlement structures, such as roads, platforms and shade walls, may be built with unprocessed or minimally processed local rocks using the ancient method of dry stacking.

## 3. Methodology
### 3.1. Environment
The environment is set up in a physics engine to simulate the task of assembling a structure that approximates a target volume, using a sequence of irregular blocks. A state of the environment is represented as a pair of elevation maps: (i) an overhead view of the current structure, and (ii) a bottom view of the new object.

### 3.2. Reward shaping
A simple way to translate the goal of approximating a target volume into a reward value is by using the intersection over union (IoU). We propose a new metric, Discounted IoU (DIoU), to account for structural stability:

$$DIoU_t = \frac{\sum_{i=0}^{t-1} b_t^{[i]} \cdot \mu_t^{[i]}}{T + t - \sum_{i=0}^{t-1} b_t^{[i]}}$$

Where $\mu_t^{[i]}$ is a discount factor based on the displacement of rocks from their original placed position.

## 4. Results
A dataset of 5500 models was used. Two metrics are used to evaluate the obtained policies: IoU (similarity between built and target volume) and Average Discount (AD - effectiveness and stability of placements).

| Method | IoU₃₀ | AD₃₀ |
| :--- | :--- | :--- |
| Learned with IoU | 0.266 (0.026) | 0.584 (0.064) |
| Learned with DIoU | 0.303 (0.029) | 0.791 (0.058) |
| Random | 0.125 (0.027) | 0.738 (0.066) |
| Random (goal) | 0.232 (0.025) | 0.507 (0.064) |
| Cross-correlation | 0.27 (0.024) | 0.769 (0.046) |

## 5. Conclusion
The major achievement of this work was to develop a setup in which a dry stacking policy can be learned without previously acquired models of the environment. The agent learned emergent behaviors, such as starting an episode by placing objects at the boundary of the target area to create inward sloping supports, which is consistent with manual dry stacking theory.