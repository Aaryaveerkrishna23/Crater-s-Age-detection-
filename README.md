# Crater-s-Age-detection-
**Southern Lunar Crater Age Classification**
## Overview
This repository contains a machine learning script designed to classify Southern Lunar craters into different age groups. The craters are classified into five age categories: pre-Nectarian, Nectarian, Imbrian, Eratosthenian, and Copernican. The goal is to accurately predict the age of lunar craters based on certain features.

## Project Highlights
Dataset
The dataset comprises Southern Lunar craters classified into five distinct age groups. The original dataset posed a challenge due to its relatively small size, and removing outliers resulted in a significant loss of data (20%).

## Approach
After rigorous experimentation, it was observed that using a Robust Scaler proved to be optimal for handling outliers in such a small dataset. This decision was motivated by the need to retain as much data as possible while still achieving reliable classification results.

## Classification Results
The project yielded promising results, with the best accuracy achieved when classifying craters into three main classes: old craters, middle-aged craters, and new craters. The accuracy of this classification reached 67.8%, showcasing strong generalization capabilities. Importantly, all tests were conducted on a strict test dataset, maintaining the same distribution as the original input, and ensuring the absence of oversampling or data leakage.

## Here are specific results for various classification scenarios:

Classifying only Nectarian and Pre-Nectarian craters with Robust Scaler: 74% accuracy
Classifying Nectarian, Pre-Nectarian, and an additional "Other" class: 64% accuracy.
Classifying only the three classes (Old, Middle, New) with Robust Scaler: 66.6% accuracy.
## Usage
To replicate or build upon these results, follow the steps outlined in the provided machine learning script. Ensure that the dataset is appropriately formatted and that the Robust Scaler is utilized for optimal performance.


