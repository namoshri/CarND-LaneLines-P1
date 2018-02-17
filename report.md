# **Finding Lane Lines on the Road** 

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.


My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I .... 

In order to draw a single line on the left and right lanes, I modified the draw_lines() function:
* Calculated slop of each hough line
* based on slope decided if line belogs to right lane or left lane
* Beween right/left lanes, max+min of X and y calculated to draw stright line in ROI.

Image and video output's are html files and uploaded too.


### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be, extrapolation could go inaccurate in case of bigger curve road/lane.


### 3. Suggest possible improvements to your pipeline

Figure out how to draw transparent line mentioned in sample video.
