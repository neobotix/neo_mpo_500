# ROS configuration and launch files for Neobotix MPO-500

This package contains configuration and launch files for Neobotix MPO-500.

![Neobotix MPO-500](http://www.neobotix-roboter.de/fileadmin/_processed_/a/1/csm_Mecanum-Roboter-MPO-500-Hauptansicht_d84bcd2932.jpg) ![Neobotix MMMO-500](http://www.neobotix-roboter.de/fileadmin/_processed_/2/1/csm_MMO-500-UR10-Main_8682e85e32.jpg)

The [MPO-500](http://www.neobotix-robots.com/mecanum-robot-mpo-500.html) is an omnidirectional robot with Mecanum wheels for all kinds of service robotics and research

# Contact information

For more information please visit our website at www.neobotix-robots.com. 
If you have any questions, just get in touch with us:
* General information: http://www.neobotix-robots.com/company-contact.html
* ROS related questions: ros@neobotix.de

# Installation

1. Create a catkin workspace (![tutorial](http://wiki.ros.org/catkin/Tutorials/create_a_workspace))

2. download all packages listed under "Additionally required Neobotix-ROS-Packages" into your workspace

3. IMPORTANT! delete all not used packages downloaded in step 2!

4. install all packages listed under "Additionally required thid party ROS-Packages"

5. build your workspace


## Additionally required Neobotix-ROS-Packages:

Hardware connection: ![neo_relayboard_v2](https://github.com/neobotix/neo_relayboard_v2)

Kinematic: ![neo_mecanum_kinematics](https://github.com/neobotix/neo_kinematics_mecanum)

Laserscanner: ![cob_sick_s300](https://github.com/neobotix/neo_driver)

Scan-Merge: ![cob_scan_unifier](https://github.com/neobotix/neo_driver)

Teleoperation: ![neo_teleop](https://github.com/neobotix/neo_control)

Msgs: ![neo_msgs](https://github.com/neobotix/neo_msgs)

Srvs: ![neo_srvs](https://github.com/neobotix/neo_srvs)

## Additionally required thid party ROS-Packages:

Joystick: ![joy](http://wiki.ros.org/joy)

MoveBase: ![move_base](http://wiki.ros.org/move_base) and ![move_base_msgs](http://wiki.ros.org/move_base)

SLAM: ![gmapping](http://wiki.ros.org/gmapping)

AMCL: ![amcl](http://wiki.ros.org/amcl)

## Usage:

1. edit the configuration of each ROS-Node to our needs 

2. use the bringup.launch file for basic startup

3. use the navigation.launch file for starting up MoveBase and SLAM or AMCL

### ROSlaunch files:

Bringup: ![mpo_500_bringup.launch](https://github.com/neobotix/neo_mpo_500/blob/indigo/launch/mpo/mpo_500_bringup.launch)

Navigation ![mpo_500_nav.launch](https://github.com/neobotix/neo_mpo_500/blob/indigo/launch/mpo/mpo_500_nav.launch)


### Configuration:

For each used ROS-Node there is a Folder in configs



