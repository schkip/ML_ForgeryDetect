Udacity Machine Learning Nanodegree Capstone Project

"The Art Thief - Is is a Whiteley?"

Forgery Identification using Machine Learning 

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
GITHUB

I truncated the number of images, bottleneck features, checkpoints and weights so that it would fit on Github.
You can add images and run the code to generate bottleneck features, checkpoints and weights.


>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
ENVIRONMENT

The environment is Anaconda running on a local machine.

Steps:

Install anaconda https://www.anaconda.com/distribution/

use the Anaconda command line to create a virtual environment

$conda -V  

$conda update conda

$conda create -n yourenvironment python=3.7 anaconda

this will create an environment called yourenvironment

$source activate yourenvironment


>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
HARDWARE VERSION / REQUIREMENT

Environment was installed on an Intel NUC
32G RAM
Intel I7 3.1GHZ
64-bit
Windows 10

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
INSTALLING LIBRARIES

switch to the Anaconda environment "yourenvironment"

$conda install -n yourenvironment [package]

where [package] includes

keras
matplotlib
cv2
math
numpy
sklearn
glob
scipy

then open the jupyter notebook with the python files by using the Anaconda prompt in yourenvironment 

$jupyter notebook 

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
FILE DESCRIPTIONS

The following are the files and their description

CNN_scratch.ipynb			CNN classifier for forgery detection built from scratch
color_analysis.ipynb		analysis of an image set for peak color histogram
intensity_analysis			analysis of an image set for histogram peak intensity histogram analysis
ORB_feature_extractor		feature extraction and first keypoint pair image feature extraction using ORB algorithm
ROC_AUC.ipynb				calculator of the Receiver Operating Characteristic and Area under the curb
transfer_VGG16.ipynb		CNN classifer for art forgery using transfer learning from pretrained VGG16 on ImageNet

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
DATA DESCRIPTIONS

The data is located in the following folder structure

-data
--eval
--train
---brett
---not_brett
--validation
---brett
---not_brett

where the training data for each class is in the train directory
the validation data is in the validation directory
the eval directory contains a sample of each class and also the alleged forged painting

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
DOCUMENTATION

The final report and the capstone project proposal are contained in the /documentation directory

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
AUTHORS

Steve Winnall 16/08/2019



