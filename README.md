# Object Detection and Localization

The data was taken from the following link. ->   https://public.roboflow.com/object-detection/thermal-cheetah/1

Using thermal cheetah data, a new model was built on top of ResNet50 by adding a few DNN layers. The model predicts a label and bbox parameters for a new testing picture and draws the label and the object's box localized on top of the image. You can see the detailed description in the code file directly. 

In the repository, you can find attached the code for building the model `ThermalCheetahObject_Detection.ipynb` and the model itself, `resnet_model.h5`, which you can download by the following link. Since the file size was not small enough to upload here, I uploaded it to my drive instead. Please take a look at the model here. -> https://drive.google.com/file/d/1tIBTX5N44sSGg_1QzITbmi3QpvqynsYd/view?usp=sharing
