# ComputerVisionAnimalDetection

This project creates a system that takes an image as input and outputs the same image with a red rectangle around each animal, along with a label classifying the type of animal found inside the rectangle. 

To generate images which can be used to train the convolutional neural network model, run MakePatchesWithCV.py and BackgroundClass.py (this will take a significant amount of time)

To generate the model, run Model.py. To view the confusion matrix to determine how the model is performing on each class, run ModelConfusionMatrix.py

To run object detection and image classification on each of the test images, run Inference.py. You can then view the results in the "PostPatchInferencedImages" folder to see how the model did!

Alternatively, if you would like to see the test image results without training and running the model yourself, go to http://ec2-184-73-118-28.compute-1.amazonaws.com/load to select random test images and generate the resulting output of the model. Unfortunately, due to budgetary constrainsts this website will not be kept running indefinitely. If the above link does not work, you can view the final test image results in this repository by   
