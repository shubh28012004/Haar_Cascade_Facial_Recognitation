# Haar_Cascade_Facial_Recognitation
Discuss about recognizing objects in consumer images, analyzing human activity in video using tools / platforms.

## AIM: To recognize objects in consumer images and analyze human activity in videos using OpenCV and Haar-Cascade classifiers.
Objectives:
1) Access the camera integrated with a Desktop/Laptop using OpenCV in Python.
2) Capture video and store it.
3) Perform different operations frame-wise on captured images/video using Haar-Cascade.
4) Operations include blurring, negative, enhancement, etc.

Theory:
- **Camera Basics**: 
  - OpenCV allows interfacing with a webcam or external camera using `cv2.VideoCapture(0)`.
  - Frames are read using `cam.read()`, where `ret` indicates success, and `frame` stores the captured image.
  - `cv2.VideoWriter` is used to save videos.

- **Haar Cascade**:
  - A machine learning object detection method used to identify objects in images.
  - Uses XML files for detecting predefined objects (e.g., face, eyes, full body, etc.).
  - Works in multiple stages to filter features progressively.
  - Positive images – These images contain the images which we want our classifier to identify.
  - Negative Images – Images of everything else, which do not contain the object we want to detect.


