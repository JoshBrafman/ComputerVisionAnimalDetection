# ComputerVisionAnimalDetection

This Artificial Intelligence project, which is based on RCNN, creates a system that takes an image as input and outputs the same image with a red box around each animal. It also prints a label classifying the type of animal in each box.

To generate images which can be used to train the convolutional neural network model, run MakePatchesWithCV.py and BackgroundClass.py (this will take a significant amount of time)

To generate the model, run Model.py. To view the confusion matrix to determine how the model is performing on each class, run ModelConfusionMatrix.py

To run object detection and image classification on each of the test images, run Inference.py. You can then view the results in the "PostPatchInferencedImages" folder to see how the model did!

Alternatively, if you would like to see the test image results without training and running the model yourself, go to http://ec2-184-73-118-28.compute-1.amazonaws.com/load to select random test images and generate the resulting output of the model. Unfortunately, due to budgetary constrainsts this website will not be kept running indefinitely. If the above link does not work, you can view the final test image results in this repository in "website/static/postInferences." If you would like to see the test images that the model took as input (the original image without the red rectangles), you can view them by selecting the images with the corresponding number in "website/static/preInferences."
