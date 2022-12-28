# facial-mask-detection

Welcome to my project. This application detects the facial co-ordinates around the nose and mouth area of a person and compares if the person is wearing mask or not. 
This application is built using Python, Keras and Tensorflow for object detection and training the model. A square box is created around the faces detected. The box changes to green for the person wearing mask and red if the person is not.
Alarm is also in built in the appliation if a person is not wearing the mask. 
The model is trained using the dataset which includes 6567 images of person wearing the mask and 4000 images for the person not wearing mask in every angle.

**Pre-requisites**
1. pip install tensorflow
2. pip install openCV
