# Detection of Surface Cracks using Deep Learning
Detection of Surface Cracks in Concrete Structures using Deep Learning

Detection of surface cracks is an important task in monitoring the structural health of concrete structures. 
If cracks develop and continue to propogate, they reduce the effective load bearing surface area and can over time cause failure of the structure. 
The manual process of crack detection is painstakingly time-consuming and suffers from subjective judgments of inspectors. 
Manual inspection can also be difficult to perform in case of high rise buildings and bridges. In this blog, we use deep learning to build a simple yet very accurate model for crack detection. 
Furthermore, we test the model on real world data and see that the model is accurate in detecting surface cracks in concrete and non concrete structures example roads. 

Todo:
[] Add Sequential rather than one model to the last layer of pre-trained ResNet18
[] Add transformation, e.g. RandomResizedCrop, CenterCrop, RandomRotation, RandomHorizontalFlip, RandomVerticalFlip, ColorJitter.
[] Add dropouts.
[] Test on images that are randomly found on internet.
[] Highlight crack.
