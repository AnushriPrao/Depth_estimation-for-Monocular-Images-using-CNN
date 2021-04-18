# Depth Estimation of Monocular Images using Convolutional Neural Networks

To predict the depth images of the single RGB image using Convolutional Neural Networks.

This project is about deep learning concept of retrieving the depth of an image to measure the distance between the objects and the view point. Files naming Toolbox images-checkpoint.ipynb helps in getting toolbox images of Nyuv2 depth (https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html).

This work is inspired by the concept explained in https://arxiv.org/abs/1812.11941 (High Quality Monocular Depth Estimation via Transfer Learning). 

# Dataset link:
Train data(nyu_train.zip) : https://drive.google.com/drive/folders/1TzwfNA5JRFTPO-kHMU___kILmOEodoBo

Test data (nyu_test.zip) : https://s3-eu-west-1.amazonaws.com/densedepth/nyu_test.zip

# For training:
	Please run the colab notebook(Final code.ipynb) by downloading the data to the local system or in Google drive(easier approach as training needs GPU power)
	
	Instead of diving the entire code into multiple pipelines, a compact .ipynb file is written for the ease of use. 

# For testing:
	evalute.py is expected to be in the same directory as the training file(Final code.ipynb)
	
No explicit plottings are necessary, all the plots are included in the code.

Files DenseDepth_bs8.ipynb, DenseDepth_bs6.ipynb and DenseDepth_bs4.ipynb has separate plots for batch size variation and training data variation. 

# Environments that needs to be installed before running the code
- Google Colab: https://colab.research.google.com/notebooks/intro.ipynb

- Python 3.8 
- Tensorflow 2.2
- RAM of minimum 4 to 8GB

