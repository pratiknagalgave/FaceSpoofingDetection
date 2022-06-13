# FaceSpoofingDetection
I perform the end to end pipeline for deploying the face antispoofing system by using opencv. First, I train the liveness detection model by using our own dataset and then deploy the trained model using opencv and python.

Workflow of the system :
At first, the input image is captured by using a webcam and then we apply face detection algorithm to the input image. Then the detected face is forwarded to the liveness net which check whether the image comes from a real person or not.
