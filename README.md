# Adaptive Swarm

![potential_surface](https://github.com/RuslanAgishev/adaptive_swarm/blob/master/figures/layered_planner/surface_potential_trajs.png)

## Package description
This project is a layered path planner algorithm to solve multiple agents navigation
problem in a cluttered environment.

The general path planning problem is divided into approximate global trajectory construction, which is further smoothed by a local path planning method.
The proposed approach provides a solution based on a leader-followers architecture with a prescribed formation geometry that adapts dynamically to the environment and avoids collisions.

The path generated by the global planner based on rapidly-exploring random tree (RRT) algorithm is corrected with the artificial potential fields (APF) method that ensures robots trajectories to be collision-free, reshaping the geometry of the formation when required by environmental conditions.
