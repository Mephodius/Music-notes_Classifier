# Music-notes_Classifier
The project aims to predict the right music note (out of 88 + 1 for noise) according to the input audio-file chunk (50 ms). <br />
Real-world music data (isolated notes + noise) was gathered by myself. <br />
Predictor is a composition of two PyTorch MLP's (one for determining if chunk contains music and the other for classifying it).
