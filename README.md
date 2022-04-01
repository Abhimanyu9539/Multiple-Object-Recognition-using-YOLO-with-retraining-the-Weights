# Multiple-Object-Recognition-using-YOLO-with-retraining-the-Weights
Multiple Object Recognition using YOLO with retraining the Weights

## Data Collection and Labeling with LabelImg

- To create a custom object detector, we need an excellent dataset of images and labels so that the sensor can efficiently train to detect objects.

- We can do this in two ways.

- Using Google's Open Images Dataset

- We can gather thousands of images and their auto-generated labels within minutes. Explore that dataset here!

## Creating your dataset and then labeling it manually

- We will create a dataset manually by collecting images from google image scraper or manually clicking them and then marking them using an image annotation tool, LabelImg.

 
## Building a YOLOv4 Object Detector with Darknet in the Cloud

- Enabling GPU within your notebook

- Cloning and Building Darknet

- downloading AlexeyAB's famous repository and adjusting the Makefile to enable OPENCV and GPU for darknet and then build darknet.

 

## Demo on Pretrained model

- YOLOv4 is trained on the coco dataset, which has 80 classes that it can predict. We will take these pre-trained weights to see how it results on some of the images.

 

## Customize YOLOv4 with the different command-line flags

- Threshold Flag

- Output Bounding Box Coordinates

- Don’t Show Image

- Multiple Images at Once

## Preparing dataset for training Yolo

- Labeled Custom Dataset

- Custom .cfg file

- Edit the yolov4.cfg for your custom model training using the google colab editor 

- obj.data and obj.names files

- train.txt and test.txt file

- The train.txt and test.txt files hold the relative paths to all our training and validation images.

## Train Your Custom Object Detector

## Training Yolo model from a checkpoint

## Model Evaluation using Mean Average Precision

## Predictions on images

## Predictions on Video
