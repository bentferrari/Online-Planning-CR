# Offline_Online_motion_planning_for_continuum_robots
This is the open-source code for "An Open-Source Snake Hole-Digging Inspired Safety-Critical Insertion
Planning and Replanning Framework for Continuum Robots".

Requirement: 1. MATLAB, 2. MATLAB APP: Optimization Toolbox, 3. MATLAB APP: Global Optimization Toolbox

The motion planner is divided into two parts:

1. Offline_planner 2. Online_replanner
     
In the offline_planner folder, we have two sub-folders:

    1.1 final_configuration_planning and 1.2 insertion_planning.
    
Tasks:
1. Find the final configuration in an environment→Run

   \offline_planner\final_configuration_planning\shape_optimization.m
   
2. Find the insertion motions in an environment→Run
   
   \offline_planner\insertion_planning\insertion_planner.m
   To see the demo, you can run \offline_planner\insertion_planning\plot_insertion.m

3. Online replanning with moving obstacles→Run

   \online_replanner\clf_cbf_qp_main.m

Demo at:https://www.youtube.com/watch?v=WsuaO7YvfqE
