# traffic_sign_detection
 # Software reqirements:
 # NUMPY
 # KERAS
 # OPENCV
 # MATPLOTLIB
 
 # STRUCTURE 
 folder:
 # mydata:
 folder to store images for training ,all the iamges are stored are of size 32x32 size.Images are stored in sub-folders having class number as a folder name
 data set contains has 43 diffrent classes ,means 43 diffrent sign boards are feeded to model for training.
 dataset contains more than 60000 images
 # train.ipynb: training the model 
 # test.ipynb: running the module to get result from live video feed.
# imgoutput.ipynb :  running the module to get result from iamge.
# model_trained.p:model file genereted by sucessful training
 
# steps for Execution 
 Executing with live video:
 1)Run the file train.ipynb.
 2)Run the file Test.ipynb.

Executing with image as input:
 1)Run the file train.ipynb.
 2)store the file in project directory and change the name of input file in imgoutput.ipynb.
 3)Run the file imgoutput.ipynb.
 4)output image by name output.jpeg will stored in project folder 
