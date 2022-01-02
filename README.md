# OBJECT DETECTION USING MASK R-CNN

# Description:

## MASK R-CNN 
Mask R-CNN is a state of the art model for instance segmentation, developed on top of Faster R-CNN. Faster R-CNN is a region-based 
convolutional neural networks,that returns bounding boxes for each object and its class label with a confidence score.
Mask R-CNN is an extension of Faster R-CNN with additional branch for predicting segmentation masks on each Region of Interest (RoI).


![sample_image1](https://user-images.githubusercontent.com/55678844/147868029-3cf9eedd-d72c-4e5b-9e22-740175825ca7.png)
![sample_image2](https://user-images.githubusercontent.com/55678844/147868032-db50d80f-8627-44ab-8835-75682b66ee24.png)

# Project Structure

1. For the purpose of this project, we will use Custom dataset which is a collection Car and Truck Images. 
2. Data Annotation
    - For annotation there are many tool which we can use:
      - VGG Image Annotator - https://www.robots.ox.ac.uk/~vgg/software/via/
      - makesense.ai - https://www.makesense.ai/
    - I have used VGG Annotator because in VGG Annotator we can Annotate multiple classes Objects at same time but we can not do this in makesense.ai.
    - After Annotating all the images .I have used Annotations in the form of JSON format there are other formats also available that we could use.

3. Model Training
    - I have used this github repo for training the **MASK R-CNN** model - https://github.com/matterport/Mask_RCNN from this repo we need only **mrcnn** folder. 
    - We can download the repo or we can clone it by using **git clone --repo url** command.
    - I have used Pretrained weights **mask_rcnn_coco.h5**. 
    - We need to make or update custom.py file for transfer learning as per our use. 

# Libraries with Versions
1.TensorFlow 1.3, Keras 2.0.8 


   
