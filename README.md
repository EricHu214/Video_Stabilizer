## Description
This is an implementation of a video stabilizer. The main file is a python notebook.

We experimented with naive stabilization (stabilizing fixed object in place) and optical flow stabilization using feature point motion estimation (stabilizing global camera motion).

Our attempt to mitigate videos with noisy motion with a deep learning disparity network did not produce good results

by Eric Hu, Hsiang-Chi(Jacky) Yang

## Results
![](https://github.com/EricHu214/Video_Stabilizer/blob/master/original%20video.gif)
![](https://github.com/EricHu214/Video_Stabilizer/blob/master/stabilized%20video.gif)

## Techniques
- Features detection and matching (SIFT)
- Optical Flow (Lucas-Kanade)
- Geometric transformations
- Neural Network/Stereo image Processing

## Reference
- GwcNet, Disparity map detection
https://github.com/xy-guo/GwcNet
- Homography Examples using OpenCV
https://www.learnopencv.com/homography-examples-using-opencv-python-c/
- OPENCV: Feature Matching
https://docs.opencv.org/master/dc/dc3/tutorial_py_matcher.html
- Homography by Dr. Gerhard Roth
http://people.scs.carleton.ca/~c_shu/Courses/comp4900d/notes/homography.pdf
- MeshFlow
http://www.liushuaicheng.org/eccv2016/meshflow.pdf
