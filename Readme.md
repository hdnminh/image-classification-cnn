
**Leaf Disease Classification and Concrete Crack Classification**


## About project
This are image classification problems. I will implement VGG-16 and LeNet - 2 simple convolutional neural networks to solve 2 prolems: 
1. Classify cracks in images. (binary classification)
2. Classify 1 of 5 types of leaf's disease (multiclass classification)

This project using 2 frameworks: pytorch and tensorflow

1. With Leaf Disease datasets:
- **Input:** a 32x32x3 image
- **Output:**: this leaf belongs to 1 of 5 classes: CBB, CBSD, CGM, CMD, or healthy.

2. With Crack datasets:
- **Input:** a 227x227x3 image
- **Output:** whether there is a crack in image or not.

## Model
### 1. Lenet
Lenet was introduced in 1998 by Yann LeCun
LeNet-5 CNN architecture is made up of 7 layers. The layer composition consists of 3 convolutional layers, 2 subsampling layers and 2 fully connected layers:


<p align="center">
<img alt="image" src="https://raw.githubusercontent.com/blurred-machine/Data-Science/master/Deep%20Learning%20SOTA/img/lenet-5.png">
</p>

![](image\letnet-architecture-detail.png)

## Reference
1. https://d2l.ai/chapter_convolutional-neural-networks/lenet.html
2. https://towardsdatascience.com/understanding-and-implementing-lenet-5-cnn-architecture-deep-learning-a2d531ebc342
3. https://www.kaggle.com/code/blurredmachine/lenet-architecture-a-complete-guide
4. https://builtin.com/machine-learning/fully-connected-layer
5. https://www.analyticsvidhya.com/blog/2020/08/image-augmentation-on-the-fly-using-keras-imagedatagenerator/#:~:text=However%2C%20the%20main%20benefit%20of,still%20in%20the%20training%20stage.
6. https://tiensu.github.io/blog/33_dataaugmentation_modelcheckpoint_cnn/ (ModelCheckpoint)
7. https://majianglin2003.medium.com/train-neural-network-with-pytorch-5231c616d420