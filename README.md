# Class-Activation-Maps
This project implements Class Activation Maps (CAM), a technique used to visualize the regions of an image that contribute most to a particular class prediction made by a Convolutional Neural Network (CNN).


## Overview
Class Activation Maps are a visualization technique that helps interpret CNNs by highlighting which parts of an image are most influential in determining the network's prediction for a specific class. This implementation demonstrates CAM using a pre-trained CNN model (such as VGG16, ResNet, etc.) and shows heatmaps overlaid on input images to indicate activated regions.

## Installation
To use this implementation, clone the repository:

```git clone https://github.com/aneeshbajwa/Class-Activation-Maps.git```

## Examples

### Input Image - from [Caltect-256 dataset](https://data.caltech.edu/records/nyy15-4j048)
![alt text](https://github.com/aneeshbajwa/Class-Activation-Maps/blob/1edaf92cc1d39ed06090796aef38d4926cea7948/Test_image.png)

### Class Activation Map (CAM) Overlay
![alt text](https://github.com/aneeshbajwa/Class-Activation-Maps/blob/1edaf92cc1d39ed06090796aef38d4926cea7948/CAM_Overlay.png)

## Credits
This project draws inspiration from the work on [Class Activation Maps by Zhou et al. (2016)](http://cnnlocalization.csail.mit.edu/Zhou_Learning_Deep_Features_CVPR_2016_paper.pdf).
