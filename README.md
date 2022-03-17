# Tugas-Akhir

# Dataset
- This Dataset containing 4 columns including time, x-axis, y-axis, and z-axis of vibration data.  with each normal, unbalance, bearing fault, and misalignment conditions.
- You can access our Dataset in here https://drive.google.com/drive/u/3/folders/1zAmBpHNhdATZoZ9QQYuYjQUDIP-iyE6c

# Data Acquisition
-- Update 17/03/2021
- There are 4 types of engine failure, namely normal conditions, misalignment, unbalance, and bearings. With each dataset totaling 360 vibration data recorded using the Endaq accelerometer consisting of the x, y, and z axes. Each data is recorded for approximately 5 seconds with a sampling frequency of 20kHz.

# Preprocessing
-- Update 17/03/2021
- Normalization (normalize data between 1 and -1)
- Frequency domain using FFT (Fast Fourier Transform) for spectral features
-- Further development
- Time domain using EMD (Empirical Mode Decomposition) for temporal features

# Feature Extraction
-- Update 17/03/2021 (in progress)
- Spectral Features : 
- Mean Frequency FM
- Frequency Standard Deviation (FSD)
- Skewness of Frequency (FSK)
- Kurtosis of Frequency (FKR)
- Band Power (BPWR)
- Median Frequency (FMED)
- Spectral Centroid (SC)
- Spectral Flux (SF)
- Spectral Roll Off (SRO)
- Spectral Flatness (SFL)
- Spectral Crest (SCR)
- Spectral Decrease (SDEC)
- Spectral Slope (SSL)
- Spectral Spread (SS)

-- Further development
- Temporal Features :
- Mean (M)
- Standard Deviation (SD)
- Skewness (SK)
- Kurtosis (KR)
- Peak to Peak (PP)
- Root Mean Square (RMS)
- Energy (E)

# Build Classifier
- KNN
- SVM
- Naive Bayes

# Predict a New Vibration Data 
