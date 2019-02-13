# ISIC 2018: Skin Lesion Analysis Towards Melanoma Detection

This repository presents results of our work to detect Melanoma by Skin Lesion Analysis.

## About ISIC
The International Skin Imaging Collaboration (ISIC) is an international effort to improve melanoma diagnosis, sponsored by the International Society for Digital Imaging of the Skin (ISDIS). The ISIC Archive contains the largest publicly available collection of quality controlled dermoscopic images of skin lesions.

The goal of this [challenge] (https://challenge2018.isic-archive.com) is to help participants develop image analysis tools to enable the automated diagnosis of melanoma from dermoscopic images.

This challenge is broken into three separate tasks:
Task 1: Lesion Segmentation  
Task 2: Lesion Attribute Detection
Task 3: Disease Classification

Ours results are for Task 3: Disease Classification

Possible disease categories are:
| 1   | Melanoma |
| 2   | Melanocytic nevus |
| 3   | Basal cell carcinoma |
| 4   | Actinic keratosis / Bowen’s disease (intraepithelial carcinoma) |
| 5   | Benign keratosis (solar lentigo / seborrheic keratosis / lichen planus-like keratosis) |
| 6   | Dermatofibroma |
| 7   | Vascular lesion |

 
## Results
Following Graphs show Model Accuracy for Training and Testing Phase; Model Loss for Training and Testing Phase; and Computation Time for Training the model and Training plus Tresting the model.



## Sanity Check
Following are five random images that were picked and detected one of the disease categories by our model

![Pred1](https://github.com/naneja/isic2018/blob/master/figs/pred1.png)

## Dataset Size
Below is the Training Dataset consisting of 10,015 images for different disease categories
| Sr.No. | Disease | Training Files |
|:-------------:|:-------------:|:-------------:|
| 1   | Melanoma | 1113 |
| 2   | Melanocytic nevus | 6705 |
| 3   | Basal cell carcinoma | 514 |
| 4   | Actinic keratosis / Bowen’s disease (intraepithelial carcinoma) | 327 |
| 5   | Benign keratosis (solar lentigo / seborrheic keratosis / lichen planus-like keratosis) | 1099 |
| 6   | Dermatofibroma | 115 |
| 7   | Vascular lesion | 142 |


## Feedback
Please submit your feedback to [Dr. Nagender Aneja](http://expert.ubd.edu.bn/nagender.aneja). Please write an email (nagender.aneja@ubd.edu.bn) if you are interested to impement the model in a mobile app or web app. We welcome people and organization who can provide more data on plants from different countries to join this project. 

## Project Members
*  [Dr. Nagender Aneja](http://expert.ubd.edu.bn/nagender.aneja), nagender.aneja@ubd.edu.bn
*  [Dr. Sandhya Aneja](http://expert.ubd.edu.bn/sandhya.aneja), sandhya.aneja@ubd.edu.bn
