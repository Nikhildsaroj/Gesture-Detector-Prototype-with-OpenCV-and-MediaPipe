# Gesture Detector Prototype with OpenCV and MediaPipe

## Introduction
Gesture detection is a computer vision task that involves identifying and annotating frames in a video where a thumbs-up hand gesture is present. This documentation outlines the approach, implementation details, and usage instructions for detecting thumbs-up gestures in a video using the MediaPipe Hands framework and OpenCV.

### Desired Gesture Representation:
The desired gesture representation chosen for this task is a single image depicting a thumbs-up gesture.
![Thumbs-Up Gesture](https://media.istockphoto.com/id/1403409986/photo/closeup-of-unknown-group-of-diverse-businesspeople-showing-thumbs-up-sign-and-symbol-in.jpg?s=1024x1024&w=is&k=20&c=FE8uWtuRVU3TZBD9Mv2sljrHn8Zyrr39sBNLo2IiCi8=)

### Test Video Selection:
- Two test videos were chosen to evaluate the performance of the gesture detection model.
- The first test video was obtained from a website, representing a standard scenario commonly encountered in real-world applications. [Link](/content/drive/MyDrive/hand/test2.mp4)
- The second test video was created by myself by merging different video clips, including one captured by me, to assess the model's robustness across diverse video compositions and backgrounds. [Link](/content/drive/MyDrive/hand/test5.mp4)
- By using a variety of test videos, we aim to validate the model's effectiveness in detecting thumbs-up gestures under different environmental conditions, lighting variations, and hand movements.
- The inclusion of user-captured video adds a personalized touch and ensures that the model can generalize well to various input sources encountered in practical use cases.

## Data Processing
In this section, I'll outline how the input and test video data are preprocessed and prepared for analysis throughout our discussion.

## Model Selection/Development
In the Gesture Detector prototype, we utilized the MediaPipe Hands framework provided by Google, which offers a pre-trained hand landmark model for real-time hand detection and tracking.

## Detection Algorithm
The detection algorithm employed in the Gesture Detector prototype involves the following steps:

## Annotation
Frames where the desired gesture is detected are annotated by overlaying the text "DETECTED" in bright green on the top right corner of the output frames.

## Implementation Details
In this section, we'll delve into the implementation details of the prototype.

## Challenges Faced and Solutions
This section discusses the challenges encountered during the development process and the corresponding solutions.

## Video Processing
- Hand Landmark Detection in Test Video
- Background Subtraction in Test Video
- Grayscale Visualization in Test Video

## Code Sections
1. Install library
2. Thumbs-Up Gesture Detection in Image
3. Data Augmentation for Thumbs-Up Gesture Images
4. Hand Landmark Detection in Augmented Thumbs-Up Gesture Images
5. Hand Landmark Detection in Test Video
6. Background Subtraction in Test Video
7. Grayscale Visualization in Test Video
8. Thumbs-Up Gesture Detection in Test1 Video
9. Thumbs-Up Gesture Detection in Test2 Video

## Conclusion
Thumbs-up gesture detection utilizing MediaPipe Hands and OpenCV presents a robust solution for identifying and annotating thumbs-up gestures within videos. The prototype demonstrates high accuracy and can be applied to various real-world applications.

