# Heart-Arrhythmia-Detection-in-ECG

Author: Majella Imperial </br>
Github: [@singjellarity](https://github.com/singjellarity) </br>
Date: June 2022

---
## Design of Heart Arrhythmia Detection in ECG Beats Utilizing Machine Learning Algorithm with Signal Processing

Based on the [MIT-BIH Arrhythmia Database](https://www.physionet.org/content/mitdb/1.0.0/), this repository contains some of my team's codes used for our final design project required for our bachelor's program in Electronics Engineering.
## Original Authors
- Francisco, Carmela G.
- Imperial, Mary Majella E.
- Labajo, Remilena C.
- Napa, John Vincent S.
  
## Partial Abstract
> In this paper, the proposed method uses a machine learning model that can classify ECG beats generated from the human heart to 5 types: normal beat, supraventricular premature beat, premature ventricular contraction, fusion of ventricular and normal beat, and unclassified beat. In consideration of other studies, the proponents designed a wearable heath care device for heart arrhythmia detection in ECG beats utilizing machine learning algorithm with signal processing. The system in form of wearable health device comes with built-in storage subsystem and cloud-based data visualization. It also features sensing and recording of heart rate, BP, and body temperature as a supplementary feature of the device. Furthermore, the paper is not suggesting any self-diagnosis based on the classified beats. It simply aims to simplify the ECG signal to beats to reduce the time cardiologists need to read the ECG recordings.

---
# File Exploration
This repository contains the following:
- ANN.ipynb
- CNN.ipynb
- RNN_LSTM.ipynb </br>
All three notebooks contain a short study on the performance of an Artificial Neural Network, Convolutional Neural Network, and Long Short-Term Memory machine learning models on the MIT-BIH Arrhythmia Database. </br>
- RNN-TinyML-New.ipynb </br>
Based on the performance of the three machine learning algorithms, the LSTM was chosen to be deployed on our device. This file contains a notebook saving the LSTM model as a TinyML. </br>
- ecg_arrhythmia.h
- ecg_arrhythmia.hdf5
- x_test.h </br>
The above files are some of the files deployed to our device. 




