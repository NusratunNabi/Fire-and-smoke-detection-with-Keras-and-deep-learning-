
fire-smoke-detection - v6 2023-08-18 7:40am
==============================

This dataset was exported via roboflow.com on September 20, 2024 at 2:25 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 3203 images.
Fire-smoke-detection-boxes-to-segmentations are annotated in YOLO v3 (Keras) format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 2 versions of each source image:
* 50% probability of horizontal flip
* Salt and pepper noise was applied to 5 percent of pixels

The following transformations were applied to the bounding boxes of each image:
* Random rotation of between -15 and +15 degrees


