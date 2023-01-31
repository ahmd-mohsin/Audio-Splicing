# Audio-Splicing
Detecting Audio Splicing Using MATLAB and Machine Learning

Details:
Audio Splicing is a technique of attaching different pieces of audio together 
to create a new edited audio. Fake audios have become a trend now, and 
with the increasing expertise of the editors it has become impossible to 
differentiate between fake and real audio without the use of proper tools. 
Also, in the field of Forensics Science, audio forensics is done to validate if a 
piece of audio is admissible in courts or other official venue. To validate 
audios different techniques has been used, one of them is using Fourier 
Transform to detect any splicing. In this project, for detecting splicing in each 
audio python libraries have been used to analyse the audio, the Machine 
Learning model have been run to classify different sections of the audio 
based on their frequencies. Then Fast Fourier Transform was taken, and 
spectrogram of the audio signal was made to further analyse the audio. And 
finally, audio toolbox of MATLAB was used to detect splicing in the audio, the 
number of splices combined, and their duration was recorded. The Machine 
learning library used with pre trained model was opensoundscape (pytorch 
models). The pretrained model was RESNET 18.
![SNS](https://user-images.githubusercontent.com/107636242/215844825-5df382a1-3308-45d6-8b98-7c13fbe04bdf.png)
