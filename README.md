<h1 align="center">Robotics-Assignment</h1>

<div align='center'><img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZmh3NHd3Z2J5dG04NmZ0azVzYXFmODVtNmdtb3dwcnEwdTBxZHA0aiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/58OujxlE7e19Mjv0gj/giphy.webp" alt="Logo" width="300"/></div>

## 📝 Table of Contents

- [ Requirment 1](#Requirment1)
- [ Requirment 2](#Requirment2)
  


##  Requirment 1 <a name = "Requirment1"></a>

### How It Works
1. The `laser_measurments` function:
   - Converts the input map to grayscale.
   - Casts laser rays from the robot's position at angles ranging from -125° to 125°.
   - Calculates the distance to obstacles and the endpoint of each laser beam.
   
2. The `draw` function:
   - Visualizes the robot's position and orientation.
   - Plots the laser beams and obstacle endpoints on the map.

Results:


<div align='center'><img src="./results/req1_1.png" alt="img1" width="450"/>  <img src="./results/req1_2.png" alt="img2" width="450"/></div>


##  Requirment 2 <a name = "Requirment2"></a>
### How It Works
1. Finding the Most Likely Pose:
The function `find_most_likely_pose()` searches the entire map for the pose with the highest probability. It iterates over possible positions (x, y) and orientations theta to find the best match.

2. Visualization:
The function `draw_pose()` displays:
The robot's best pose on the map.
The likelihood map showing the probability distribution.


Results:
<div align='center'><img src="./results/req2_1.png" alt="img1" width="1000"/></div>
<div align='center'><img src="./results/req2_2.png" alt="img1" width="450"/><img src="./results/req2_3.png" alt="img1" width="450"/></div>

