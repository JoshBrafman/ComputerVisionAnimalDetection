# ComputerVisionAnimalDetection

The goal of this project was to create a system that can an image as input and output a rectangle around each animal in the picture, along with a label classifying the type of animal inside the box. To generate images which can be used to train the convolutional neural network model, run MakePatchesWithCV.py and BackgroundClass.py (this will take a significant amount of time)

To generate the model, run Model.py. To view the confusion matrix to determine how the model is performing on each class, run ModelConfusionMatrix.py

To run object detection and image classification on each of the test images, run Inference.py and view the results in the "PostPatchInferencedImages" folder to see how the model did!

Alternatively, if you would like to see our test image results without training and running the model yourself, go to http://ec2-184-73-118-28.compute-1.amazonaws.com/load
