# Facial-Expression-Analysis
Facial Expression Recognition (FER) is an intriguing field within computer vision that aims to detect and classify human emotions based on facial expressions. Our project leverages the power of Convolutional Neural Networks (CNNs) to achieve real-time facial expression recognition using the [FER 2013 Dataset](https://www.kaggle.com/datasets/msambare/fer2013).

# Objective
Our primary objective is to develop a robust and accurate system capable of automatically detecting and classifying facial expressions into predefined emotion categories such as anger, disgust, fear, happiness, sadness, surprise, and neutrality.

# Features
Real-time Emotion Detection: Our trained model can analyze live video streams and detect facial expressions in real-time.

Multi-class Classification: The model classifies facial expressions into multiple emotion categories simultaneously.

# Why Facial Expression Recognition?
Facial expression recognition has a wide range of applications, including human-computer interaction, virtual reality, healthcare, and marketing research. By accurately identifying human emotions, our system can enhance user experiences and enable more personalized interactions in various domains.

# Usage
The Live Face Recognition folder contains the requirements and webcam.py file which can be run to detect emotion categories such as anger, disgust, fear, happiness, sadness, surprise, and neutrality in your face.😊

This Code uses OpenCV and DeepFace Libraies so install them in your system if you haven't before running the code.🚀

You can install these dependencies via pip:

`pip install opencv`

`pip install deepface`

After this step running the contents on the Live Face Recognition folder should detect your live facial expressions by opening your camera.⭐

# Model Training 
The FacialEmotionAnalysis.ipynb File contains the code for training the model from the  [FER 2013 Dataset](https://www.kaggle.com/datasets/msambare/fer2013).

Make sure to download the data set from this link before running the model.

This first cell contains this code where you unzip and save the dataset for training so choose the appropriate zip file.

`from google.colab import files
uploaded = files.upload()
for fn in uploaded.keys():
  print('User uploaded file "{name}" with length {length} bytes'.format(name=fn, length=len(uploaded[fn])))`

You will get a choose file button below the cell make sure to choose the unextracted zip file.

The rest of the code will allow you to take a photograph from your camera and read your facial expression.

Thank You for Reading.💙
