# stepDetectionIMU
Pedestrian Dead Reckoning using Step Estimation method on IMU data


One way to implement Pedestrian Dead Reckoning algorithm is by using Step Estimation on IMU data. Step estimation involves different stages including first, Step Detection technique. In Step Detection, IMU features are extracted to detect individual's steps. This involves setting a threshold or pattern recognition techniques (such as peak detection) to identify the start and end of each step. Second, Step counting where the algorithm keeps track of the step count whenever a step is identified. Third, Orientation and heading where the direction of movement is considered. Fourth, psotion estimation where the individual's step length, step count, initial position and orientation are integrated over time to estimate the final position of the individual. 
