## Digital Signal Processing and Deep Learning
--------------------------------------------------------

This repository is a study of **Digital Signal Processing techniques** for **Audio** signals

1. DSP helps creation of **features** for ML
	- We look at creation of features for traditional ML - for example a SVM classifer
	- And, we look at creating features for **Deep learning** techniques such as MLP, CNN, RNN and LSTM
	
2. For _traditional_ ML feature engineering, we look at Time domain, Frequency domain and  time-frequency features

3. **Time Domain features**:
    - A-D-S-R model: Attack-Decay-Sustain-Release model for audio
    - Amplitude envelope (AE)
    - Root-mean-square Energy (RMS-E)
    - Zero-crossing rate (ZCR)

4. **Frequency Domain features**:
    - FFT - Fast Fourier Transform
    - STFT - Short Time Fourier Transform
    - MFCC - Mel Frequency Cepstral Coefficents
	- MFCC: MFCC feature extraction technique basically includes windowing the signal,
applying the DFT, taking the log of the magnitude, and then warping the frequencies
on a Mel scale, followed by applying the inverse DCT.
	
5. For deep learning, we use MFCC converted to images
6. We build a CNN using TensorFlow Keras
7. To-Do: Build RNN, LSTM for DSP

8. For additional technical notes please see: https://github.com/Rajesh-Siraskar/Digital_Signal_Processing_and_Deep_Learning/blob/main/README_DSP-Notes.ipynb

Launch a project
- 20-May-2021: Valve fault diagnotics based on sound files
		- Attempt to train to recognize faulty valves