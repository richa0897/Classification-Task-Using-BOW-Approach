# Classification-Task-Using-BOW-Approach

## Overview of Approach
To find classification of test images we perform the following steps: 

(i) automatically detect regions/points of interest, 

(ii) compute local descriptors over those regions/points, 

(iii) quantize the descriptors into words to form the visual vocabulary

(iv) find the occurrences in the image of each specific word in the vocabulary for constructing the BoW feature or a histogram of word frequencies 

(v) Perform a supervised training of ml models with the bow representation of these images and, 

(vi) Perform classification of test data into bike or horses
