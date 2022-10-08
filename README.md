# Tugas-Akhir Machine Learning

# Abstract
In the industrial world, condition monitoring is needed because it can increase the reliability of a machine component. If damage occurs and is not repaired immediately, it will cause more severe damage. These types of damage produce a vibration signal with a certain pattern. The purpose of this research is to detect machine breakdowns automatically using machine learning. The dataset in the form of a pump vibration signal in the time domain is converted into the frequency domain using the Fast Fourier Transform (FFT) technique. The results of the FFT are then extracted features. There are 9 statistical extraction features used which are then selected the best features using the feature importance score technique. The extraction results are entered into a machine learning algorithm. There are 3 machine learning algorithms, namely k-nearest neighbor (kNN), support vector machine (SVM), and gaussian naive bayes (GNB). Through the process of training and validation to produce an unweighted accuracy (UA) value and can predict the type of damage to the pump. The UA values with the kNN, SVM, and GNB algorithms are 95.80%, 95,29%, and 80.69%. Algorithm testing is done with an inference program that aims to evaluate the designed machine learning algorithm.

# Dataset
- This Dataset containing 4 columns including time, x-axis, y-axis, and z-axis of vibration data.  with each normal, unbalance, bearing fault, and misalignment conditions.
- You can access our Dataset in here https://drive.google.com/drive/u/0/folders/1B-R2uadcDpQc3dEvQ0FlbkssE_2cQAml

# Data Acquisition
- There are 4 types of engine failure, namely normal conditions, misalignment, unbalance, and bearings. With each dataset totaling 360 vibration data recorded using the Endaq accelerometer consisting of the x, y, and z axes. Each data is recorded for approximately 5 seconds with a sampling frequency of 20kHz.

# Preprocessing
- Frequency domain using FFT (Fast Fourier Transform) for spectral features
- Normalization (normalize data between 0 and 1)
- Filtering with 0 - 1000 Hz of frequency

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

# Report & Paper
- You can access our Report & Paper in here https://drive.google.com/drive/u/0/folders/11oGAlwagNvrA-ZbN00GwpIADbK1Q7QlE
