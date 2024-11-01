# J1-implementation
This is a code snippet of journal 1. 
Dataset is too big to upload. It can be provided upon request
We primarily propose a novel sampling technique to balance the dataset, named as random oversampling using both classes (ROBC). This technique performs oversampling using both the theft and normal classes.

With this technique, the problem of low accuracy has been resolved. We also propose a unique ETD model using densenet-fully convolutional network (DenseNet-FCN) and gated recurrent unit (GRU) with a light gradient boosting machine (LightGBM), known as DenseNet-GRU-LightGBM, to address the above mentioned concerns. 
DenseNet-FCN module extracts periodic and non-periodic patterns from 2-D electricity consumption data in a precise way. Whereas, GRU module captures as well as memorizes features from 1-D consumption data. 
Afterwards, LightGBM module is used as an ensemble classifier to give final ETD results. 
As a result, the proposed model has excellent ETD results. Comprehensive simulations indicate that the proposed scheme outperforms other existing methods regarding ETD.
