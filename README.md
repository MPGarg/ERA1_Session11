# Assignment-7

## Problem Statement

![image](https://user-images.githubusercontent.com/120099863/217985996-93407e73-209e-455c-89bf-111b113e6880.png)
![image](https://user-images.githubusercontent.com/120099863/217986065-4a8acd18-707b-44c2-9746-494199523db2.png)

## Code Details

All classes & functions are defined in [link](https://github.com/MPGarg/common_repo). 

In notebook EVA8_Assigment_7.ipynb [link](EVA8_Assigment_7.ipynb) functions from the main repository are called. Model ResNet18 is trained for 20 Epochs on CIFAR10 dataset with 94.27% training and 86.56% testing accuracy.

### Training Log:

Last Few Epochs

![image](https://user-images.githubusercontent.com/120099863/217988018-1ba94527-4a42-42d3-a8a5-3696dd59a2e7.png)

### Accuracy & Loss Curve

![image](https://user-images.githubusercontent.com/120099863/217988229-25b02352-fa6c-49ff-b9af-ec8164fb2c6d.png)

### Misclassified Images

![image](https://user-images.githubusercontent.com/120099863/217988355-fe8aeb54-8f19-46a8-85b6-6e2c5bedcbad.png)

### GradCam Output

![image](https://user-images.githubusercontent.com/120099863/217988491-60008c63-7fc4-421e-ab8b-25f854fc375b.png)

## Conclusion

* It can be seen via GradCam images what the network is seeing while predicting class
* For some images it is looking beyond the main object & detecting non-similar objects. Like predicting bird instead of deer
* In some images it is getting confused between cat & dog, deer & horse
* In some cases it is covering extra areas & predicting wrongly. For e.g. plane instead of horse

