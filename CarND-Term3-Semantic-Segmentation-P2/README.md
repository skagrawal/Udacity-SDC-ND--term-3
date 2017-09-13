# CarND - Semantic Segmentation Project

### Project Overview
In this project, I trained a Fully Convolutional Network (FCN) to label the pixels of a road in images. I started with the VGG16 network and updated it by adding skip layers, 1x1 convolutions and upsampling to build the desired FCN.

During training, I experimented with multiple epochs, batch sizes, learning rates and dropout rates. Final values of hyperparameters are:

- Dropout probability: 0.50
- Epochs: 15
- Batch Size: 4
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
 - Some sample outputs
 
 ![1](./runs/1505240322.712861/um_000000.png?raw=true )
 ![2](./runs/1505240322.712861/umm_000051.png?raw=true )
 ![3](./runs/1505240322.712861/umm_000086.png?raw=true )
![4](./runs/1505240322.712861/uu_000093.png?raw=true )
![5](./runs/1505240322.712861/umm_000032.png?raw=true )
##### References
- [Fully Convolutional Networks for Semantic Segmentation](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf)

- Udacity SDC ND
