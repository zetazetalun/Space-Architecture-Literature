# From Rocks to Walls: a Model-free Reinforcement Learning Approach to Dry Stacking with Irregular Rocks

**Authors:** André Menezes, Pedro Vicente, Alexandre Bernardino, Rodrigo Ventura
**Affiliation:** Institute for Systems and Robotics, Instituto Superior Técnico, Universidade de Lisboa, Portugal
**Conference:** 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops

## Abstract
In-situ resource utilization (ISRU) is a key aspect for an efficient human exploration of extraterrestrial environments. A cost-effective method for the construction of preliminary structures is dry stacking with locally found unprocessed rocks. This work focus on learning this task from scratch. Former approaches rely on previously acquired models of rocks, which may be hard to obtain in the context of a mission. In alternative, we propose a model-free, data driven approach. We formulate the problem as the task of selecting the position to place each rock on top of the currently built structure. The rocks are presented to the robot in sequence. The goal is to assemble a wall that approximates a target volume, given the 3D perception of the currently built structure, the next object and the target volume. An agent is developed to learn this task using reinforcement learning. The deep Q-networks (DQN) algorithm is used, where the Q-network outputs a value map corresponding to the expected return of placing the object in each position of a top-view depth image. The learned policy outperforms engineered heuristics, both in terms of stability of the structure and similarity with the target volume. Despite the simplification of the task, the policy learned with this approach could be applied to a realistic setting as the high level planner in an autonomous construction pipeline.

## 1. Introduction
For a long term human exploration of extraterrestrial environments, such as the Moon and Mars, it is essential to use native materials as replacement to resources otherwise brought from Earth at great expense. This is commonly referred to as in-situ resource utilization (ISRU) and, amongst other applications, is useful for the construction of planetary infrastructures. Initial settlement structures, such as roads, platforms and shade walls, may be built with unprocessed or minimally processed local rocks using the ancient method of dry stacking.

## 3. Methodology
### 3.1. Environment
The environment is set up in a physics engine to simulate the task of assembling a structure that approximates a target volume, using a sequence of irregular blocks. At each time step, the next object in the sequence is presented to the agent, as well as the currently built structure and the target volume. The agent chooses the new object position (i.e, takes an action) and a careful placement of the object on top of the current structure, with the same orientation as it was presented, is simulated in the environment.

### 3.2. Reward Shaping
A new metric is proposed to evaluate the stability and accuracy of the construction: Discounted Intersection over Union (DIoU). This metric penalizes placements that result in displacements (instability) of the existing structure.

## 4. Results
A set of experiments is performed on the described environment, simulated using PyBullet. The dataset of rock models used is composed of 500 models generated with different levels of irregularity. Two metrics are used to evaluate the obtained policies: Intersection over Union (IoU) and Average Discount (AD).

| Method | IoU30 | AD30 |
| :--- | :--- | :--- |
| Learned with IoU | 0.266 (0.026) | 0.584 (0.064) |
| Learned with DIoU | 0.303 (0.029) | 0.791 (0.058) |
| Random | 0.125 (0.027) | 0.738 (0.06) |
| Random (goal) | 0.232 (0.025) | 0.507 (0.064) |
| Cross-correlation | 0.27 (0.024) | 0.769 (0.046) |

## 5. Conclusion
The major achievement of this work was to develop a setup in which a dry stacking policy can be learned without any previously acquired models of the environment. An agent is able to learn from scratch a policy that captures the goal of the environment and its dynamics. The emergent behavior is consistent with dry stacking theory, such as placing rocks to create inward-sloping support structures.