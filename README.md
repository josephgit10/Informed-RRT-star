#### Project 5 #### 
### ENPM 661 ####  
### Planning for Autonomous Robotics ###


Author: Pritom Raymond Leo Gomes(pgomes10@umd.edu),  Joseph Thomas (joseph10@umd.edu)and Amogh Wyawahare (wamogh@umd.edu) ---> University of Maryland Masters Robotics pgomes10@umd.edu
        
****** The folder contains all the python scripts and ros code


Instructions:
(Use ROS to launch the code in gazebo )

The code is designed by assigning a fixed initial and final position

To run the code:
1. install ros and turtlebot3 and their dependencies
2. extract the zip file. 
3. place the rrt_star package in your workspace folder. Now type cd <your_ws> to go into the workspace and type catkin_make to build all packages. 
4. source devel/setup.bash from catkin_ws  
5. run the launch file using “roslaunch rrt_star demo.launch x:=0 y:=0 yaw:=0”. 
6. here the values of x and y and yaw will update the desired initial orientation of bot. 
7. A new terminal should pop up where it will ask for the start(x,y) and goal(x,y). 
8. Then, the start coordinates should be the same as the values of x, y specified in the roslaunch command and the goal coordinates can be changed as desired. Pressing enter will form the final result. of the 2D implementation showing the optimal path taken by the algorithm.
