# Face recognition using Singular value decomposition
Dataset used was of yalefaces. All the faces are stacked in matrix and normalization is done. SVD is calculated of that matrix and U matrix obtained is multiplied with faces(f x U). This is done for training dataset. For test image(t) U matrix is obtained from SVD and multiplied with test image i.e t x U. Now distance or norm is calculated from test image to train images. The image with which least norm is obtained is the correct image.

Code was built in python in spyder3.6. Here test image taken was one image from dataset.
