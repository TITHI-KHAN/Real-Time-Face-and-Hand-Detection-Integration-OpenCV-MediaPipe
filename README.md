# Real-Time-Face-and-Hand-Detection-Integration-OpenCV-MediaPipe

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
