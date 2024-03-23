# EE992

base model is VGG16 for comparison

Tested
VGG16
1. Batch size = 128, only unfrozen, eta = 0.001
2. Batch size = 128, frozen and unfrozen, eta1 = 0.001, eta2 = 1e-5
3. Batch size = 256, frozen and unfrozen, eta1 = 0.001, eta2 = 1e-5
4. Batch size = 256, frozen and unfrozen, eta1 = 0.01, eta2 = 1e-4
Losses and accuracies in excel file

Untested (ordered in priority)
1. Any other model eg. DenseNet121, Xception, ResNet101, ResNet152
2. Different loss function
3. Image augmentation
4. Fully connected layer neurons/depth
5. Encoding - notcovered in class - still want to go ahead?
