# DS4002-CS2

## Table of Contents
**1. Hook Document**

**2. Rubric**

**3. Various Materials**
- Relevant Articles:
  - These articles are included to provide context and information around the case study topic.
- SRC:
  - This folder contains all of the source code for our project. This folder contains all code used to load and combine the image data as well as structure the final model for training.
- DATA:
  - This folder is where we store all datasets being used for this project. Specifically it has three subfolders that contain all image data for the respective kind of tumor that the image displays (benign, malignant, or normal). Within each of these folders, the images are further divided into two folders titled "full" or "masked" based on the image type.
- Figures:
  -  This folder contains exploratory plots looking into the distribution of data between the three types of tumors. This folder should be populated with any additional exploratory or result plots created.

## Hook Document
- Link to Document: https://docs.google.com/document/d/1GmsvIRSqqhp4ce9Q6sBaSj5Hig9wb_g2pFEXYYaSpXY/edit?usp=sharing

## Rubric
- Link to Rubric: https://docs.google.com/document/d/1u9jtmI0qhVIF2E45JgMPDHbCnlXABrwEiZHp5QPYpuk/edit?usp=sharing

## Articles
- [embed]https://pdf.sciencedirectassets.com/311593/1-s2.0-S2352340923X00031/1-s2.0-S2352340923003669/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEoaCXVzLWVhc3QtMSJHMEUCIQCds52NciLG0LBJNayXFMoquuwqfCtWkVbbeiArTRM2kQIgCoZ4Q4ofzgO5yOW3SZo1zvXreOgIfR9v7cy5gjyTQf8qvAUIk%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDEWhID%2BzIljDNxymEyqQBRdkcy%2Ftt%2BruQA8cvRbUUZYh9o1jGUfT9p%2BI2IuPqIrKgFDlkKxKaGwkc51dPrpCTIy%2BIHhiAIrS3VBltWZzulpMitPaimHhF1dgP7lOeAdfDquITsK4o86TiNWFU2gwbW%2BbDCmLw6HF9yU6B8O44MYI2YUbxGdNUT2pVZV%2FVcJQeCuU5jSJHPVaegDYM8zFc59GkS32X2WAAmjoKmNvB%2FGFYRxrCOgOrrt5Nu2K3G9JZc1MnJxOcU5qDJfEiZtNxxGgX2WAF9at1ZD%2BAZXos8qUP6fCoAWDIq6Lhr8y5Zjhj9xBmsbbOkYy%2FbYxw5vkPnk8P%2BtUWnRFDESsobkbiUMlU3sdPdVBfn1cs1kIhuFyWIfzwxHnJ953xNvXx6Kp0B92A9fv7cSTIu%2FXXMEPoPLFFrJygtNV0th8L5XEyDn6EqLLY9IBUMaOo0ajaGBS7KyrTlCR%2BKzke1%2FcXdT9ZZ%2Fn2ZGgOA2qIb6Q29JLLPqEW3xJww2RmUSuoIiBKIhwUnGtH%2Bk%2BrD32V12QLjuAmzvfGGc6i3LXgRyFatzpayr5k%2F%2FqIoslLsIR5tAOeorSGcfRoaY4p%2ByZ3SEpWDHL2Opv7bBf93VwlyoWbRkrrIOcAIM8ndYMtNH6jqYAPSqg993YzoDdQyF3h83POW8f8q4f7HJ4OvHcXdAY4BTh%2Bxj3HkoPy6sY44HM%2BhxRRUm%2FXGVc0qSB4mdpTL2wS6xMcqPaqijIVmu614eg6LkYKEgKtD%2FlACtkMjI%2F670ILVBEpuRWkffkxGumaGih3qBREQYT5f9XQSR6YATk%2BxY9Zs9oC4M1wdoxukBPO3wBkFy%2F6vSzjofFiW1bNUKNZsdLAZwyuMbZh1xp%2FNGtRGuZwQMKMLGy2aoGOrEBu5HZ%2Bf4nASpSyjLQY4dL9XytmyP8uoGtTwXnUUwXjKAd8ruisxCRClcpphQwyFLYkxiV11%2F0Kw%2FMvtuxfalwC3Kh9m8uREHGJep5LBmroqoTAtnlzUNZYDwCD1lhGstNJNftr7CuXyD902Zmg0n29aw%2BXjkGkfkhjITQiVi0Slj9Wpw9kQ2gkR2%2Boi%2BPjNBiUwufdvXBpxo64%2FT56XOhuc%2FtXOfAQ0wLhDrwymlvNTbp&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20231116T192218Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYZZONL2SZ%2F20231116%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=3b788f016bd874bece8f3db39cf3f734177db07b4be8596376961d1847c1fc12&hash=dcc042330ead2b5b8447ce5b5f92dd461c4feaf24ca30940d4709f85a6c071b9&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2352340923003669&tid=spdf-6e340c08-aba4-426c-9874-1d0feb8e9d1e&sid=bc3a0fbd356ed34023797c15626e3f485218gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=0f155e55595d5300520359&rr=82721a1b8d43113f&cc=us[/embed]

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


## References
[1] W. Al-Dhabyani, M. Gomaa, H. Khaled, and A. Fahmy, "Dataset of breast ultrasound images," Data in Brief, vol. 28, p. 104863, 2020. [Online]. Available: https://doi.org/10.1016/j.dib.2019.104863.

[2] G. Ayana, K. Dese, and S. Choe, "Transfer Learning in Breast Cancer Diagnoses via Ultrasound Imaging," Cancers, vol. 13, no. 4, p. 738, 2021. [Online]. Available: https://doi.org/10.3390/cancers13040738.

[3] F. Chollet, "Data Preprocessing," TensorFlow, 2017. [Online]. Available: https://www.tensorflow.org/tutorials/images/transfer_learning#data_preprocessing. 
