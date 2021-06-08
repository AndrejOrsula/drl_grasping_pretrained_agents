# Pre-trained Agents for [AndrejOrsula/drl_grasping](https://github.com/AndrejOrsula/drl_grasping)

This submodule contains pre-trained agents for [AndrejOrsula/drl_grasping](https://github.com/AndrejOrsula/drl_grasping), which can be directly enjoyed without needing to train them from scratch. You can also continue their training with your desired choice of hyperparameters.

Currently, the following combinations are available in this repository for the sake of reduced repository size.

| Environment                     	| Robot   	| Algorithm 	|
|---------------------------------	|---------	|-----------	|
| Grasp-OctreeWithColor-Gazebo-v0 	| panda   	| TQC       	|
| Grasp-OctreeWithColor-Gazebo-v0 	| ur5_rg2 	| SAC       	|
| Grasp-Octree-Gazebo-v0          	| ur5_rg2 	| TQC       	|

Feel free to open an issue if you want to try some specific pre-trained agents as combinations of robot, algorithm, environment and different approaches (demonstrations, curriculum, sharing of feature extractor, ...). I might have already trained the one you are looking for and share it.
