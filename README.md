# OBJECT DETECTION USING MASK R-CNN

# Description:

## MASK R-CNN 
Mask R-CNN is a state of the art model for instance segmentation, developed on top of Faster R-CNN. Faster R-CNN is a region-based 
convolutional neural networks,that returns bounding boxes for each object and its class label with a confidence score.
Mask R-CNN is an extension of Faster R-CNN with additional branch for predicting segmentation masks on each Region of Interest (RoI).

# Project Structure

1. For the purpose of this project, we will use Custom dataset which is a collection Car and Truck Images. 
2. Data Annotation
    - For annotation there are many tool which we can use:
      - VGG Image Annotator - https://www.robots.ox.ac.uk/~vgg/software/via/
      - makesense.ai - https://www.makesense.ai/
    - I have used VGG Annotator because in VGG Annotator we can Annotate multiple classes Objects at same time we can not do this in makesense.ai.
    - After Annotation I have used Annotations in the form of JSON format there are other formats as well we could use.

3. Model Training
    - This code is an implementation of the methodology described in this research paper by Gregory Koch et al. 
      Model architecture and hyper-parameters that I have used are all as described in the paper
    - The two Convolutional Neural Networks are not different networks but are two copies of the same network, 
      hence the name Siamese Networks. Basically they share the same parameters.

# Libraries with Versions
1.TensorFlow 1.3, Keras 2.0.8 


   
