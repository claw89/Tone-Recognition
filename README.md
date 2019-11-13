## Mandarin-Tone-Recognition

Two Jupyter notebooks detailing an attempt to classify the tones of a Mandarin Chinese utterance based on the audio spectrogram. 
Part 1 uses a manual extraction of fetures from extracted tone lines; Part 2 applies the full spectrogram as the input of a 
convolutional neural network; Part 3 uses a recurrent neural network to encode the variable length input spectrogram.

The model obtained in Part 3 is used for tone clasificaiton in the related [demo Android application](https://github.com/claw89/Tone-Recognition-Application).
