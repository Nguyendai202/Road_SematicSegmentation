# Road_SematicSegmentation
detection road using FCN 

### Introduction
In this project, you'll label the pixels of a road in images using a Fully Convolutional Network (FCN).

<p align="center">
 <img src="data_road/um_000001.png" alt="Overview" width="75%" height="75%">
 <br>Qualitative results.
</p>



### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [PIL](https://www.pypi.org/)
 - [Opencv](https://www.opencv.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

### Run

Run the following command to run the project:
```
python main.py
```
