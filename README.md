# FER
Facial Expression Recognition by Fusion of HOG and LBP with an SVM Classifier. 

## Implementation
See FER_Model.ipynb

## Usage
You need the CK+ dataset and JAFFE dataset. Each dataset folder needs to be split into "Test" and "Training", 
and then both of these folders need to be divided into the emotion labels for the ML model.

Copies of JAFFE online typically just have one folder full of `.tiff` files. In this case run the `ConvertJAFFE.ipynb` 
file and point it to the directory of the JAFFE dataset you have. Should sort everything automatically, including a
70-30 split of training and testing
