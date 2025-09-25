# real-time_image_processing_project

## Abstract
This project demonstrates **real-time image processing** using **ROS (Robot Operating System)** and **C++**. It subscribes to a ROS image topic and detects changes between consecutive frames, allowing immediate response to dynamic events. This system is ideal for applications in robotics, surveillance, motion detection, and interactive robotics experiments.


## Features
- **Real-time image subscription:** Continuously receives images from a ROS topic.  
- **Change detection:** Highlights differences between frames for immediate response.  
- **Efficient C++ implementation:** Optimized for real-time performance.  
- **Seamless ROS integration:** Can be combined with other nodes, sensors, or robotic systems.  


## Workflow
1. **Node Initialization:**  
   - Launch the ROS node and subscribe to the desired image topic.

2. **Image Acquisition:**  
   - Receive images using `sensor_msgs/Image` in real-time.

3. **Image Processing:**  
   - Detect changes between consecutive frames.  
   - Apply image processing algorithms (filters, edge detection, etc.) as needed.

4. **Output / Action:**  
   - Display processed images in a window.  
     

## Results


