## Voice clone: Text to Speech Synthesis

This repository is an implementation of Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis (SV2TTS) with a vocoder that works in real-time.
Its a neural network-based system for text-to-speech (TTS) synthesis generate speech audio in the voice of different speakers, including those
unseen during training. 

It consists of three independently trained components: 

(1) recurrent speaker encoder: computes a fixed dimensional vector from a speech signal,

(2) a sequence-to-sequence synthesizer:predicts a mel spectrogram from
a sequence of grapheme or phoneme inputs, conditioned on the speaker embedding vector 

(3)  an autoregressive WaveNet  vocoder:converts the spectrogram into time domain waveforms.

# ![git](https://user-images.githubusercontent.com/91752852/138429931-2d4ba99c-a322-4acb-9785-cfbb27642911.jpg)
### fig 1: Multispeaker speech synthesis model



# Documentation

This project is about real human voice cloning. The main objective of our project to generate deepfake voice similar to original Human voice.Our project can be divided into two parts: input audio from users and clone voice. We have further classified them into seven steps which are given below.

Step 1:Import necessary libraries

Step 2:Usingt HTML and JS for microphone acces

Step 3:Record audio from users

Step 4:Saving audio files

Step 5:Clone the github project and download pretrained models

Step 6:Initialize the voice cloning models

Step 7:Synthesis text to audio for Voice Clone


# Demo
