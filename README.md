# Two-Stage-live-Identifier-for-beer-
This is the repository for my computer vision project. The project encompasses 2 CNNs working together to identify beer bottles  

There are 5 files that are uploaded. Two of the files are trained neural networks. These are the 25x2x0.keras and best.pt The other 3 files are jupyter notebooks containing code to create your own networks as well as data manipulation for training, validation adn testing datasets. 

The .keras CNN is a classification CNN which can classify between plastic and beer bottles. 

The .pt is a yolo object detector CNN for identifying bottles. 

The jupyter notebook datamanipulation is for manipulating data for the classification CNN 

The notebook nexcnn is for creating, training and testing the classification CNN 

The notebook detection contains the code to create the yolov8 detection cnn whilst also containing a large amount of data manipulation code for converting bounding box annotating text files from pen images format to yolov8 format.

