# Semantic-Segmentation
a tensorflow implementation for scene understanding and object detection using Semantic segmentation 

## Semantic Segmentation
In semantic segmentation, By putting an image into a neural network, it generates an output a category for every pixel in the image. Now the output is a discrete set of categories, much like in a classification task. But instead of assigning a single class to an image, we want to assign a class to every pixel in that image. 

### Limitations of This Approach
* very expensive to label this data (labeling every pixel)
* computationally expensive to maintain spatial information in each convolutional layer

### Build the model
DeepLab is a state-of-art deep learning model for semantic image segmentation, where the goal is to assign semantic labels (e.g., person, dog, cat, car and so on) to every pixel in the input image. Some segmentation results :

### Reference 
* [FCN paper]
* [Hierarchical Multi-Scale Attention for semantic segmentation](https://arxiv.org/abs/2005.10821)
