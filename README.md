# Object Detection and Localization

The data was taken from the following link.  https://public.roboflow.com/object-detection/thermal-cheetah/1

Using thermal cheetah data, a new model was built on top of ResNet50 by adding few DNN layers. The model predicts a label and bbox parameters for a new testing picture and draws the label and the box of the object localized on top of the image. You can see step by step description in the code file directly. 

In repository you can find attached the code of building the model `ThermalCheetahObject_Detection.ipynb` and the model itself, `resnet_model.h5`. 
