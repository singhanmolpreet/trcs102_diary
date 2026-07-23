# Day 28 - OpenCV Drawing, Image Filtering, and Camera Operations

## Date

Day 28 of ML Training

## Objective

To learn how to draw shapes and text on images, apply basic image filtering techniques, and capture images and videos using a webcam with OpenCV.

## Topics Covered

### 1. Drawing on Images

* Drawing a line using `cv2.line()`
* Drawing a circle using `cv2.circle()`
* Customizing color, thickness, and position

### 2. Adding Text

* Writing text on an image using `cv2.putText()`
* Selecting font style
* Adjusting font size, color, and thickness

### 3. Image Filtering

* Image sharpening using convolution kernels
* Median Blur using `cv2.medianBlur()`
* Gaussian Blur using `cv2.GaussianBlur()`
* Comparing sharpening and smoothing techniques

### 4. Camera Operations

* Accessing the webcam using `cv2.VideoCapture()`
* Displaying live video feed
* Capturing frames from the camera

### 5. Video Recording

* Saving webcam video using `cv2.VideoWriter()`
* Configuring video codec, frame size, and frame rate
* Releasing camera and video resources properly

## Activities Performed

* Drew lines and circles on images.
* Added custom text to images.
* Applied sharpening, median blur, and Gaussian blur filters.
* Captured live video from the webcam.
* Recorded and saved webcam footage as a video file.

## Key Learnings

* OpenCV provides simple functions for drawing shapes and annotating images.
* Image sharpening enhances edges, while blurring techniques help reduce noise.
* Median Blur is effective for removing salt-and-pepper noise, whereas Gaussian Blur smooths images by reducing high-frequency details.
* `VideoCapture()` enables real-time image acquisition from a webcam, while `VideoWriter()` allows processed or raw video to be saved.

## Summary

Day 28 focused on practical image processing and computer vision using **OpenCV**. The session covered drawing geometric shapes, adding text, applying image filters, capturing live webcam video, and recording videos. These techniques form the basis for many real-time computer vision and image processing applications.
