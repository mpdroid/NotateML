# Notate ML
Issue tracking for Notate ML

Preparing input image datasets is a critical and challenging task in any Machine Learning project.  Notate ML brings the power and usability of Apple's mobile devices to accelerate this task and deliver higher quality training data to your object detection model. 
FEATURES
・Create a dataset, type, scan, or speak your labels into it\
・Snap new pictures, or import old ones from your photo library\
・Crop images, draw bounding boxes, tag and label objects of interest\
・Export images and annotations for training with YOLO, Apple Create ML, or Google Auto ML

CREATING A DATASET
・Create a new data set and give it a unique name\
・Add labels in one of several ways:\
   ・One at a time, using the keyboard\
   ・Copy and paste a comma-separated list from another document\
   ・Scan from a physical text source\
   ・Use the device voice feature to speak them in\
・Labels can be edited or deleted by swiping left on each row\
・Only unused labels can be deleted

IMPORTING IMAGES
・Tap into the dataset and import photos (up to 50 at a time) from your Photo Library\
・This app can only access photos that you select using Apple's photo picker feature\

CAPTURING IMAGES FROM THE CAMERA
・While browsing the images in a dataset, tap the "Capture" button to snap new images with the camera\
・The app will require your permission to access the camera\
・If you choose to decline, you can always grant access at a later date using "Settings"\

ANNOTATING THE IMAGE
・Select an image from the dataset image browser to annotate it\
    ZOOMING and CROPPING\
   ・Pinch with two fingers to zoom in or out of the image\
   ・Drag with two fingers to move (pan) the image about\
   ・Optionally crop the image to the visible square dimensions\
   ・Cropping can only be done when the image has no bounding boxes\
   ・Double tap on the image to reset zoom and recenter the image\
   ・Tap the "Reset" button in the bottom panel to  restore image and annotations to the original state before editing\
   ・The cropped image dimensions and visible area dimensions in pixels are displayed above the image at all times\
    TAGGING
   ・Drag with one finger or stylus to draw bounding boxes around objects of interest\
   ・Long press on a box to select an existing annotation\
   ・Use the picker  to assign a label to the selected bounding box\
   ・Or tap the red Delete button to remove the selected box\
   ・Tap anywhere outside the selected box to unselect  it\
・Tap the "Reset" button to  restore image and annotations to the original state before editing\
・Tap the "Done" button to complete annotating the image\


EXPORTING THE DATASET
・While browsing dataset images, tap the "Export" button, to select export options\
・Datasets can be exported in one of three "schemas" for use with different object detector training frameworks\
・The YOLO schema generates a set of files organized for use with the YOLO framework\
・The Create ML schema generates files to use as input to Apple's Create ML application\
・The Auto ML schema generates files to use as input to Google's Auto ML service\
・ After reviewing the export options, tap the "Export" button on the Export options screen to generate data files for training\
・ Choose one of the sharing options (e.g. Airdrop, Files) enabled by your device to export the data files

DELETING
・Delete an image by swiping left in the dataset image browser\
・Delete an entire dataset by swiping left in the dataset browser\
・If a dataset contains images, you will be prompted for confirmation

Some tips
・Crop the images before tagging them\
・Use a stylus for more accurate bounding boxes\
・Maintain different datasets for training and validation\
・Limit datasets to under 1000 images each, for ease of use\
・Export and delete unused datasets to conserve storage 

