# Udacity_Sensor-Fusion
This is my project for Udacity Self Driving Cars Nano Degree Second Module Sensor fusion Mid Term Project

# Goals
- Compute lidar Point-Cloud from Range Image
- Create Birds-Eye View for Lidar PCL
- Object detection in BEV image using pretrained model
- Evaluate Models Object Detection

# Process

## Visualize range image channels
Find in images folder 2 images from different data sets for range and intensity stacked together
## Visualze point-cloud
Find examples in Examples in Visualized Point Cloud folder for samples for vehiles with it's features appear

## BEV-map coordinates
## Compute intensity layer of bev-map
Adjusted so vehicles are visible
## Compute height layer of bev-map

## Add Second Model
Model fpn_resnet added
hyper parameters added (taken from test.py file)
## Bounding boxes
boxes are added but noted that x,y need to be flipped as the BEV requires this

## IOU calculate & count true positive
## Count false negative and false positive
## compute percision and recall

# Conculusion
In this project I used the knowledge I gain from the lessons to extract lidar data from the waymo dataset and generate images for channels needed to later use it with a Machine learning model to make it useful and detect the surrounding and finally evaluate the model my self according to my data and results I got.

