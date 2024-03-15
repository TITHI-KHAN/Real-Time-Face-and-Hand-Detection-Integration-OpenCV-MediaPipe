# Real-Time-Face-and-Hand-Detection-Integration-OpenCV-MediaPipe

## To run the code, please either use "Visual Studio" or "Jupyter Notebook from Anaconda Navigator".

### For the project video, please check the "Project Video" file. Thank you.

![3_1](https://github.com/TITHI-KHAN/Real-Time-Face-and-Hand-Detection-Integration-OpenCV-MediaPipe/assets/65033964/884f9e03-b9b7-468f-9656-d5f1e964ac40)

![3_2](https://github.com/TITHI-KHAN/Real-Time-Face-and-Hand-Detection-Integration-OpenCV-MediaPipe/assets/65033964/02f68ce8-8177-4e82-b595-50f79a2d25c6)

![3_3](https://github.com/TITHI-KHAN/Real-Time-Face-and-Hand-Detection-Integration-OpenCV-MediaPipe/assets/65033964/a2357f8a-0c4a-4e38-87f9-722624dbaa9c)

![3_4](https://github.com/TITHI-KHAN/Real-Time-Face-and-Hand-Detection-Integration-OpenCV-MediaPipe/assets/65033964/fcec1b1a-08e7-4bf5-b2f9-b48f4ecec5d7)

![3_5](https://github.com/TITHI-KHAN/Real-Time-Face-and-Hand-Detection-Integration-OpenCV-MediaPipe/assets/65033964/5d281f09-01ee-43dd-ad5d-4f9409230e6d)


### Combines both OpenCV and MediaPipe for face and hand gesture detection.
### Employs the Haar cascade classifier in OpenCV for face detection.
### Utilizes the MediaPipe Hands module for hand gesture detection.

This Python script combines the detection of both face and hand gestures using OpenCV and MediaPipe.

Here's a breakdown of what the script does:

1. It imports the necessary libraries: `cv2` for OpenCV and `mediapipe` for hand gesture detection.

2. The script initializes the MediaPipe hands module for hand gesture detection and the drawing utility for visualization.

3. Two functions are defined:
   - `detect_face()`: This function detects faces in the input frame using the Haar cascade classifier.
   - `detect_hand()`: This function detects hand gestures in the input frame using the MediaPipe hands module.

4. The main function (`main()`) initializes the webcam capture and enters a loop to continuously capture frames.

5. Within the loop:
   - Frames are captured from the webcam.
   - The `detect_face()` function is called to detect faces and draw rectangles around them.
   - The `detect_hand()` function is called to detect hand gestures and draw landmarks.
   - The resulting frame, with both face and hand detections, is displayed in a window named 'Face and Hand Detection'.
   - The loop breaks when the 'q' key is pressed.

6. Finally, the script releases the webcam capture and closes all OpenCV windows.

The script provides a simple yet effective demonstration of real-time face and hand gesture detection, which can be utilized in various applications such as augmented reality, virtual reality, and human-computer interaction systems.
