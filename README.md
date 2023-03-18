# ANPR(Automatic Number Plate Recognition System)

## Table of Contents
+ [About](#about)
+ [Getting Started](#getting_started)
+ [Dataset](#dataset)
+ [Contributing](../CONTRIBUTING.md)

## About <a name = "about"></a>
ANPR (Automatic Number Plate Recognition) is a technology that uses cameras and software to read and interpret vehicle registration plates. It is widely used in law enforcement, traffic management, toll collection, and parking enforcement. ANPR can quickly identify and track vehicles of interest, making it a valuable tool for improving public safety and security.

## Getting Started <a name = "getting_started"></a>

### Prerequisites
* make venv 
```
python -m venv anprsys
```
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

## Dataset <a name = "dataset"></a>
* run first four command line in ```Training and Detection.ipynb``` to form path for image Directory
* Get dataset from https://www.kaggle.com/datasets/andrewmvd/car-plate-detection
* Divide dataset into two parts test and train
* allocate image and anotation in same file like this 
![alt text](https://github.com/harshkasat/ANPR/blob/master/screenshot/train%20dataset%20screenshot.png)
* do this for test set also


#### Traning and Detection.ipynb
* run each cell in jupyter notebook or in any other IDE. 

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo.

