[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# Audio-Splicing
Detecting Audio Splicing Using MATLAB and Machine Learning

This repositiory contains my files for my auido splicing experimenation. The details for this experiment are given below.

## Details:
Audio Splicing is a technique of attaching different pieces of audio together 
to create a new edited audio. Fake audios have become a trend now, and 
with the increasing expertise of the editors it has become impossible to 
differentiate between fake and real audio without the use of proper tools. 

[<img align="right" width="250" height="250" src="https://tsgdoc.socsci.ru.nl/images/2/21/Matlab_Logo.png"/>](https://www.mathworks.com/products/matlab.html)
[<img align="right" width="250" height="250" src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/172px-Python-logo-notext.svg.png"/>](https://en.m.wikipedia.org/wiki/File:Python-logo-notext.svg)



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

## Flow chart
![SNS](https://user-images.githubusercontent.com/107636242/215844825-5df382a1-3308-45d6-8b98-7c13fbe04bdf.png)

## Project Structure
The project is structured as follows:

```fish
Audio-Splicing
├── test/                              # Contains test files
├── Python Expriment files/            # Contains Experimentation files
├── Spectrogram Images/                # Contains Images for Spectrograms
├── report/                            # report file
├── LICENSE                            # license file
├── README.md                          # readme file
```

## Installation
To get started with downloading this repository, follow the steps below:

Clone the repository to your local machine using the following command:

   
    https://github.com/ahmd-mohsin/Audio-Splicing.git

## Changes
For any further recommnded changes and collaborations, feel free to contact. With ❤️ Ahmed.
