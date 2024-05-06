# Speech emotion recognition project

Link to google-colab in which the project was done, because of access to GPU:
https://colab.research.google.com/github/kamilMlynarczykk/projekt-Speech-emotion-recognition/blob/main/Speech_Emotion_Recognition_80percent.ipynb

## 1. Goals of project

- Based on human speech predicting those 6 emotions: ANGER, HAPPIENESS, SADNESS, DISGUST, FEAR or NEUTRAL

## 2. Used Datasets

- Crowd-sourced Emotional Mutimodal Actors Dataset (Crema-D)
- Ryerson Audio-Visual Database of Emotional Speech and Song (Ravdess)
- Surrey Audio-Visual Expressed Emotion (Savee)
- Toronto emotional speech set (Tess)

## 3. Data augmentation

Data has been augmented by applying noise, shifting-pitch and stretching, so instead of one audio file, there were 4 in return:
original, noised, with shifted pitches and stretched
It gave approximately 40 000 samples instead of 10 000

## 4. Feature extraction

- MFCC - Mel-frequency cepstrum coefficients: 42
- Chroma - Chromagram from a waveform or power spectrogram: 24
- ZCR - zero-crossing rate of an audio time series: 1 (avg value)
- RMS = root-mean-square (RMS) value for each frame: 1 (avg value)

## 5. Preparing Data

- Data (features and labels) splited into train and test in proportions: 75/25
- Normalized

## 6. Creating Model

- CNN

## 7. Plotting results

- Train and test: loss and accuracy plots
- Confusion Matrix on testing data

## 8. Results

- 80% accuracy of predicting six basic emotions tested on this dataset

  
