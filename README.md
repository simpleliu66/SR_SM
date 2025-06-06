# An Action Model based Efficient and Accurate Scene Recognition Method for Service Robot Topological Semantic Mapping

This repository includes the demonstrations of our proposed method called **An Action Model based Efficient and Accurate Scene Recognition Method for Service Robot Topological Semantic Mapping**. 

:hourglass_flowing_sand: We will publish the source code and data once the paper is accepted. 

**Abstract**
Given the limitations of current scene recognition methods in efficiency, redundancy, and accuracy for service robot topological semantic mapping, this paper proposes a scene recognition method based on an action model. Considering the similarity of images captured from the adjacent topological nodes and the low-quality image caused by the uncertain node position and observation direction of the robot, we develop an action model using a deep Q-learning network (DQN). This model enhances accuracy and efficiency by deciding whether to (1) inherit the scene type from the preceding node without re-recognition or (2) adjust the robot’s observation angle to capture a more informative image. A rule-based reward function integrated with a scene score model enables simultaneous learning of similarity assessment and viewpoint adjustment policies. Furthermore, a training strategy based on generated path is proposed to provide sufficient data for training the action model.	Extensive comparative experiments in simulated environments demonstrate that our method surpasses state-of-the-art approaches in both recognition accuracy and efficiency. Deployment on a mobile robot confirms its practical efficacy, achieving precise and efficient scene recognition across diverse real-world environments.

# Framework

<p align="center">
<img src="https://github.com/simpleliu66/SR_SM/blob/main/img/intro.jpg" height= "250" width="800">
</p>

# Demonstration
## Some demos in [**Habitat**](https://aihabitat.org/datasets/hm3d/).
Demos of scene recognition for topological semantic mapping in three large and complex indoor environments: (1) 00847, (2) 00877, and (3) 00843 from Habitat, including maps, whether the scene recognition model is used, and the scene recognition result of each node.

https://github.com/user-attachments/assets/1642adef-5c63-4380-9b84-73b812d487b3
