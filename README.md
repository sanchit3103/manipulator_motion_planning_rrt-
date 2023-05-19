# Motion planning of a 2 DOF manipulator using RRT* algorithm

<p align="justify">
This project focuses on designing an RRT* implementation for motion planning of a 2 DOF robotic manipulator for finding feasible paths across multiple waypoints in an environment equipped with obstacles. The configuration space of the robot was plotted to show the collision free and collision regions. The RRT* algorithm was implemented in the configuration space. Among multiple possibilities of a path to the waypoint in the tree, the shortest path to reach the target was selected. The first path found and the final path selected are shown in the results below.
</p>

## Project implementation in form of GIF file

<p align="justify">
The GIF below shows the implementation of RRT* algorithm for motion planning of the manipulator. First path found is highlighted in blue and final path selected is highlighted in red. 
  
</p>

<p align="center">
  
  <img src = "https://github.com/sanchit3103/manipulator_motion_planning_rrt-star/assets/4907348/7305de86-5261-40b4-9ec7-e78690aa49d6)" height="400"/>

</p>

## Details to run the code

* <b> main.ipynb: </b> Notebook which includes the plotting of configuration space and implementation of RRT* algorithm.
