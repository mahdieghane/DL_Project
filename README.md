# DL_Project
In this project, I tried to develop a new DL architecture. The designed Neural Network has compared with the famous structure like VGG16, Resnet,... and had a better results.

Data Augmentation:

to make data able to use the two dimensional convolutional network, the shape of the data has been reformed. In this way, first all of the seconds related to the same subject and same Video ID, resulting in the same label has been founded. Then, chosen every 50 time-point with their features has been chosen as an input. The step size to have the next data is one. By doing so, the form of the dataset changed to (7811,50,14). 
![augmented (2)](https://user-images.githubusercontent.com/80203915/196021071-76a04ddf-c28e-4e37-8598-fb967bf3edcc.jpg)

[Report.docx](https://github.com/mahdieghane/DL_Project/files/9793663/Report.docx)
