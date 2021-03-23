# E6691 Advanced Deep Learning Assignment 2 - Spring 2021

## Data Description
This is an assignment for Sign Language MNIST Competition:
The original MNIST image dataset of handwritten digits is a popular benchmark for image-based machine learning methods but researchers have renewed efforts to update it and develop drop-in replacements that are more challenging for computer vision and original for real-world applications. Since everyone is familiar with MNIST dataset, the Sign Language MNIST is presented here and follows the same CSV format with labels and pixel values in single rows to challenge you.

The American Sign Language letter database of hand gestures represent a multi-class problem with 24 classes of letters (excluding J and Z which require motion).

The dataset format is patterned to match closely with the classic MNIST. Each training and test case represents a label (0-25) as a one-to-one map for each alphabetic letter A-Z (and no cases for 9=J or 25=Z because of gesture motions). The training data (27,455 cases) and test data (7172 cases) are approximately half the size of the standard MNIST but otherwise similar with a header row of label, pixel1, pixel2….pixel784 which represent a single 28x28 pixel image with grayscale values between 0-255. 

## Dependencies
Python libraries needed:
* numpy
* torch
* pandas
* string
* matplotlib
* seaborn

## Executing program
Please run jupyter notebook:"Sign_Language_MNIST_Competition_Lechen.ipynb"


## Additional information
<br>
Assignment 2 is a in-class Kaggle competition in which you need to design your deep learning models and submit your results to receive credits.

You will find more details (competition intro, data description, etc.) in the link below.


Kaggle Link:  https://www.kaggle.com/c/sign-competition-mnist-e6691-2021spring/ (Links to an external site.)

Invitation Link: https://www.kaggle.com/t/605f40ed43d54d91bc7d5ed20d6df1cd (Links to an external site.)

 

A few notes:

- **One student per team.** Create your own team with your UNI in Kaggle competition.
- **No plagiarism.** Transferring learning is accepted but must be cited properly.
- **Only PyTorch.** Feel free to use the Google Cloud and the common image we provided.
- **Coding Style matters.** Be careful to your coding style by naming properly, using functions, comments properly, etc.
- TO BE UPDATED.
