# Realtime optical flow model
This program can perform optical flow in real-time and is written in Python. First, you need to set up the necessary environment and install packages. Then, prepare the camera settings or video and set the ID or path in the argument of videoCapture. The tracking performance of the optical flow varies depending on the parameters of the Lucas Kanade method. Set the initial point with "oldpoint".

# Environment and Install packages for python3.7 (anaconda3)
 - conda create --name op_f python=3.7
 - pip install -r requirements.txt
 - connect camera and  cap = cv2.VideoCapture("cameraID or video path")  
