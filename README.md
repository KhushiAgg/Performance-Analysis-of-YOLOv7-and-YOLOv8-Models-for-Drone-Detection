# Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection
Drone detection techniques are used to detect
unmanned aerial systems (UAS) also commonly known as drones. A
rapid increase in these drones has limited the airspace safety and so
the research for drone detection has emerged. This study compares
between the two widely used deep-learning models, previously used
YOLOv7 and the latest YOLOv8. The overall finding of this study
suggests that the YOLOv8 deep-learning model appears to be more
promising and may make valuable contributions on their own.

# Dataset Used
The YOLO Drone Detection Dataset, which is a collection of
pictures and annotations of drones shot in diverse outdoor
settings and taken from RoboFlow, is the dataset that was used.
This dataset includes approximately 3.5k training images, 1k
validation images and 510 testing images, each of which
includes a bounding box indicating where the drone is located in
the image.The dataset was made in order to recognise and track
drones using the real-time object detection technique YOLO
(You Only Look Once), which utilizes convolutional neural
networks (CNNs). Due to its quick detection time and great
accuracy, YOLO is a well-liked object identification technique.

Link of the dataset: https://universe.roboflow.com/vinitawale/drones-uav-yolov5/dataset/1

# YOLOv7 Output :
<img width = 250, height = 250, src = "https://github.com/KhushiAgg/Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection/blob/main/drone%20yolo%20v7%20results/v1img1.png"> <img width = 250, height = 250, src = "https://github.com/KhushiAgg/Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection/blob/main/drone%20yolo%20v7%20results/v1img2.png">
<img width = 250, height = 250, src = "https://github.com/KhushiAgg/Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection/blob/main/drone%20yolo%20v7%20results/v1img3.png">
<img width = 250, height = 250, src = "https://github.com/KhushiAgg/Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection/blob/main/drone%20yolo%20v7%20results/v1img4.png">
<img width = 250, height = 250, src = "https://github.com/KhushiAgg/Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection/blob/main/drone%20yolo%20v7%20results/v7vid1.png">
<img width = 250, height = 250, src = "https://github.com/KhushiAgg/Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection/blob/main/drone%20yolo%20v7%20results/v7vid2.png">

* YOLOV7 Confusion Matrix

<img width = 900, height = 800, src = "https://github.com/KhushiAgg/Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection/blob/main/drone%20yolo%20v7%20results/v7cm.png">

# YOLOv8 Output :
<img width = 250, height = 250, src = "https://github.com/KhushiAgg/Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection/blob/main/drone%20yolo%20v8%20results/v8img1.png"> <img width = 250, height = 250, src = "https://github.com/KhushiAgg/Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection/blob/main/drone%20yolo%20v8%20results/v8img2.png">
<img width = 250, height = 250, src = "https://github.com/KhushiAgg/Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection/blob/main/drone%20yolo%20v8%20results/v8img3.png">
<img width = 250, height = 250, src = "https://github.com/KhushiAgg/Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection/blob/main/drone%20yolo%20v8%20results/v8img4.png">
<img width = 250, height = 250, src = "https://github.com/KhushiAgg/Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection/blob/main/drone%20yolo%20v8%20results/v8vid1.png">
<img width = 250, height = 250, src = "https://github.com/KhushiAgg/Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection/blob/main/drone%20yolo%20v8%20results/v8vid2.png">
* YOLOV8 Confusion Matrix

<img width = 900, height = 800, src = "https://github.com/KhushiAgg/Performance-Analysis-of-YOLOv7-and-YOLOv8-Models-for-Drone-Detection/blob/main/drone%20yolo%20v8%20results/v8cm.png">

# Results
 We got the result that for 10 epochs YOLOv8 gave 50.16% accuracy
while YOLOv7 gave 48.16% accuracy making YOLOv8 more
promising for the task. As a practical application for future work,
we intend to deploy YOLOv8 on edge devices to achieve real-time
drone detection in critical security applications.
