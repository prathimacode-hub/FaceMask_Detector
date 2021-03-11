# FaceMask_Detector
Real time face-mask detection using OpenCV
This project uses an OpenCV to differentiate between images of people with and without masks. The stored weights are used to classify as person wearing mask or no mask, in real time, using OpenCV. With the webcam capturing the video, the frames are preprocessed and fed to the model to accomplish this task. The model works efficiently with no apparent lag time between wearing/removing mask and display of prediction.

The model is capable of predicting multiple faces with or without masks at the same time.
I have used haarcascade algorithm and the images data of people wearing and not wearing mask as well for the model to train by itself.
