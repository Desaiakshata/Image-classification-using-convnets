# Image-classification-using-convnets
---
Dog vs Cat - Convolutional neural networks (Exercise taken from a book)
Folow along the code in the notebook to implement convolutional neural networks to classify dog vs cat images
Create 3 data directories: train, validation, test as follows
```
train
    |
    |--Cats
    |--Dogs
```
```
validation
         |
         |--Cats
         |--Dogs     
```
```
test
   |
   |--Cats
   |--Dogs
```   
I have made use of 2000 training images, 1000 validation images and 1000 test images having equal number of cat and dog images

### The training accuracies are improved in three steps:

#### 1. Increasing the size of the dataset using image augmentation techniques
#### 2. Adding dropout layer as part of model regularization
#### 3. Using pretrained model VGG16 and training just the top densely connected network (By freezing the conv base
