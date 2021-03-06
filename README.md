# gan-colorization
Colorization of panchromatic space images with Generative Adversarial Network

### Abstract
The colors are important in analysis and image processing. Therefore, colorization of images is useful for many applications, not only in the restoration of old images, but also in many fields of science, including automation and satellite remote sensing. This process could be described as assigning colors to the gray-scaled images in order to get the reality seen with human eyes. In this thesis, a method of colorization of panchromatic space images, which could be used in such tasks as image segmentation, detection of roads or buildings, as well as tracking of objects, was presented. To colorize images one of the state of art artificial algorithm - generative adversarial network - was used. An important part of the work was to adjust proper parameters of training. To this end, the effect of label smoothing, the learning rate value, the number of epochs have been checked, and also the network architecture has been slightly modified. The solutions used in the work were based on two spaces of color representation: RGB and CIELab.

### Data
[SpaceNet 2: Building Detection v2] (https://spacenet.ai/spacenet-buildings-dataset-v2/)

### Technologies
* Python 3
* Keras/Tensorflow
