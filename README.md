### Overview

This project performs image classification on 50 Taiwanese school meal categories using transfer learning.
The dataset contains 105,402 images, highly imbalanced across classes.
To achieve better performance, this project uses:

* Dataset balancing
* Image augmentation
* Multiple pretrained CNN models
* Layer freezing / unfreezing
* Fine-tuning
* Top-1 / Top-5 accuracy evaluation
* Confusion matrix analysis
### Dataset
* 50 classes, 105,402 images
* Largest class: 3232 images
* Smallest class: 457 images
* Real-world data with strong class imbalance
* Food images with high similarity across some categories (especially vegetables)

#### Balanced Dataset
All classes are resampled to 457 images.
#### Split
Train/Test = 8 : 2
Validation = 10% of training set
