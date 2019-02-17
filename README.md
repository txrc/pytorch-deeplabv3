# PyTorch-DeepLabV3

<<<<<<< HEAD
This is an implementation of Semantic Segmentation on the [Berkeley Deep Drive Dataset](http://bdd-data.berkeley.edu/index.html). ResNet-101 was used as the feature extractor and the Atrous Spatial Pyramid Pooling module mentioned in the DeepLabV3 paper are in this repo. [Rethinking Atrous Convolution for Semantic Image Segmentation](https://arxiv.org/abs/1706.05587).

The pretrained ResNet-101 model weights were taken from the MIT ImageNet. Download it [here]((http://sceneparsing.csail.mit.edu/model/pretrained_resnet/resnet101-imagenet.pth)) and use torch.load to load the weights into the model.
=======
This is an implementation of Semantic Segmentation on the [Berkeley Deep Drive Dataset](http://bdd-data.berkeley.edu/index.html) which segments drivable lanes into the current driving lane as well as the available alternate lanes. ResNet-101 was used as the feature extractor and the Atrous Spatial Pyramid Pooling module mentioned in the DeepLabV3 paper are used in this repo. [Rethinking Atrous Convolution for Semantic Image Segmentation](https://arxiv.org/abs/1706.05587).

The pretrained ResNet-101 model weights were taken from the MIT ImageNet. Download it [here](http://sceneparsing.csail.mit.edu/model/pretrained_resnet/resnet101-imagenet.pth) and use torch.load to load the weights into the model.
>>>>>>> 45080faebba51eb18f87994a5cf1050a58b78c12

## Acknowledgement
Part of the code is borrowed from [SpeedingHZL's PyTorch-Segmentation-Toolbox](https://github.com/speedinghzl/pytorch-segmentation-toolbox). 

I have no intention of copying the models or using the code for any commercial purposes. 

<<<<<<< HEAD
I am experimenting the model on my capstone project which involves Scene Understanding of Self Driving Cars.
=======
I am experimenting the model on my capstone project which involves Scene Understanding of Self Driving Cars.
>>>>>>> 45080faebba51eb18f87994a5cf1050a58b78c12
