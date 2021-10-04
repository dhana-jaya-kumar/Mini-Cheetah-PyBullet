# Mini-Cheetah-PyBullet
A PyBullet gym Environment for Mini Cheetah 

<p align="center">
   <img width="360" height="300" src="https://github.com/dhanajaya78/Mini-Cheetah-PyBullet/blob/main/media/RoughTerrain.png">
   <img width="360" height="300" src="https://github.com/dhanajaya78/Mini-Cheetah-PyBullet/blob/main/media/Stairs.png">
</p>


<p align="center">
   <img width="700" height="400" src="https://github.com/dhanajaya78/Mini-Cheetah-PyBullet/blob/main/media/FPVCam.gif">
</p>


## To Do:

- [x] Check MPC implementation of pybullet and the simulation bed configuration.
- [x] Import Mini Cheetah in the place of Laikago, do the requied system indentification and test the MPC controller.
- [x] Clean and develop the simulation bed into a gym env with appropriate functions and classes.
- [x] Build a independent Domain Randomizer class, to work hand in hand with the environment.
- [x] Integrate, test and verify environment.
- [x] Add functions for capturing image as the observation.


## References

### Papers:

1. From Pixels to Legs: Hierarchical Learning of Quadruped Locomotion. [Paper](https://arxiv.org/abs/2011.11722), [CoRL Presentation](https://youtu.be/o4PDEnqjT0I)
2. Vision-aided Dynamic Exploration of Unstructured Terrain(in Mini Cheetah). [Paper](https://ieeexplore.ieee.org/document/9196777), [Video](https://youtu.be/Tv7Vd-gF11s)

### Paper and Code:

1. [Previous Implementations - Github](https://github.com/topics/mini-cheetah)
2. [MPC Controller in Pybullet](https://github.com/google-research/motion_imitation/tree/master/mpc_controller)
3. [SlopedTerrainLinearPolicy(for DR)](https://github.com/StochLab/SlopedTerrainLinearPolicy)
4. [Sim-to-Real: Learning Agile Locomotion For Quadruped Robots(DR implementations of minatour)](https://github.com/bulletphysics/bullet3/tree/master/examples/pybullet/gym/pybullet_envs/minitaur/envs)
5. [Active Domain Randomization](https://paperswithcode.com/paper/active-domain-randomization)
