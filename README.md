# Auto-Image-Orientation-Correction

This model can automatically correct the orientation of the input image if it's rotated to 0, 90,180, 270 and 360 degrees. It is trained on a dataset of different angles of images such as 0 degree, 90 degree, 180 degree, 270 degree and 360 degree. Our model can classify the rotation angle of input image and then correct it's orrientation by rotating it to 0 degree angle.  

## Applications

It can be useful in automatically correcting the orientation of images in large quantities. For example, you have 100000 images which are rotated in random angles. This model can correct the rotation angle of all th images at once. 

## Code Requirements 

The example code is in Python (version 3.6 or higher will work)

## Dependencies

1) import cv2
2) import imutils
3) import keras
4) import scipy
5) import tensorflow
6) import numpy
7) import Pickle

### Dataset

The dataset I used to train the model is consists of total 14000-15000 images which are divided into five parts. First part is saved as 0 degree angle images, second part is rotated to and saved as 90 degree angle images, third is rotated to and saved as 180 degree angle images and the fouth part rotated to and saved as 270 degree angles. 

 0 degree angle images
 
![Dataset](https://github.com/msalmankhaliq/Auto-Image-Orientation-Correction/blob/main/dataset/1f4ec52f-7d55-4c06-995a-cd0e4894b4d7.png)

90 degree angle images

![Dataset2](https://github.com/msalmankhaliq/Auto-Image-Orientation-Correction/blob/main/dataset/Sample-images-from-the-VGGFace2-dataset.jpg)

180 degree angle images

![Dataset3](https://github.com/msalmankhaliq/Auto-Image-Orientation-Correction/blob/main/dataset/images.jpg)

270 degree angle images

![Dataset4](https://github.com/msalmankhaliq/Auto-Image-Orientation-Correction/blob/main/dataset/Samples-from-the-VGG-Face-dataset-Each-row-contains-the-face-images-of-the-same-person.jpg)


