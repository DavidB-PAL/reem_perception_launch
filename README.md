### ROS Node: reem_perception_launch
Copyright (c) 2013, David Butterworth, PAL Robotics S.L. 
<br>
<br>
Launch file for the perception system of the REEM robot. 

Ultimately, this would be integrated into one of the robot's main packages. <br>
This launch file is reference by the tabletop perception and manipulation pipeline.
<br>

<br>
Loads OpenNI, PointCloud Snapshotter, Filter, OctoMap, Collision Map & Planning Scene.

Can be easily used in simulation, or with the real robot. <br>
Makes it easy to disable the snapshotter system and use a constant PointCloud feed.

In ROS Fuerte, the PR2 has launch files for perception in the arm_navigation package, amongst other places, but this may not be ideal.
<br>

<br>
**Required ROS packages:** <br>
reem_common     (DavidB-PAL fork, not yet merged with Master 15/3/13) <br>
reem_simulation (DavidB-PAL fork, not yet merged with Master 15/3/13) <br>
reem_arm_navigation (DavidB-PAL fork, not yet merged with Master 15/3/13) 

reem_manipulation_worlds <br>
reem_head_scan_action <br>
pointcloud_snapshotter
<br>

<br>
**Usage:** <br>

Normally this is used as part of a larger system. <br>
The reem_move_arm_action includes a demo showing how to build a Collision Map and move the arm whilst avoiding obstacles.

