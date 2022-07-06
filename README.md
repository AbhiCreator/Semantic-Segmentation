# Semantic-Segmentation
DLFA Spring 2022 Assignment - 1

Build a U-net model for semantically segmentation of regions corresponding to different object
classes implemented on the Semantic Segmentation of Underwater Imagery (SUIM)
dataset. The dataset is uploaded on MS Teams "Semantic Segmentation - Dataset”.

● Use Pytorch only (not Tensorflow)

Steps to follow:

1. Load and visualize the data (show some examples of images and corresponding
masks). [1 mark]

2. Data Processing [2.5 marks]
a. Convert to 572×572 spatial size, if larger then center crop, if smaller then pad
with zeros as the background class.
b. Convert the RGB masks into 8 different grayscale masks (each mask having
“white” values for a particular class and “black” values for the rest of the classes). 

3. Splitting to train and validation data in the ratio 8:2. [0.5 marks]

4. Build a U-Net model identical in architecture to the one in the original paper (https://arxiv.org/abs/1505.04597). [3 marks]

5. Train the model for 50 epochs (calculate training loss, training accuracy, validation loss,
and validation accuracy). [1 mark]

6. Plot two curves (one for loss and the other for accuracy). Put both the training loss and
validation loss in the loss plot, and put both the training accuracy and validation
accuracy in the accuracy plot. [1 mark]

7. Write the interesting points you observe (in the Jupyter notebook). [1 mark]
