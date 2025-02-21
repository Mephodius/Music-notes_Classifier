# Music-notes_Classifier
The project aims to predict the right music note (out of 88 + 1 for noise) according to the input audio-file chunk (50 ms).
Real-world music data (isolated notes + noise) was gathered by myself. 
Predictor is a composition of two PyTorch MLP's (one for determining if chunk contains music and other for classifying it).
