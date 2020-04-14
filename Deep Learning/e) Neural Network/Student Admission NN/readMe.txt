Predicting Student Admissions with Neural Networks
In this notebook, we predict student admissions to graduate school at UCLA based on three pieces of data:

GRE Scores (Test)
GPA Scores (Grades)
Class rank (1-4)
The dataset originally came from here: http://www.ats.ucla.edu/

solution:
First of all, we have plotted accepted and rejected students from ou dataset. Afterwards, we separated students according to their ranks and plotted them. As ranks were from 0 to 4, we have done One Hot encoding of our rank column. Furthermore, we have done scaling of grades and Gpa between 0 and 1. After preprocessing, we splitted our dataset into train and test set using random shuffling. Afterwards, splitted our dataset into feature and target labels. At the end, we used everything for training of 2 layer neural network. Started from random weights and used gradient descent  for back propagation. During training, I have used mean squared error to calculate training loss. Accuracy = 72.5 %
