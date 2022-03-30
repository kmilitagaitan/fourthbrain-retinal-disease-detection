# Retinal Disease Detection

Color-filtered fundus images visualize the rear of an eye called retina (Figure 1). Fundus image provides doctors with a snapshot on the interior of the eye of patients. Based on this type of image, doctor will be able to read abnormalities present on the back of the eye, thus making diagnosis easier and more accurate. Many eye diseases can be found using fundus images, such as diabetic retinopathy, glaucoma, and macular degeneration.
Current available public datasets (EYEPACS, Messidor, etc.), although rich in quantity, only focus on diabetic retinopathy. However, more often than not, a patient can have two or more diseases concurrently. To overcome these 2 problems, we take other common diseases into consideration and create a multi-labeled dataset. The following will describe the dataset in details.

## Problem Description

The dataset includes 3,285 images from CTEH (3.210 abnormals and 75 normals) and 500 normal images from Messidor and EYEPACS dataset. The abnormalities include: opacity, diabetic retinopathy, glaucoma, macular edema, macular degeneration, and retinal vascular occlusion
In this assignment, we will use 3,435 images for training and predict diseases on 350 unlabeled images.

## References

 - [Data Augmentation](https://machinelearningmastery.com/how-to-configure-image-data-augmentation-when-training-deep-learning-neural-networks/)
 - [Densenet](https://towardsdatascience.com/creating-densenet-121-with-tensorflow-edbc08a956d8)
 - [Fundus Imaging Paper](https://pubmed.ncbi.nlm.nih.gov/33918998/)