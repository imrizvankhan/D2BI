# Deep Ill Light Image Enhancement (D2BI-Net)

Requirements
Python
Tensorflow >= 1.10.0
numpy, PIL

Descriptions:
This project is a TensorFlow implementation of a Ill Light Image Enhancement. We aim to enhance the illy illuminated images, i.e front-lit, backlit, low-lit, high-lit, dim or weak-lit and a combination of these conditions. We employ Retinex theory and  design an adaptive enhancement constraint parameter to upgrade the low light images for pleasing visual quality. 
The model implemented in this regard is compliled of simple and light weight multilayer distribution loss-net (to divide image) and an encoder-decoder (3x3 up-down sampling) unit for illumination repairing denoted as repair-net.



Dataset:

The dataset consist of more than 1300 images of ill-illumination conditions, arranged as under-exposes to well exposed, named as UXOV-Data set. 

Test and GT images:
We presented evaluation on 18-test images from our data set, whereas the dataset contain many sample images with reference images and in each case a high exposure can act as a reference GT for the low exposure test image.  We have presented the seperate files for test and training data, where every scene has a seperate folder with multiple exposures. 

Dataset-Link:
 The dataset can be downloaded from the google grive link :
 https://drive.google.com/drive/u/1/folders/1uj8MGHWtRMbeuh8VZemmIv-wqUqVNdo6




