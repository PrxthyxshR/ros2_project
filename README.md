# Batch A Team 15
# ros2_project

## TEAM MEMBERS

    -Avinash Madhu [CB.EN.U4AIE21006]
    -Lakshmi R R[CB.EN.U4AIE21027]
    -M S Sree Mridhula[CB.EN.U4AIE21028]
    -Prathyush Rajagopal[CB.EN.U4AIE21043]

## Project Description
This course is focus on Maze Solving behavior of robot In a Simulation based on ROS2. Computer Vision is the key focus with integrated important robotics algorithms of Motion Planning . The type of robot we will be using is Differential Drive Robot with a caster wheel . Course is structured with below main headings .

1. Custom Robot Creation

2. Gazebo and Rviz Integerations

3. Localization

4. Navigation

5. Path Planning

## Implementation of the Project

- Simulation Part

  *Creation Custom Robot Design in Blender ( 3D modeling )

  *Bringing Maze Bot into ROS Simulation powered by Gazebo and RVIZ

  *Drive your robot with Nodes

  *Add Sensor for better perception of Environment

  *Build different Mazes to be solved

- Algorithm Part

  *Localization with Fore and Back ground extraction

  *Mapping with Graphs Data Structure

  *Path Planning with
     
      +Dijikstra
      +DFS Trees
      +Min Heap
      

### Navigation while avoiding Obstacles and GTG behavior


## Codes to be Typed in Terminal to run final maze solving model
### Terminal 1 
     colcon build --allow overriding maze_bot
     source ~/path_planning_ws/install/setup.bash
     ros2 launch maze_bot maze_2_robot_camera.launch.py


### Terminal 2

     source ~/path_planning_ws/install/setup.bash
     ros2 run maze_bot maze_solver

