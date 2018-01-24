development version for the driverless car. Right now only the simulation environment is progressing.
To start the simulation use: roslaunch mybot_gazebo mybot_world.launch
At first all the joints are moving freely -> start the joint controller: roslaunch mybot_control mybot_control.launch
Now you can control all the individual joints by starting the RQT tool: rosrun rqt_gui rqt_gui
How to use the rqt_gui see here:
http://gazebosim.org/tutorials/?tut=ros_control (lower middle of the page)

todo:
-vehicle seems to be slightly crooked? 
-both front tires are fixed and the hinge is still revolute no revolute2 joint. 
-still somehow jerky? 

While trying to run the controller for gazebo the following error occurs:
"Controller Spawner couldn't find the expected controller_manager ROS interface"
Solution still not found! Any suggestions?
