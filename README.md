# autonomous_racecar
Putting ros-enabled Jetson nano on Losi RC Car that I have. Sensor being used is an Intel Realsense d435i that will be used for SLAM on this platform.

General Information on Mobile Robot Setup: http://wiki.ros.org/navigation/Tutorials/RobotSetup

Useful Resources:

1. http://wiki.ros.org/move_base - Knits together the local and global planner (map goal --> cmd_vel)

2. http://wiki.ros.org/teb_local_planner - Local Planner

3. http://wiki.ros.org/global_planner - Global Planner

4. https://groups.google.com/forum/#!topic/linorobot/WRIAlba7Siw - Good discussion of use with these planners

5. http://wiki.ros.org/ackermann_steering_controller - ACkerman Steering Controller (cmd_vel --> motor commands, tf)
