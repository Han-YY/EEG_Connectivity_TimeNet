# EEG_Connectivity_TimeNet
Networks developed for video classification are applied to the connectivity based on EEG, and the connectivity features were converted into 'video frames' for fitting the deep networks.

## Dataset
This dataset is for pain assessment, which contains 2 resting states, 2 thermal stimulus conditions and 1 reference condition.

## Data Preprocessing
### Signal Filtering
The signals were extracted from 3 sub-bands of an extensive alpha band: 7-9 Hz, 9-11 Hz, and 11-13 Hz.
### Generating 'video'
#### Frame
3 frequency bands as 3 channels of each 'frame', and the number of rows and columns in the frames are the order of studied EEG electrodes.
#### Clip
Each clip contain 20 frames.

## Basic Models
### 3D CNN
### RNN
#### GRU
#### LSTM
### Transformer
