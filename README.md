# Garbage Classification Dataset 🗑️📊
This repository contains a dataset of 13,714 labeled images for garbage classification. The images are annotated in YOLO format, with labels for various waste categories. This dataset is designed to aid in the development of object detection models for garbage collection and segregation tasks.

## Dataset Overview
The dataset contains images of garbage categorized into 7 classes. This dataset is ideal for training models for automatic waste classification systems or for integration into autonomous robots used for garbage collection and segregation.
### Classes:
- 0: Cardboard
- 1: Miscellaneous
- 2: Organic
- 3: Paper
- 4: Glass
- 5: Metal
- 6: Plastic

### Dataset Structure:
- **images**: Contains all the images in the dataset.

- **labels**: Contains the YOLO annotation files corresponding to each image. Each .txt file contains the class index and bounding box coordinates for the objects in the image.

- **data.yaml**: Configuration file containing dataset paths and class names.

