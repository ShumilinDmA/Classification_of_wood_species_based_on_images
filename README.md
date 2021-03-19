# Classification of woods species based on images

Classification of woods species based on high-resolution images from Brazilian forests. A theory and pipeline are contained in the Report.pdf file.

Files in directory:
* Forest_Species.ipynb - Solution file. After fully finished working, the notebook will create models in the directory
* Report - Report about the practical assignment
* requirement - Third side libraries versions
* DenseNet_log - Logs of the learning process of DenseNet model
* Resnet50 - Logs of the learning process of Resnet50 model

How to use:
Open Jupyter notebook on a machine with GPU or in Google Colab, just run all ceils inside the notebook.
The notebook will download archives with datasets, unzip images, save their reshaped versions.
After the training process, in a directory will appear logs about the learning process and pytorch models. 

Results:
* The problem of classification of high-resolution images of 41 tree species by the type of cut structure is solved 
* The Pytorch and Catalyst frameworks were used. Was created an ensemble of heavyweight models with an F1 score of 98.7 percent
* Was used knowledge distillation of the ensemble of models in AlexNet, F1 score became 96.3 percent, the inference time was decreased in 3 times compared to the fastest model in the ensemble.
