# thesis
Comparison of neural network models for object detection in an image

Models :
- SSD MobileNet V2
- Faster R-CNN ResNet
- RetinaNet ResNet
- CenterNet Hourglass

The meta architecures (SSD, Faster R-CNN, RetinaNet, CenterNet) were improved by the feature extractors like MobileNet, ResNet and Hourglass.

The models were downloaded from the TensorFlow Hub website which were trained on the Microsoft COCO dataset.
According to the assumptions of the project, models were tested and compared using datasets on which none of the models had been trained( Google's Open Images V4).It was necessary to have the same name of classes so the mapping was used.For each model, the program returned the confusion matrix for each
selected classes and resolution of images. The tests involved approximately 100 photos per class.It was 90 classes.Based on the confusion matrix it was possible to get important measures and parameters and compare the models