# Emotion-Detection
  
# Components and Imports

OpenCV (cv2): Used for image processing and accessing the webcam.

NumPy (np): Used for numerical operations, especially for handling arrays.

TensorFlow and Keras (tensorflow, keras): Used to load and run a pre-trained emotion detection model.

CVZone (cvzone): A high-level module for computer vision tasks. Specifically, FaceDetector from cvzone.

FaceDetectionModule is used for face detection.

 # Model Loading: Loads a pre-trained emotion detection model.

Face Detection: Uses FaceDetector to detect faces in real-time.

Frame Preprocessing: Crops and resizes the face region to match the model's input size.

Emotion Prediction: Feeds the preprocessed face into the model to predict the emotion.

Drawing and Displaying: Draws bounding boxes and labels on the frame and displays the result.

Exit Condition: Ends the loop and closes the program when 'q' is pressed.