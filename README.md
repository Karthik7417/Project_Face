# Real-time face detection and emotion/gender classification using fer2013/IMDB datasets &  Head-pose detection to measure roll, pitch & yaw using a keras CNN model and openCV3

* IMDB gender classification test accuracy: 96%.
* fer2013 emotion classification test accuracy: 66%.


## Instructions for Emotion Recognition + Gender Recognition

### Run real-time emotion demo:
> python3 video_emotion_color_demo.py


### To train previous/new models for emotion classification:


* Download the fer2013.tar.gz file from [here](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)

* Move the downloaded file to the datasets directory inside this repository.

* Untar the file:
> tar -xzf fer2013.tar

* Run the train_emotion_classification.py file
> python3 train_emotion_classifier.py

### To train previous/new models for gender classification:

* Download the imdb_crop.tar file from [here](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/) (It's the 7GB button with the title Download faces only).

* Move the downloaded file to the datasets directory inside this repository.

* Untar the file:
> tar -xfv imdb_crop.tar

* Run the train_gender_classification.py file
> python3 train_gender_classifier.py

## Instructions for Head Orientation Detection

### Research Paper
Patacchiola, M., & Cangelosi, A. (2017). *Head pose estimation in the wild using Convolutional Neural Networks and adaptive gradient methods*. Pattern Recognition, http://dx.doi.org/10.1016/j.patcog.2017.06.009.

### Run real-time head-pose detection demo:
> python3 head_pose_estimation_webcam.py
