# DS4002-CS2

## Table of Contents
**Hook Document**

**Rubric**

**Various Materials**

- SRC:
  - This folder contains all of the source code for our project. This folder contains all code used to load and combine the image data as well as structure the final model for training.
- DATA:
  - This folder is where we store all datasets being used for this project. Specifically it has three subfolders that contain all image data for the respective kind of tumor that the image displays (benign, malignant, or normal). Within each of these folders, the images are further divided into two folders titled "full" or "masked" based on the image type.
- Figures:
  -  This folder contains exploratory plots looking into the distribution of data between the three types of tumors. It also contains a confusion matrix displaying the results of our model.
## Hook Document

## Rubric

## SRC
### Installing/ Building our code
- It is recommended to run the notebook files in an IDE that supports both Jupyter Notebooks and R markdown files such as Pycharm.
- These files use the 'tidyverse' and 'dplyr' R libraries and the json, re, pickle, numpy, pandas and sklearn Python libraries
- File paths may be incorrect on your machine, you are recommended to check all file paths before running.

### Notebook Files
| Notebook Name | Decription |
| -------- | -------- |
| transfer_learning.ipynb | This notebook contains all code used for the completion of the project. This includes data cleaning, creating the dataset, transfer learning with MobileNetV2, and fine tuning the model. |

### Usage
- To use this model, first unpickle it. Then call the sklearn method predict(data) to get predictions.

## DATA
### Dataset Dictionary
| Column Name | Definition | 
| -------- | -------- |
| Image | Breast Ultrasound Image file (json format)|
| Classification | Type of tumor (benign, malignant, or normal)|

## Figures
| Figure | Takeaways | 
| -------- | -------- |
|  ![Figure 1](Figures/Tumor_Distribution.png) | This plot was used during the exploratory phase of the project. It provided a way to visualize the spread of the data across the three possible types of ultrasound images. From this plot we were able to see that benign had the most image data while normal has by far the least. |
|  ![Figure 2](Figures/results.png) | This figure is a confusion matrix of our results of the classification model created for this project. As you can see, this model shows that we were able to accurately classify a breast cancer tumor 90% of the time based on an ultrasound image. Specifically, there were only two false cases for the malignant tumor classification, which is extremely important given the severity of that diagnosis. |


## References
[1] W. Al-Dhabyani, M. Gomaa, H. Khaled, and A. Fahmy, "Dataset of breast ultrasound images," Data in Brief, vol. 28, p. 104863, 2020. [Online]. Available: https://doi.org/10.1016/j.dib.2019.104863.

[2] G. Ayana, K. Dese, and S. Choe, "Transfer Learning in Breast Cancer Diagnoses via Ultrasound Imaging," Cancers, vol. 13, no. 4, p. 738, 2021. [Online]. Available: https://doi.org/10.3390/cancers13040738.

[3] F. Chollet, "Data Preprocessing," TensorFlow, 2017. [Online]. Available: https://www.tensorflow.org/tutorials/images/transfer_learning#data_preprocessing. 
