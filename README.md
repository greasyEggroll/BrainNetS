Code for the paper under review: A Fully Automated Hybrid Ensemble Machine to Improve Brain Tumor Diagnosis
The ipynb contains all the direct code for the model combined with all the processing
The dataset is the figshare public brain tumor dataset with 3 classes
The algorithm combines the densenet architecture to extract features to train a stacking classifier consisting of a SVM and random forest tuned using randomSearch and connected to logistic regression meta classifier
