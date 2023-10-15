# DSP-Project

#Classify human electrocardiogram (ECG) Signals
#MATLAB Project Introduction
This project contains a MATLAB (.mlx) file that demonstrates various MATLAB functionalities. The file provides detailed explanations and code examples.

#Project Contents
MATLAB Project File (.mlx): Detailed code explanations and demonstrations.

[Modified_physionet_data.txt]: required by PhysioNet's copying policy and provides the source attributions for the data as well as a description of the preprocessing steps applied to each ECG recording.

License.txt

[ECGData.mat] : holds the data used in this project

We are given an ECG signal for the classification process.

In general people can be divided in three groups:
persons with cardiac arrhythmia (ARR)
persons with congestive heart failure (CHF), and
persons with normal sinus rhythms (NSR).
The goal of this PStA is to classify human electrocardiogram (ECG) signals using the Short Time Fourier Transformation and the Continuous Wavelet Transform (CWT) and deep convolutional neural networks (CNNs). The resulting CNNs shall be used to classify the given ECG signal to ARR, CHF, and NSR, respectively.

To store the preprocessed data of each category, first create ECG data directories dataDir1 and dataDir2 inside tempdir. We rename the dataDir1 as 'Scalograms' and dataDir2 as 'Spectrograms' for our convenience to execute Continuous Wavelet Transformation and Short-Time Fourier Transformation. Then create three subdirectories in both Scalograms and Spectrograms named after each ECG category
