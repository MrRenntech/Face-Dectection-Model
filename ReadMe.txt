Install OpenCV library in your system using the command pip install opencv-python.
Save the code in a Python file with a .py extension.
Download the haarcascade_frontalface_default.xml file from OpenCV's official GitHub repository.
Save the haarcascade_frontalface_default.xml file in the same directory as the Python file.
Replace the 0 argument in the cv2.VideoCapture() function with the index of the camera you want to use. If you only have one camera, you can leave it as 0.
Run the Python file in your terminal or IDE.
When you run the code, it will open a new window displaying the video feed from your camera with detected faces marked by a green rectangle.