# Face-Image-Classification-Python-
In face detection, we attempt to infer a discrete label indicating whether a face is present or 
not based on observed image data. Through this project I aim to achieve face image classification 
using Gaussian model, Mixture of Gaussian model, t-distribution, Mixture of t-distribution, 
and Factor Analysis. 

The database used in this project is the Fddb folds DB. It can be found here:
http://vis-www.cs.umass.edu/fddb/
The images used for training and testing the classifiers have not been included since it exceeds the file size limit.

For each classification model the results are reported as follows:
1. Visualization of the the estimated mean(s) and covariance matrix for face and non-face 
respectively.
2. Evaluation of the learned model on the testing images using 0.5 as threshold for the 
posterior by computing the false positive rate, false negative rate and the misclassification 
rate.
3. Plot of the Receiver Operating Characteristic Curve (ROC Curve) to evaluate the diagnostic 
ability of the binary classifier.
