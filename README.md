# Classification of forest cover type 

<img src="https://github.com/misiungs/readme_images/blob/master/forest.jpg?raw=true" alt="drawing" width="500"/>

# Problem

This repository is about multivariate classification with use of a neural network.
The main goal is to find the neural network parameters for which accuracy will be the best.  

The data set is available under repository:  
https://archive.ics.uci.edu/ml/datasets/covertype  
It has been used in publications:  
Blackard, Jock A. and Denis J. Dean. 2000. "Comparative Accuracies of Artificial Neural Networks and Discriminant Analysis in Predicting Forest Cover Types from Cartographic Variables." Computers and Electronics in Agriculture 24(3):131-151.  
Blackard, Jock A. and Denis J. Dean. 1998. "Comparative Accuracies of Neural Networks and Discriminant Analysis in Predicting Forest Cover Types from Cartographic Variables." Second Southern Forestry GIS Conference. University of Georgia. Athens, GA. Pages 189-199.  
Blackard, Jock A. 1998. "Comparison of Neural Networks and Discriminant Analysis in Predicting Forest Cover Types." Ph.D. dissertation. Department of Forest Sciences. Colorado State University. Fort Collins, Colorado. 165 pages.  

# Approach

The classification problem is about predicting forest cover type based on cartographic variables only. 
In total 12 features (54 after one hot encoding) is used to categorize cover into one of 7 classes. 
For classification deep neural networks in tensorflow have been used.
Various hyperparameters have been tunned to achieve the best possible results.

# Conclusions
The final achieved accuracy is 94.03%.
This a satisfactory result since is almost 24% better than the one in the original paper.

