# From Rocks to Walls: a Model-free Reinforcement Learning Approach to Dry Stacking with Irregular Rocks

**André Menezes, Pedro Vicente, Alexandre Bernardino, Rodrigo Ventura**
*Institute for Systems and Robotics, Instituto Superior Técnico, Universidade de Lisboa, Portugal*

## Abstract
In-situ resource utilization (ISRU) is a key aspect for an efficient human exploration of extraterrestrial environments. A cost-effective method for the construction of preliminary structures is dry stacking with locally found unprocessed rocks. This work focus on learning this task from scratch. Former approaches rely on previously acquired models of rocks, which may be hard to obtain in the context of a mission. In alternative, we propose a model-free, data driven approach. We formulate the problem as the task of selecting the position to place each rock on top of the currently built structure. The rocks are presented to the robot in sequence. The goal is to assemble a wall that approximates a target volume, given the 3D perception of the currently built structure, the next object and the target volume. An agent is developed to learn this task using reinforcement learning. The deep Q-networks (DQN) algorithm is used, where the Q-network outputs a value map corresponding to the expected return of placing the object in each position of a top-view depth image. The learned policy outperforms engineered heuristics, both in terms of stability of the structure and similarity with the target volume. Despite the simplification of the task, the policy learned with this approach could be applied to a realistic setting as the high level planner in an autonomous construction pipeline.

## 1. Introduction
For a long term human exploration of extraterrestrial environments, such as the Moon and Mars, it is essential to use native materials as replacement to resources otherwise brought from Earth at great expense. This is commonly referred to as in-situ resource utilization (ISRU) and, amongst other applications, is useful for the construction of planetary infrastructures [13]. Initial settlement structures, such as roads, platforms and shade walls, may be built with unprocessed or minimally processed local rocks using the ancient method of dry stacking [16]. Although rudimentary, this technique has been proven to produce long lasting structures, while requiring very low pre-processing time and energy. Due to the increased risk and limitations imposed by human missions [1], it is important to have systems with the capability of autonomously setting up infrastructure.

However, assembling a structure from a set of irregularly shaped rocks is a difficult task, usually performed by experienced humans and requiring some amount of intuition. It is not clear how to translate this into an autonomous system, specially in a country where no models of the environment are available. Model-based approaches are not suitable within this context. For this reason, the problem of dry stacking in extra-terrestrial environments requires a learning from scratch and model-free approach.

## 4. Results
A set of experiments is performed on the described environment, simulated using PyBullet. The dataset of rock models used is composed of 500 models generated with each value of irregularity, resulting in a complete dataset of 5500 models. The size of the overhead and object elevation maps are 128 x 128 and 32 x 32, respectively. The episode length t is set to 30 objects. Two metrics are used to evaluate the obtained policies. The first is the IoU, which is a measurement of the similarity between the built and target volumes. The second is the average of the discounts (AD), which evaluates the effectiveness and stability of the placements.

| Method | IoU_30 | AD_30 |
| :--- | :--- | :--- |
| Learned with IoU | 0.266 (0.026) | 0.584 (0.064) |
| Learned with DIoU | 0.303 (0.029) | 0.791 (0.058) |
| Random | 0.125 (0.027) | 0.738 (0.060) |
| Random (goal) | 0.232 (0.025) | 0.507 (0.064) |
| Cross-correlation | 0.27 (0.024) | 0.769 (0.046) |

## 5. Conclusion and Future Works
The major achievement of this work was to develop a setup in which a dry stacking policy can be learned without any previously acquired models of the environment. An agent is able to learn from scratch a policy that captures the goal of the environment and its dynamics. The emerged behavior is, to some extent, consistent with dry stacking theory [20]. The agent learned the policy using a model-free approach in simulation, which can be directly used in extra-terrestrial environments since the agent is not based on pre-existent models. Our data-driven approach is more suitable for ISRU.