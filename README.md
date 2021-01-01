# ArUco-markers-with-OpenCV-and-Python

## What is ArUco
- Similar to AprilTags, **ArUco markers are 2D binary patterns** that computer 
vision algorithms can easily detect.

## ArUco Usability
1. Camera calibration
1. Object size estimation
1. Measuring the distance between camera and object
1. 3D position
1. Object orientation
1. Robotics and autonomous navigation
1. etc.

## ArUco over AprilTag
1. ArUco markers are **built into the OpenCV library** via the **cv2.aruco** 
submodule (i.e., we don’t need additional Python packages).
1. The OpenCV library itself can **generate ArUco markers** via the 
**cv2.aruco.drawMarker** function.
1. There are **online ArUco generators** that we can use if we don’t feel like 
coding (unlike AprilTags where no such generators are easily found).
1. There are **ROS (Robot Operating System) implementations** of ArUco markers.
1. And from an implementation perspective, ArUco marker detections tend to be 
**more accurate**, even when using the default parameters.

## References
1. https://www.pyimagesearch.com/2020/12/14/generating-aruco-markers-with-opencv-and-python/
1. https://www.pyimagesearch.com/2020/12/21/detecting-aruco-markers-with-opencv-and-python/
1. https://www.pyimagesearch.com/2020/12/28/determining-aruco-marker-type-with-opencv-and-python/
