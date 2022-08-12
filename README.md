# Song-Recommendation-using-real-time-face-emotions
Recommends songs based on real-time face emotion detection (ongoing project).

# Demo inference:
![DEMO](https://github.com/BhanuNayak/song_recommender/blob/main/imgs/inference.jpg)

(Still under progress)

# Project Description:
A keras model implemented from scratch is trained on the FER-2013 dataset for detecting face emotions. It can detect 6 emotions. The implementation makes use of OpenCV to get a live video feed from the web-cam of the computer and passes it through the pre-trained model (weights in the face_emotions_weights.h5 file) to detect the emotion. It is now to return the songs filtered and stored in csv files or spotify api, according to the detected emotion.

# Model Architecture:
(https://github.com/BhanuNayak/song_recommender/blob/main/imgs/model_architecture.jpg)

# To run the project:
Flask: 
- Run <code>pip install -r requirements.txt</code> to install all dependencies.
- Run <code>python app.py</code>

# Tech used:
- Keras
- Tensorflow
- Flask

# Dataset FER-2013:
The FER-2013 dataset can be downloaded from the kaggle link <a href = "https://www.kaggle.com/msambare/fer2013">here</a>.


