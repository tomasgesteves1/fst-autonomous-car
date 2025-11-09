## Estimation and Mapping

📡 These modules were presented by me in the Engineering Design competitions, where teams present their technical solutions and development work.  
🥇 We achieved 1st place in both Portugal and Spain competitions.

### State Estimation
For state estimation we used an Extended Kalman Filter with the following architecture:

![EKF Architecture](/media/slam/ekf.png)

### SLAM
For simultaneous localization and mapping we used a graph based SLAM approach with pose graph optimization using the g2o library:

![SLAM Architecture](/media/slam/graphslam.png)

### My Contributions
🔍 Visualization tooling for debugging track and map consistency  
📊 Accuracy evaluation studies across multiple dynamic runs  
🧠 Loop closure optimization strategies

Loop closure was essential for the system to recognize previously visited track regions and eliminate cumulative drift in mapping and state estimation.

Before loop closure:

![Before Loop Closure](/media/slam/loopclosure1.png)

After loop closure:

![After Loop Closure](/media/slam/loopclosure2.png)
