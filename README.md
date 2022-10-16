# Identifying Focus from EEG signals
In this project, I tried to develop a new DL architecture for extracting focus index from EEG signals. The designed Neural Network has compared with the famous structure like VGG16, Resnet,... and had a better results.

**Data Augmentation**:

to make data able to use the two dimensional convolutional network, the shape of the data has been reformed. In this way, first all of the seconds related to the same subject and same Video ID, resulting in the same label has been founded. Then, chosen every 50 time-point with their features has been chosen as an input. The step size to have the next data is one. By doing so, the form of the dataset changed to (7811,50,14). 

<p align="center">
  <img src="https://user-images.githubusercontent.com/80203915/196021071-76a04ddf-c28e-4e37-8598-fb967bf3edcc.jpg" width="600" title="Deta Augmentation">
</p>


**Trining**
 The designed network has been shown in the following network. This network has been inspired from the EEGNet which is well-known for the the analysing EEG signals. The obtianed results from this network has compared with the famous networks for image and signal processing like VGG16, Inception, Resnet. Results show that the designed architecture is able to extract focus index from EEG signals more accurately. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/80203915/196021262-0709f2ef-262d-4cdb-88aa-0609bcce1ea8.jpg" width="500" title="Desgined Network">
</p>

[Report.docx](https://github.com/mahdieghane/DL_Project/files/9793663/Report.docx)
