# Real-Time-Object-Based-Drawing

1) Interactive Drawing Tool:

Real-time application that allows users to draw on a digital canvas by moving a blue object in front of a webcam.

2) Computer Vision Techniques:

Utilizes OpenCV for live video capture and image processing.

Implements color segmentation in the HSV color space to specifically detect blue objects.

3) Robust Object Tracking:

Uses morphological operations (opening and dilation) to reduce noise in the segmented image.

Applies contour extraction to identify and track the object's centroid across frames.

4) Digital Canvas Integration:

Draws continuous lines on an off-screen canvas based on the tracked blue object’s movement.

Supports dynamic drawing even when the object is farther from the camera (by lowering the contour area threshold).

5) User Interaction:

Integrated keyboard controls:

Press 'q' to quit the application.

Press 'c' to clear the canvas.

6) Technical Stack and Learning Outcomes:

Built with Python and OpenCV, showcasing practical computer vision techniques like color filtering and contour detection.

Serves as a prototype for interactive digital art interfaces and gesture-controlled applications.
