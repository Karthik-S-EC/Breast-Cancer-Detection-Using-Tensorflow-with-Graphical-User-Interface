# Breast-Cancer-Detection-Using-Tensorflow-with-Graphical-User-Interface

Breast Cancer Detection using Tensorflow with GUI for testing with better user friendly.
## Steps Involved in training
1. Use Google Colab for Training(Because of faster training and High RAM and GPU)
2. Create folder named Breast Cancer Detection in Google Drive
3. Inside Breast Cancer Detection Create 2 folders naming data and weights
4. Inside Data folder create train and validation folders and upload all the images of train and validation into respective folders
5. The Structure will look like this:
#### Google Drive->Breast Cancer Detection->data->train->class0 and class1->Images
#### Google Drive->Breast Cancer Detection->data->validation->class0 ans class1->Images
#### Google Drive->Breast Cancer Detection->weights->(pre-trained weights file if any)
6. upload the Breast-Cancer-Detection.ipynb file into drive or Google Colab 
7. Run the Breast-Cancer-Detection.ipynb file (Architecture is ResNet50 and inital weights are from imageNet)
8. After running the whole file. Inside the weights folder the model file named BestDetection.h5 will be generated

## Packages Needed:
1. Tensorflow == 1.15 (if GPU is available install Tensorflow-gpu)
2. OpenCv
3. Numpy
4. setuptools( >= 41.0.0)
5. PyQt5

## Installation steps:
1. IF GPU is available:
    1. If NVIDIA Graphics card is available download and install CUDA and cuDNN.
       1. CUDA download link:
       2. cuDNN download link:
       Follow currect steps to install CUDA and cuDNN(Make sure that both CUDA and cuDNN are of same version)
       Tensorflow = 'pip3 install tensorflow-gpu==1.15"
       
2. Tensorflow = 'pip3 install tensorflow==1.15'
3. OpenCv = 'pip3 install opencv-python'
4. Numpy = 'pip3 install numpy'
5. setuptools = 'pip3 install --upgrade setuptools'
6. PyQt5 = 'pip3 install PyQt5'

## Screenshots of the Graphical user interface of Breast Cancer Detection
![Image of GUI](https://github.com/Karthik-S-EC/Breast-Cancer-Detection-Using-Tensorflow-with-Graphical-User-Interface/blob/master/Annotation%202020-05-01%20111633.jpg)
![Clicking on Detect without selecting the Image](https://github.com/Karthik-S-EC/Breast-Cancer-Detection-Using-Tensorflow-with-Graphical-User-Interface/blob/master/Annotation%202020-05-01%20111718.jpg)
![Loaded Custom Dataset Trained Model](https://github.com/Karthik-S-EC/Breast-Cancer-Detection-Using-Tensorflow-with-Graphical-User-Interface/blob/master/Annotation%202020-05-01%20111840.jpg)
![Result of one of the Image](https://github.com/Karthik-S-EC/Breast-Cancer-Detection-Using-Tensorflow-with-Graphical-User-Interface/blob/master/Annotation%202020-05-01%20111912.jpg)


    
