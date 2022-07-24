# Tugas-Akhir

# Dataset
- This Dataset containing 4 columns including time, x-axis, y-axis, and z-axis of vibration data.  with each normal, unbalance, bearing fault, and misalignment conditions.
- You can access our Dataset in here https://drive.google.com/drive/u/3/folders/1zAmBpHNhdATZoZ9QQYuYjQUDIP-iyE6c

# Data Acquisition
-- Update 17/03/2021
- There are 4 types of engine failure, namely normal conditions, misalignment, unbalance, and bearings. With each dataset totaling 360 vibration data recorded using the Endaq accelerometer consisting of the x, y, and z axes. Each data is recorded for approximately 5 seconds with a sampling frequency of 20kHz.

# Preprocessing
-- Update 17/03/2021
- Normalization (normalize data between 0 and 1)
- Frequency domain using FFT (Fast Fourier Transform) for spectral features

# Feature Extraction
- Mean (M)
- Standard Deviation (SD)
- Skewness (SK)
- Kurtosis (KR)
- Peak to Peak (PP)
- Root Mean Square (RMS)
- Shape Factor (SF)
- Impulse Factor(IF)
- Crest Factor (CF)

# Build Classifier
- KNN
- SVM
- GNB

# Predict a New Vibration Data using Inference Program
- Vibration Data of 2 Pumps Operating Simultaneously
- Vibration Data with Addition Gaussian White Noise
