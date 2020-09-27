# Music-genre-classitfication
<img src="https://user-images.githubusercontent.com/69448968/94357214-6bf0f980-00b4-11eb-93bf-72c8aa7856c9.jpeg" width="60%">

## About
Our project is a classifier to identify various music genres. We have trained the model to classify genres such as blues, classical, country, disco, hiphop, jazz, metal, pop, reggae and finally rock. 

We have used Librosa, a Python package for music and audio analysis. Librosa is basically used when we work with audio data like in music generation(using LSTM’s), Automatic Speech Recognition.

It provides the building blocks necessary to create the music information retrieval systems. Librosa helps to visualize the audio signals and also do the feature extractions in it using different signal processing techniques.

We have used Convolutional Neural Networks and it is performed by involving high-level features such as Spectrogram Feature and Chroma Feature. Python programming language has been used for several steps of works from dataset collection, segmentation, feature extraction, until classification.

## Dataset

The dataset is collected from the GTZAN dataset which was available in Kaggle (https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification).

genres original - A collection of 10 genres with 100 audio files each, all having a length of 30 seconds (the famous GTZAN dataset, the MNIST of sounds)

images original - A visual representation for each audio file. One way to classify data is through neural networks. Because NNs (like CNN, what we will be using today) usually take in some sort of image representation, the audio files were converted to Mel Spectrograms to make this possible.

2 CSV files - Containing features of the audio files. One file has for each song (30 seconds long) a mean and variance computed over multiple features that can be extracted from an audio file. The other file has the same structure, but the songs were split before into 3 seconds audio files (this way increasing 10 times the amount of data we fuel into our classification models). With data, more is always better.
