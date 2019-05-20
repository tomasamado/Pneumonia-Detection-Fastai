# Pneumonia-Detection-Fastai
Implementation of convolutional neural networks for pneumonia detection in chest radiographs. Three networks were implemented. The first one for classification. The second one for detecting bounding boxes that indicated the presence of lung opacities. The third one for both tasks.

Training data was obtained from the RSNA Pneumonia Detection Challenge in Kaggle (26684 Images + 2 csv files contaning info on each image.) https://www.kaggle.com/c/rsna-pneumonia-detection-challenge.

Resnet34 was used as backbone for the neural networks.

Results were: 83.67% classification accuracy(First Network). An IoU score of 0.504 while predicting on pneumonia-positive radiographs (Second Network). 83.66% classification and IoU score of 0,386 on pneumonia-poistive radiographs(Third Network).
