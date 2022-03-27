# Attribute-recognition-and-reidentification-Market1501-dataset


The goal of this work is to develop a system that is able to, make predictions about some attributes of the people in the dataset and reidentify people in the test set using the queries images in the query folder. The systems is trained and evaluated on the Market-1501 dataset.
For further details, please check the report.

## Dataset
Here some sample images from the Market 1501 dataset. 
![dataset](https://user-images.githubusercontent.com/51090995/151345687-c329e100-0767-4968-b8c0-d90308da3c6c.png)
Each subject is captured from multiple cameras in different moments. Are present also some junk images or distractors as you can observe in the last row
## Dataset

The dataset used for this project is a version
of the Market-1501 person re-identification dataset.

![alt text](https://github.com/ZizZu94/market-1501-classification-reid/blob/main/img/dataset.png?raw=true)

Each image in the dataset corresponds to a tight crop of a pedestrian
and the same person appears multiple times in the dataset.
Moreover, while the differences between some persons are
marked and easy to spot, some other cases are difficult to
distinguish.

## Dependencies

Python

```
$ sudo apt-get install python3 python3-pip
```

PyTorch

```
$ pip install pytorch
# $ conda install pytorch
```

Tensorflow

```
$ pip install tensorflow
# $ conda install -c conda-forge tensorflow
```

NumPy

```
$ pip install numpy
# $ conda install numpy
```

Pandas

```
$ pip install pandas
# $ conda install pandas
```

Matplotlib

```
$ pip install matplotlib
# $ conda install matplotlib
```

## Classification task

As the first task, we built a
multi-class classification model. We split the images in the
train directory into a train and a validation dataset and used
them to train a model that given the image of a pedestrian
predicts the following attributes:

![alt text](https://github.com/ZizZu94/market-1501-classification-reid/blob/main/img/dataset-2.png?raw=true)

## ReIdentification task

In the second task of our project, you built
a person re-identification model to retrieve from the test directory
all the images depicting the same person identity appearing
in a given query image. More formally, for each image
in the queries directory, we produced an ordered list of images
from the test directory that we believe correspond to
the same person identity depicted in the query image.
## To run the code

In order to run the code please follow the next steps:
- Load the dataset.zip file into your Google drive account 
- Download the folder in your google drive account
- In the dataset section change the dataset.zip path (to unzip the dataset) according to your google drive folder structure
- Run the .ipynb files on Colab
