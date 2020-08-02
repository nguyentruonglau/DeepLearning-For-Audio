
Use Residual Networks and Mel Frequency Cepstral Coefficients in Voice Recognition Problem
==========================================================================================

# Introducetion
  
  
This is the repository used to voice recognition problem

Here, we perform using MFCC to extract audio features and convert to image format to facilitate training on FamousVoiceDataset. Then, we rebuilt the ResNet50 model and saved the model as json, finally, in train process we saved the best model according to the error on validation data.

In addition, you can change the number of classes and the HxWxC size in the file Resnet-50.ipynb  

# Member

|STT|Name|Major|
| :---: | :---: | :---: |
|1|Nguyen Truong Lau |Computer Science|
  

# Data Set
  
FamousVoiceDataset

[2020] Nguyen Truong Lau  

# Description
  
FamousVoiceDataset is the data set that I collect and perform standardized, the quality is what I guarantee. You can see my dataset on my github.  

# USE
  

## Library
  
  
tensorflow, keras - machinelearning  
json - used to save ResNet50 model architecture.  
glob - get the path to the file  
cv2 - read/write image  
IPython - to play audio  
librosa - read/show/feature extraction audio
## Process Data
  
  
1) Download FamousVoiceDataset from my github  
2) Run ProcessData.ipynb  
3) Follow the instructions in file
## Training
  
  
1) Run Train.ipynb  
2) Result in MODEL folder
## Prediction
  
  
1) Run Prediction.ipynb  
2) End