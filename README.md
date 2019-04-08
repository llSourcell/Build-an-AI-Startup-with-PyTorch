# AI Startup with PyTorch

## Overview

This is the code for [this](https://youtu.be/OE6wssMJoag) video on Youtube by Siraj Raval on building an AI Startup with PyTorch. [This](https://github.com/flatfisher/android-dialogflow-chatbot-sample) is the original Dialogflow + Android integration project. [This](https://colab.research.google.com/drive/1b6oSQl84XdRv_abjhg1vpTpiZyZw2TPF) is the colab that I demonstrated in the video where I train the PyTorch model on movie reviews, then convert it to ONNX, then to Tensorflow's expected protobuf format. 

## Dependencies

- Firebase
- Paypal 
- Tensorflow Lite
- DialogFlow
- PyTorch

## Instructions

Download [Android Studio](https://developer.android.com/studio) then import this project. Since I've placed the dependencies in the build.gradle file, it should auto-download them for you, which is awesome. It needs more features, and better integrated dataflow. I could've put more time into it, but I'm on to the next one. The model was too big to upload to GitHub. Place any .pb model into the app/src/main/assets folder and Tensorflow lite will detect it so it can be used for inference.

## Credits 

So many people. I stand on the shoulders of giants. Respect to all developers. 
