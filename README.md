# Classification of woods pecies based on images

Classification of woods pecies based on high resolution images from brazilian forests. A theory and pipeline is contained in the Report.pdf file.

Files in directiry:
* Forest_Species.ipynb - Solution file. After fully finished working, notebook it will create models in directory
* Report - Report about practical assignment
* requirement - Third side libraries versions
* DenseNet_log - Logs of learning process of DenseNet model
* Resnet50 - Logs of learning process of Resnet50 model

How to use:
Open Jupyter notebook on machine with GPU or in Google Colab, just run all ceils inside notebook.
Notebook will download archives with datasets, unzip images, save their reshaped versions.
After training process, in directory will apear logs about learning process and pytorch models. 

Results:
* The problem of classification of high-resolution images of 41 tree species by the type of cut structure is solved 
* The Pytorch and Catalyst frameworks were used. Was created ensemble of heavyweight models with an F1 score 98.7 percent
* Was used knowledge distillation of the ensemble of models in AlexNet, F1 score became 96.3 percent, the inference time was decreased in 3 times compared to the fastest model in the ensemble.
