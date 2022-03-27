# Attribute-recognition-and-reidentification-Market1501-dataset


The goal of this work is to develop a system that is able to, make predictions about some attributes of the people in the dataset and reidentify people in the test set using the queries images in the query folder. The systems is trained and evaluated on the Market-1501 dataset.
For further details, please check the report.

## Dataset
Here some sample images from the Market 1501 dataset. 
![dataset](https://github.com/razacode/Attribute-recognition-and-reidentification-Market1501-dataset/blob/main/img/dataset-1.png)
Each subject is captured from multiple cameras in different moments. Are present also some junk images or distractors as you can observe in the last row

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

![alt text](https://github.com/razacode/Attribute-recognition-and-reidentification-Market1501-dataset/blob/main/img/dataset-2.png)

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
