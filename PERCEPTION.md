### Perception and Sensor Data Processing

🔍 I analysed cone detections from the perception stack and studied patterns in false positives.  
🎯 The goal was to identify consistent behaviours across sensors and scenes and design filtering logic to improve cone based track boundary reliability.  
📈 The strongest pattern was found in the number of points per cone cluster relative to distance from the lidar, which enabled threshold based filtering that removed invalid detections before feeding downstream modules.

![Perception Result 1](/media/perception1.png)  
![Perception Result 2](/media/perception2.png)

📉 This resulted in roughly 50 percent reduction in false positive cone detections.

![Perception Result 3](/media/perception3.png)



