# CarND - Semantic Segmentation Project

### Project Overview
In this project, I trained a Fully Convolutional Network (FCN) to label the pixels of a road in images. I started with the VGG16 network and updated it by adding skip layers, 1x1 convolutions and upsampling to build the desired FCN.

During training, I experimented with multiple epochs, batch sizes, learning rates and dropout rates. Final values of hyperparameters are:

- Dropout probability: 0.25
- Epochs: 20
- Batch Size: 16
- Learning rate: 0.0001

### Setup
##### Frameworks and Packages
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

### Start
##### Implement
`main.py` contains model design and training part.

##### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.

##### Output
 - Newest inference images are in `runs` folder

##### References
- [Fully Convolutional Networks for Semantic Segmentation](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf)

- Udacity SDC ND
