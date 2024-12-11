# Read Me for Finding-the-diameter-of-an-image-within-MATLAB
MATLAB is a useful resource that is used by engineers for programming, graphing, math, etc...
## Status
### [Unreleased]
## Creator: J. Coburn
## Created: 2024.11.13
## Last Editor: J. Coburn
## Last Edited: 2024.12.11
## Kind of Output to Handle
Image input, object type/shape, calibration input, selection of the region of interest, user input for fine-tuning, and measurement output.
## Two names of user functions and their general purposes
"ProcessImage", the general purpose of this user function is to handle image preprocessing, including steps like converting the image to grayscale, applying thresholding, and detecting edges. This function prepares the image for further analysis by extracting relevant features that will allow for accurate diameter measurement. Another user function is "measureDiameter",  the general purpose of this user function is to calculate the diameter of the object in the image. It uses the processed binary image to identify the object, then calculates its diameter based on either the major axis or the bounding box. If a calibration factor is provided, it will also convert the diameter from pixels to real-world units. 
## The kind of output that will be returned
The kind of output I will return for this project are "processImage" function output and "measureDiameter" function output.
## Why this program is useful
This program is useful because it is non-destructive measurement, has a wide range of applications, it is precise, efficient, versatile across fields, cost-effective, has real-time processing, is useful for research purposes, while this program can be integrated with other tools.
### Bugs and Updates
### [0.1.1] - 2024.12.11
When requesting calibration input, I made the calibrationFactor = 1; since there I didn't have a set diameter and number of pixels for the image I displayed. 
### [0.1.2] - 2024.12.11
When requesting region of interest (ROI) selection from the user, I was able to select the region of the image I displayed in the shape I desired which was a rectangle. Even though the code runs and displays my image and the region of interest I requested, MATLAB indicates that there is some sort of error within my code and that I have too many output arguments when requesting the region of interest for the image I displayed. 


## License
J. Coburn, hereby disclaims all copyight interest in the progam "Finding the diameter of an image within MATLAB" (which creates images within MATLAB and finds the diameter of these images) written by J. Coburn.

signature of J. Coburn 11 December 2024
J. Coburn, Owner

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.
