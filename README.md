# ANPR(Automatic Number Plate Recognition System)

## Table of Contents
+ [About](#about)
+ [Getting Started](#getting_started)
+ [Dataset](#dataset)
+ [Contributing](../CONTRIBUTING.md)

## About <a name = "about"></a>
Write about 1-2 paragraphs describing the purpose of your project.

## Getting Started <a name = "getting_started"></a>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites
* activate venv in local system
```
.\anprsys\Scripts\activate
```
* install requirements for code to run
```
pip  install -r requirements.txt
```

### Installing
#### Image Collections.ipynb to collect data from webcam
* For labeling image use Image Collection.ipynb
#### For our usage with kaggle dataset 
https://www.kaggle.com/datasets/andrewmvd/car-plate-detection


#### Traning and Detection.ipynb
* run each cell in jupyter notebook or in any other IDE. 

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo.

## Dataset <a name = "dataset"></a>
* run first four command line in ```Training and Detection.ipynb``` to form path for image Directory
* Get dataset from https://www.kaggle.com/datasets/andrewmvd/car-plate-detection
* Divide dataset into two parts test and train
* allocate image and anotation in same file like this 
![alt text](https://github.com/harshkasat/ANPR/blob/master/screenshot/train%20dataset%20screenshot.png)
* do this for test set also
