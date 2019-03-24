---
layout: post
title:  "Fire Fighting Using Machine Vision and Robotics"
date:   2019-03-24 12:19:28 +1100
categories: DSI -5 Update
---
<h1><strong>Problem Statement:</strong></h1>
To detect the fire on the shop floor and extinguish it by sending a robot to it.
<h1><strong>Requirements: </strong></h1>
<ol>
<li>To develop and test the machine vision algorithm to detect the fire in a video image.</li>
<li>To reduce the false alarm rate.</li>
<li>To send the robot to appropriate co-ordinates without it getting inside the fire.</li>
</ol>

<h1><strong>Design Solution:</strong></h1>
A web camera installed at the appropriate location is hooked up with a computer running machine vision algorithm. The machine vision algorithm detects the fire using intensity and colour information to reduce the false alarms and performs edge detection to find the edge of the fire. A canny edge detection method is used with threshold determined by training the model on different images in the fire. The thresholds on color are best separated using the HSV color space instead of RGB. Combination of both the algorithms give the edge of the brightest fire in the image. The coordinates of fire nearest to the robot are extracted and the robot is given instruction in terms of angle and distance to the fire. The robot is then sent to the coordinates, releases fire extinguishing material (CO2) and come back to original position. Th entire project is done using Image Processing Toolbox in MTALAB. The robot is designed around Philips 8 bit Microcontroller. The output of Image processing and the robot is shown in the Figure below. It can be ssen that the algorithm does not detect very strong source of blue light near the fire. 

![Matlab_Image](/assets/Matlab_Image.png)
 
<h1><strong>Conclusion</strong></h1>
In this project, it is found that by using image processing the exact location of the fire can be detected remotely, accurately and instantly by installing a camera at a suitable location and processing image at the remote terminal. After analysing different methods for fire detection, it can be concluded that intensity-based fire detection approach after colour detection gives the highest fire detection rate and the lowest number of false alarms. The robot based on Philips 8-bit microcontroller is designed and interfaced with PC using UART. 








