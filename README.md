# -CNN-Cancer-Detection-Kaggle-Mini-Project

In this competition, we must create an algorithm to identify metastatic cancer in small
image patches taken from larger digital pathology scans. The data for this competition
is a slightly modified version of the PatchCamelyon (PCam) benchmark dataset (the
original PCam dataset contains duplicate images due to its probabilistic sampling, how-
ever, the version presented on Kaggle does not contain duplicates).
In this dataset, we are provided with a large number of small pathology images to
classify. Files are named with an image id. The train labels.csv file provides the ground
truth for the images in the train folder. We are predicting the labels for the images
in the test folder. A positive label indicates that the center 32x32px region of a patch
contains at least one pixel of tumor tissue. Tumor tissue in the outer region of the patch
does not influence the label. This outer region is provided to enable fullyconvolutional
models that do not use zero-padding, to ensure consistent behavior when applied to a
whole-slide image

Note : The starter jupyter notebook code was around 29 MB which is larger than what github allows for upload so it has been uploaded as a zipped file that only contains nasnet_starter_1.ipynb.
