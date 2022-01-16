# Notate ML
Issue tracking for Notate ML

Preparing input image datasets is a critical and challenging task in any Machine Learning project. Notate ML brings the power and usability of Apple's mobile devices to help accelerate this task and deliver higher quality training data to your object detection model. 

・Create a dataset, type, scan, or speak your labels into it\
・Snap new pictures, or import old ones from your photo library\
・Crop, draw bounding boxes and tag the objects of interest\
・Export images and annotations for training with YOLO, Apple Create ML, or Google Auto ML

CREATING A DATASET 
・Create a new data set and give it a unique name\
・Add labels in one of several ways\
  ・One at a time, using the keyboard\
  ・Copy and paste a comma-separated list from another document\
  ・Scan from a physical text source\
  ・Use the device voice feature to speak them in\
・Labels can be edited or deleted by swiping left on them\
・Only unused labels can be deleted

IMPORTING IMAGES
・Click into the dataset and import photos (up to 50 at a time) from your Photo Library\
・This app can only access those photos that you have selected using Apple's photo picker feature

CAPTURING IMAGES FROM THE CAMERA
・Click on the "Capture" button to snap new images with the camera\
・The app will require your permission to access the camera\
・If you choose to decline, you can always grant access at a later date using "Settings"

ANNOTATING THE IMAGE
・Select an image from the dataset image browser to annotate it

 ZOOM mode
 ・Switch to the "ZOOM" mode to zoom and pan into a region of interest within the image\
 ・Crop the image to the visible square dimensions\
 ・Cropping to square dimensions is optional but recommended (as most object detection frameworks use square-shaped inputs)\
 ・Cropping can be done when the image has no bounding boxes\
 ・Double tap on the image to reset to the current crop dimensions\
 ・Click the "Reset" button to undo cropping and reset to the original image dimensions\
 ・The cropped image dimensions and visible area dimensions in pixels are displayed above the image at all times

 TAG mode
 ・Switch to the "TAG" mode and use finger or stylus to draw bounding boxes around the objects of interest\
 ・Use the picker wheel above the image to assign a label to the currently selected bounding box\
 ・Press and hold a bounding box to select and tap outside to unselect\
 ・The Undo button removes the most recent bounding box

・Save the current annotation edits or discard them to return to the dataset image browser

EXPORTING THE DATASET
・Datasets can be exported in one of three "schemas" for use with different object detector training frameworks\
・The YOLO schema generates a set of files organized for use with the [YOLO](https://pjreddie.com/darknet/yolo/) ( [YOLOv4]](https://github.com/AlexeyAB)) framework\
・The Create ML schema generates files to use as input to Apple's [Create ML](https://developer.apple.com/machine-learning/create-ml/) application\
・The Auto ML schema generates files to use as input to Google's [Auto ML](https://cloud.google.com/automl) service

DELETING
・Delete an image by swiping left in the dataset image browser\
・Delete an entire dataset by swiping left in the dataset browser\
・If a dataset contains images, you will be prompted for confirmation

Some tips
・Crop the images to square size before tagging the objects\
・Use a stylus for more accurate bounding boxes\
・Maintain different datasets for training and validation\
・Limit datasets to under 1000 images each for ease of use\
・Export and delete unused datasets to conserve storage 
