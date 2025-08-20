# Emotion-Detector-using-CNN
This project will detect the emotion of the people and categorize into happy, sad, angry, disgusted, fearful, neutral, surprised. It is capable of detecting the emotions in live also as well as in a video.

![emotion_detection](https://github.com/Manmohan27333/Emotion-Detector-using-CNN/edit/main/README.md)

### Packages need to be installed
- pip install numpy
- pip install opencv-python
- pip install keras
- pip3 install --upgrade tensorflow
- pip install pillow

### download FER2013 dataset
- from below link and put in data folder under your project directory
- https://www.kaggle.com/msambare/fer2013

### Train Emotion detector
- with all face expression images in the FER2013 Dataset

It will take several hours depends on your processor. (On i7 processor with 16 GB RAM it took me around 4 hours)
after Training , you will find the trained model structure and weights are stored in your project directory.
emotion_model.json
emotion_model.h5
