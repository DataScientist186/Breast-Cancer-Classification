# Breast-Cancer-Classification

Prerequisites:

You’ll need to install some python packages to be able to run this advanced python project. 
You can do this with pip-

pip install numpy opencv-python pillow tensorflow keras imutils scikit-learn matplotlib

The Dataset:

We’ll use the IDC_regular dataset (the breast cancer histology image dataset) from Kaggle. This dataset holds 2,77,524 patches of size 50×50 extracted from 162 whole mount slide images of breast cancer specimens scanned at 40x. Of these, 1,98,738 test negative and 78,786 test positive with IDC. The dataset is available in public domain and you can download it here (https://www.kaggle.com/paultimothymooney/breast-histopathology-images/). You’ll need a minimum of 3.02GB of disk space for this.

Filenames in this dataset look like this:
8863_idx5_x451_y1451_class0
Here, 8863_idx5 is the patient ID, 451 and 1451 are the x- and y- coordinates of the crop, and 0 is the class label (0 denotes absence of IDC)

