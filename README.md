# Session-11 Assignment

## Problem Statement

![image](https://github.com/MPGarg/ERA1_Session11/assets/120099863/e582adf3-906d-4987-8f23-d40a91531c46)
![image](https://github.com/MPGarg/ERA1_Session11/assets/120099863/8136af9f-c1ad-46a7-be32-e9adcbaaca3f)

## Code Details

All classes & functions are defined in [link](https://github.com/MPGarg/ERA1_main_repo). 

In notebook ERA1_S11.ipynb [link](ERA1_S11.ipynb) functions from the main repository are called. Model ResNet18 is trained for 20 Epochs on CIFAR10 dataset with 90.03% training and 89.05% test accuracy.

### Training Log:

Last Few Epochs

![image](https://github.com/MPGarg/ERA1_Session11/assets/120099863/5129ec82-ee63-442e-b6ff-837b585ac3a0)

### Accuracy & Loss Curve

![image](https://github.com/MPGarg/ERA1_Session11/assets/120099863/51163758-1d12-4bbc-bc51-076b11ee9b99)

### Misclassified Images

![image](https://github.com/MPGarg/ERA1_Session11/assets/120099863/ac22f47b-80b9-4064-8819-ff5b843ae4bf)
![image](https://github.com/MPGarg/ERA1_Session11/assets/120099863/7dc11561-ebbd-44eb-9e98-09c9796ff7ca)

### GradCam Output

![image](https://github.com/MPGarg/ERA1_Session11/assets/120099863/8f4fa336-f209-4f2d-a378-f3aa3cc04716)

## Conclusion

* It can be seen via GradCam images what the network is seeing while predicting class
* For some images it is looking beyond the main object & detecting non-similar objects. Like predicting truck instead of horse
* In some images it is getting confused between cat & dog, deer & horse
* In some cases it is covering extra areas & predicting wrongly. For e.g. plane instead of horse

