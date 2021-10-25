# Voice clone: Text to Speech Synthesis

## Overview of Speech Synthesis

Speech synthesis is the artificial production of human speech.The quality of a speech synthesizer is judged by its similarity to the human voice, and by its ability to be understood.

A text-to-speech system is composed of two parts: a **front-end** and a **back-end**. 

The front-end  first  converts raw text containing symbols like numbers and abbreviations into the equivalent of written-out words which are called text normalization, pre-processing, or tokenization. The front-end then assigns phonetic transcriptions to each word, and divides and marks the text into prosodic units, like phrases, clauses, and sentences called text-to-phoneme or grapheme-to-phoneme conversion. Phonetic transcriptions and prosody information together make up the symbolic linguistic representation that is output by the front-end. 

Lastly, the back-end—often known to as the synthesizer—then converts the symbolic linguistic representation into sound.
 
 ## Real Voice Clone project Architecture

This project is an implementation of   [Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis(SV2TTS)](https://arxiv.org/abs/1806.04558) with a vocoder that works in real-time. Its a neural network-based system for text-to-speech (TTS) synthesis generate speech audio in the voice of different speakers, including those unseen during training.SV2TTS has a three-stage deep learning framework that allows to create a numerical representation of a voice from a few seconds of audio, and to use it to condition a text-to-speech model trained to generalize to new voices.

It consists of three independently trained components:

(1) **recurrent speaker encoder**: computes a fixed dimensional vector from a speech signal,

(2) **a sequence-to-sequence synthesizer**:predicts a mel spectrogram from a sequence of grapheme or phoneme inputs, conditioned on the speaker embedding vector

(3) **an autoregressive WaveNet vocode**r:converts the spectrogram into time domain waveforms.
# ![git](https://user-images.githubusercontent.com/91752852/138429931-2d4ba99c-a322-4acb-9785-cfbb27642911.jpg)

### fig 1: Multispeaker speech synthesis model 



## Documentation

This project is about real human voice cloning. The main objective of our project is to generate deepfake voice similar to original Human voice.Our project can be divided into two parts: **input audio from user** and **clone the voice**. We have further classified them into seven steps which are given below. You can visit this link 
[voice clone project](https://github.com/Hem7513/Voice-Clone-Text-to-speech-Synthesis/blob/master/Text_to_speech_synthesis.ipynb) for more detail.

Step 1:Import necessary libraries

Step 2:Usingt HTML and JS for microphone acces

Step 3:Record audio from users

Step 4:Saving audio files

Step 5:Clone the github project and download pretrained models

Step 6:Initialize the voice cloning models

Step 7:Synthesis text to audio for Voice Clone


## Demo
[Voice clone demo Video](https://github.com/Hem7513/Voice-Clone-Text-to-speech-Synthesis/blob/master/voice%20clone%20demo.mp4)


## Applications of Speech Synthesis

It is useful for those people who suffer from dyslexia and other reading  difficulties.
 
Speech synthesis techniques are also used in entertainment productions such as games and animations to generate narration and lines of dialogue according to user specifications.

Used for developement of applications like electronic mail readers, conventional TTS system, educational application (as an interactive system for normal misspellings
detection), as an interactive voice response system in telephone enquiry system and Human Computer Interaction (HCI) for remote monitoring and controlling to give information about situation.

## Reference


[08 Recording Audio from a Microphone - Introduction to Google Colaboratory (Colab) for Research](https://www.youtube.com/watch?v=4DGkgUffWxs)

[Recording Audio in the Browser Using the MediaStream Recorder API](https:/blog.addpipe.com/recording-audio-in-the-browser-using-pure-html5-and-minimal-javascript/)

[Convert blob to base64](https://stackoverflow.com/questions/18650168/convert-blob-to-base64/18650249#18650249)

[Easy audio capture with the MediaRecorder API](https://hacks.mozilla.org/2014/06/easy-audio-capture-with-the-mediarecorder-api/)

[Record to an Audio File using HTML5 and JS](https://air.ghost.io/recording-to-an-audio-file-using-html5-and-js/)

[Clone Any Voice Using Machine Learning | KNOWLEDGE DOCTOR | Mishu Dhar](https://www.youtube.com/watch?v=2NdhKkxjf2M)

[CorentinJ/Real-Time-Voice-Cloning](https://github.com/CorentinJ/Real-Time-Voice-Cloning)

[Now Clone anyone's voice - simple steps - Deepfake Voice Cloning Tutorial](https://www.youtube.com/watch?v=I-tpsOSy5l4)

## Hello , It's me Hem ✌️ 👋 ✋

### Thanks for your valuable time 🙏🙏🙏





