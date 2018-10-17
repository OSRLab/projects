# Welcome to
```
 ██████╗ ███████╗██████╗ ██╗      █████╗ ██████╗
██╔═══██╗██╔════╝██╔══██╗██║     ██╔══██╗██╔══██╗
██║   ██║███████╗██████╔╝██║     ███████║██████╔╝
██║   ██║╚════██║██╔══██╗██║     ██╔══██║██╔══██╗
╚██████╔╝███████║██║  ██║███████╗██║  ██║██████╔╝
 ╚═════╝ ╚══════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═════╝

██████╗ ███████╗███████╗███████╗ █████╗ ██████╗  ██████╗██╗  ██╗
██╔══██╗██╔════╝██╔════╝██╔════╝██╔══██╗██╔══██╗██╔════╝██║  ██║
██████╔╝█████╗  ███████╗█████╗  ███████║██████╔╝██║     ███████║
██╔══██╗██╔══╝  ╚════██║██╔══╝  ██╔══██║██╔══██╗██║     ██╔══██║
██║  ██║███████╗███████║███████╗██║  ██║██║  ██║╚██████╗██║  ██║
╚═╝  ╚═╝╚══════╝╚══════╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝
```

This is a work in progress. Void where prohibited. No purchase necessary.


So the idea is to import the towers into Gazebo and we were successful in doing so. I think I used the python blender API to resize the mesh since collada files use meters, not millimeters, as the default unit. So that worked and I think there's a big of documentation or at least the resized mesh here. Pretty sure my_mesh.world is the template I have for including meshes into gazebo.

So I need to learn how to plug in the work I'm doing with Reinforcement Learning and Computer Vision into ROS in the form of an action server that can give updates to the trajectory to MoveIt. I might not even end up using MoveIt, which I probably will on some level bc it's optimized to do lots of things for industrial robots, the kind of robots I'm planning on using AKA serial kinematic chain manipulators).

So I guess I'm planning on using some of the functionality of MoveIt bc I want to use the ROS packages for an industrial robot arm without having to redo it myself the first go around, but yeah I eventually will want to start working on incorporating force feedback into the control algorithms.
