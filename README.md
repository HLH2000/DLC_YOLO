# DLC_YOLO
Transform the labeled data from DeepLabCut (DLC), which is in CSV format, into the YOLOv5 PyTorch TXT data format.

In your new DeepLabCut (DLC) project file, once you have labeled your data, you will generate a .csv file named "collected.csv." As you proceed with the refinement process and choose to merge data, you can also generate another .csv file named "machinelabels.csv." 

Both of these files, along with the corresponding images, have the potential to serve as valuable resources for training data in various visual tracking models, such as those within the YOLO family.



This code was created by a novice Python programmer. 

Only the YOLO format has been implemented, and work on the COCO format might not have been started.

HLH 08/19/2023
