# Project Part 3 - Autonomous Indoor Search
#### Cole Petit
#### CS-475-001

---------

### __Controller Design__

The controller was designed to follow walls. The robot would seek out a wall, position it to its right, and advance along it, turning when necessary. Being imperfect however, it would sometimes not sense small passageways and skip over the according areas. Additionally, even a perfect wall-follow controller would not yield excellent coverage because it misses wide open spaces. If there were an apriltag in the environment, the robot would have had a much higher chance of finding it if it were restricted to walls than if it could be anywhere

### __Results__

The controller performed well in its capacity as a wall-follow. However, 10 minutes was not always enough time for the robot to traverse the entire perimiter of the environment. See the results (coverage) of each trial below:

- Environment 1, Trial 1: 50.62 %
- Environment 1, Trial 2: 60.49 %
- Environment 1, Trial 3: 53.09 %
- Environment 2, Trial 1: 42.35 %
- Environment 2, Trial 2: 46.94 %
- Environment 2, Trial 3: 45.92 %

The ROS2 Cartographer was not used for this project, but rather individual floor tiles were marked off as they were visited. The coverage maps are attached in this repository.