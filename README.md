# MLP-Classifier-DLBCL - MLP-COO
Developed a python implemented deep learning based classifier for classifying cell of origin based gene expression data of DLBCL in to its subtypes ABC and GCB

MLP-COO is a DLBCL classification model with high accuracy (99.67%) that is built using multilayer perceptron ,i.e., subtype of feedforward artificial neural network (ANN). This model classify DLBCL cases on the basis of gene expression into ABC (activating B-cell like) and GCB ( germinal center B-cell like).

MLP-COO.model.pkl - This python pickle file contains trained model that is used for classification of user input data.

MLP_COO.py - This python script is used for loading the pickle file, which then classify the user input DLBCL data into two classes i.e., ABC and GCB.

Running the Classifier

Download all the attached files and place them under same directory.
Before running the model, kindly prepare input gene expression data as given in Example_input.csv.
Load the pickle file (binary files containing our trained model) using python script.
The output file will be automatically saved in working directory as MLP-COO.output.txt containing Sample ID and predicted class.
