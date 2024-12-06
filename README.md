# Read Me for Finding-the-diameter-of-an-image-within-MATLAB
MATLAB is a useful resource that is used by engineers for programming, graphing, math, etc...
## Status
### [Unreleased]
## Creator: J. Coburn
## Created: 2024.11.13
## Last Editor: 
## Last Edited:
## Kind of Output to Handle
Image input, object type/shape, calibration input, selection of the region of interest, user input for fine-tuning, and measurement output.
## Two names of user functions and their general purposes
"ProcessImage", the general purpose of this user function is to handle image preprocessing, including steps like converting the image to grayscale, applying thresholding, and detecting edges. This function prepares the image for further analysis by extracting relevant features that will allow for accurate diameter measurement. Another user function is "measureDiameter",  the general purpose of this user function is to calculate the diameter of the object in the image. It uses the processed binary image to identify the object, then calculates its diameter based on either the major axis or the bounding box. If a calibration factor is provided, it will also convert the diameter from pixels to real-world units. 
## The kind of output that will be returned
The kind of output I will return for this project are "processImage" function output and "measureDiameter" function output.
## Why this program is useful
This program is useful because it is non-destructive measurement, has a wide range of applications, it is precise, efficient, versatile across fields, cost-effective, has real-time processing, is useful for research purposes, while this program can be integrated with other tools.
