<h1 align="center">Face Mask Detection</h1>

<div align= "center"><img src="https://www.researchdive.com/blogImages/NfBEa3zk4o.jpeg" width="400" height="300"/>
  <h4>Face Mask Detection System built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.</h4>
</div>


## Introduction
Due to the seen pandemic Covid-19 in the past years we got to know how wearing masks beccame important hence this system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak . This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.


## :warning: TechStack

- [OpenCV](https://opencv.org/)
- [Keras](https://keras.io/)
- [TensorFlow](https://www.tensorflow.org/)
- [Python](https://www.python.org/)


## :file_folder: Dataset
The dataset used can be downloaded here - [Click to Download](https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset/download?datasetVersionNumber=1)

This dataset consists of ~12k images belonging to three classes:
*	Train
*	Test
*	Validation

## :key: Prerequisites

All the dependencies and required libraries are included in the file <code>requirements.txt</code> [See here](https://github.com/Sudhanshu21xx/Face-Mask-Detection/blob/main/requirements.txt)

## 🚀&nbsp; Installation
1. Clone the repo
```
$ git clone https://github.com/Sudhanshu21xx/Face-Mask-Detection.git
```

2. Open the repo in notebook

3. Now, run the following command in your notebook to install the libraries required
```
$ pip3 install -r requirements.txt
```

## :bulb: Working

1. Download the dataset.

2. Change the directory main_dir in the Facemask_model.ipynb and run it: 
```
import os
main_dir ='New Masks Dataset'
train_dir = os.path.join(main_dir,'Train')
test_dir = os.path.join(main_dir,'Test')
valid_dir = os.path.join(main_dir,'Validation')

train_mask_dir = os.path.join(train_dir,'Mask')
train_nomask_dir = os.path.join(train_dir,'Non Mask')
```

3. Run the Facemaskdetection(open_cv).ipynb (you can also change the videocapture to livecapture)
```
cap = cv2.VideoCapture('video.mp4')
#cap = cv2.VideoCapture(0)
```

## :key: Results
<div align= "center"><img src="https://github.com/Sudhanshu21xx/Face-Mask-Detection/assets/113416452/94004ca7-917e-462f-83ea-30dddae97c17"/>
<div align= "center"><img src="https://github.com/Sudhanshu21xx/Face-Mask-Detection/assets/113416452/a33c0a2f-6f68-4738-aed5-437be10d8d25"/>
  


