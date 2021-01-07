# Classification of woods pecies based on images

Classification of woods pecies based on high resolution images from brazilian forests. A theory and pipeline is contained in the Report.pdf file.

Files in directiry:
Forest_Species.ipynb - Solution file. After fully finished working, notebook it will create models in directory
Report - Report about practical assignment
requirement - Third party library versions
DenseNet_log - Logs of learning process of DenseNet model
Resnet50 - Logs of learning process of Resnet50 model

How to use:
Open Jupyter notebook on machine with GPU or in Google Colab, just run all ceils inside notebook.
Notebook will download archives with datasets, unzip images, save their reshaped versions.
After training process, in directory will apear logs about learning process and pytorch models. 
