# Errata, Corrections and Improvements
----------------------------------------------------
If you find any mistakes in The Kaggle Book, or if you have suggestions for improvements, then please [raise an issue in this repository](https://github.com/PacktPublishing/The-Kaggle-Book/issues), or email to us.


## Chapter 05, Page no 116, Table 5.1 - Fixed description as per table cells

<img src="https://github.com/PacktPublishing/The-Kaggle-Book/blob/main/Errata image/Errata-Table5.1.PNG">






Here is how we define the cells:
* **TP (true positives)**: These are located in the `lower-right cell`, containing examples that have been correctly predicted as positive ones.
* **FP (false positives)**: These are located in the `upper-right cell`, containing examples that have been predicted as positive but are actually negative.
* **FN (false negatives)**: These are located in the `lower-left cell`, containing examples that have been predicted as negative but are actually positive.
* **TN (true negatives)**: These are located in the `upper-left cell`, containing examples that have been correctly predicted as negative ones.


## Chapter 05, Page no 110, Mean squared error (MSE) and R squared

Following is the correct formula for `R squared` "co-efficient of determination":

<img src="https://github.com/PacktPublishing/The-Kaggle-Book/blob/main/Errata image/Rsquared.png">

## Chapter 05, Page no 121, correct reference to the panel in an image

The first paragraph says: "A bad classifier can be spotted by the ROC curve appearing very similar, if not identical, to the diagonal of the chart, which represents the performance of a purely random classifier, as in the top right of Figure 5.3; ROC-AUC scores near 0.5 are considered to be almost random results."

## Chapter 05, Page no 130, typo in the name of the model SSD

The last line of the note should say: ".....YOLO (https://arxiv.org/abs/1506.02640v1), Faster R-CNN https://arxiv.org/abs/1506.01497v1), or SSD (https://arxiv.org/abs/1512.02325)."

## Chapter 06, Page no 183, reference to test case number

Change "only 1,495" to "about 24,500"

## Chapter 06, Page no 184, feature_19 and feature_54

Instead of feature_19 and feature_54, the correct features that appear the most different between the training/test split are cont14, cont4, and cont5.
