# Mask R-CNN for Object Detection and Segmentation on the Videos and Images

The Mask R-CNN model generates bounding boxes and segmentation masks for each instance of an object in the image. It's based on Feature Pyramid Network (FPN) and a ResNet101 backbone.This is simple, flexible, and general framework for object instance segmentation. The method Mask R-CNN efficiently detects objects in an image while simultaneously generating a high-quality segmentation mask for each instance.

The method, called Mask R-CNN, extends Faster R-CNN by adding a branch for predicting an object mask in parallel with the existing branch for bounding box recognition. Mask R-CNN is simple to train and adds only a small overhead to Faster R-CNN, running at 5 fps.

# Step by Step Detection

# 1. Anchor sorting and filtering

Visualizes every step of the first stage Region Proposal Network and displays positive and negative anchors along with anchor box refinement.
![](assets/detection_anchors.png)
