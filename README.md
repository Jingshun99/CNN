# CNN

This project introduces possible solutions that could be implemented to increase the accuracy of Convolutional Neural Network(CNN) with a small sample size.

This folder contains one runnable file (main.ipynb), two PTH files (cifar_net(e_best) & cifar_net(r_best)) and three subfolder (images,output,weights).

## Environment:
- Windows 10 64-bit
- Python 3.9.7
- Visual Studio code

To start, run main.ipynb using Jupyter notebook or Google Colab.

***Table of Content*** decsribes what each cell is doing.

**_cifar_net(e_best).pth_** and **_cifar_net(r_best).pth_** are two files containing the model weights that yield the highest accuracy of the 2-in-1 model.

**_cifar_net(e_best)_** refers to EfficientNet-B7 while **_cifar_net(r_best)_** refers to ResNet-101.

To load, replace original **_<PATH_E>_** and **_<PATH_R>_** in cell 24 with the path of these files.

To make prediction on own image, add your image into the ***image*** subfolder, and replace the **_<img_pth>_** in cell 27 with your image path.

All the trained model will be saved in the ***weights*** subfolder and the output figures will be saved in the ***output*** subfolder.
