# Auto-Image-Caption-Generator
Image Caption Generator is a Deep Learning based approach,where if a image is fed to the model,it generates a approriate description of the image.

# Data
I used Flickr-8 dataset,since it is of only 1 gb.Whereas,Ms-Coco was about 15 gb
https://illinois.edu/fb/sec/1713398

# Objective
* Can help Visually Impaired People,By telling them the description of surrounding by converting text to speech.
* Images appearing on Websites can be automatically captioned,reducing a lot of manual effort.
* Can be used in real-time description,as well as in video which again can help visually impaired people.
* It can used in real-time in cctv,which can help figure out some kind of crime and set up the alarm.This also reduces alot of manual effort.
* Can help self-driving car
and much more

# Dependencies
* Tensorflow/Keras
* pickle
* String
* re
* Nltk
* Numpy
* os
* OpenCV

# Models
* ResNet50
* LSTM

# Metrics
Bleau-Score

# Performance
The model took about 7 hours to train and acheived a Bleu-Score of:
* BLEU-1: 0.309644
* BLEU-2: 0.111984
* BLEU-3: 0.072317
* BLEU-4: 0.024684

Here,highest acheived was 30% which shows that model is not as acuurate as expected.However,it can be improved and we can acheive a a BleuScore of 70% and above.

# Results

## Code Reference
https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/
