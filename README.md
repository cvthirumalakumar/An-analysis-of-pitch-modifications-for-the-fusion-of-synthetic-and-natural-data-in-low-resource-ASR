# An-analysis-of-pitch-modifications-for-the-fusion-of-synthetic-and-natural-data-in-low-resource-AS
This is a course prioject done for Speech Signal Processing course at IIIT-Hyderabad during my MS in 2023.

### Goal of the project
Main idea of this project is to try pitch modification (i.e., making pitch constant in all voiced segnemts of the audio and the constat pitch is the average pitch of the audio) to conver all natural as well as synthetic data monotonous (to make natural and synthetic data closer to over come training data distibution differences when training asr with natural and synthetic data together in low resource setting or domain adaptation). Since prosody is the main difference between the natural and syhthetic which is composed of pitch, duration and energy mainly. In this project we attemped to change pitch to make entire training data resemble same distribution, where pitch modification block acts as front-end block while train and test. 

We compare WER of natural and synthetic audios tested on 
* ASR trained on only Natural data
* ASR trained on Natutal+Synthetic data
* ASR trained on pitch modified version of Natural+Synthetic data