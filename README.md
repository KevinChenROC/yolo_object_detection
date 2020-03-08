# Description

Implementing filtering and non-max suppression parts of YOLO algorithm (608x608 version) for object detection task.

## Setup

1. Download [pre-trained Yolo model](https://drive.google.com/file/d/1SX80rS5ZobSDOjpFbZYASpA4i6byVoSp/view?usp=sharing) into *model_data* folder
2. Put test images in *images* folder
3. Open *yolo_object_detection.ipynb* and run all cells, 
4. Replace 0001.jpg in `predict(sess, '0001.jpg')` with the name of the image you upload 

## Acknowledgement

- Thank [deeplearning.ai](https://www.deeplearning.ai/) team to provide guidence for implementing this neural net.
- Thank [pjreddie](https://pjreddie.com/darknet/yolo/) and [allanzelener](https://github.com/allanzelener/YAD2K/pull/154/commits) for providing YOLO utility functions and model cfg and weights.
