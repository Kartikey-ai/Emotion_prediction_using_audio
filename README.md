# Emotion_prediction_using_audio

Objective was to develop an audio classification algorithm 
that could predict the emotion of a user using his audio and speech data.

## Preprocessing

For prepprocessing the entire audio data you can refer to the preprocessing directory above.
Audio data can not be used directly in our machine learning or deep learning models.
So first we need to preprocess the data so that it could be useful. 
Entie data could either be converted to a matrix, bunch of matrix, or there are many other ways of handling them.
Only then algorithms like CNN or LSTM could be used on it.

![Alt text](/preprocessing/images/audio.JPG?raw=true "Optional Title")

## Models testing

We tried and tested CNN, LSTM and other deep learning models but after multiple attempts it was shown that CNN gave better results
as compared to other models like LSTM or even CNN+LSTM. 
Testing and training of different models is shown in the ipynb files present in the directory models_and_results.


More work can been done in the prerocessing of the audio data which I believe could bring better results. 
