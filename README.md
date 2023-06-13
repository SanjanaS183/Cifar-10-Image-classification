# Cifar-10-Image-classification

The CIFAR-10 dataset is downloaded and extracted using a URL into the ./data directory. It performs normalization and data augmentation transformations on the training and validation datasets to center the input data around zero, increase dataset diversity, and make the model more robust. PyTorch data loaders are then used to load the data in batches during the training of a machine learning model. Helper functions and a wrapper class are developed to use GPU.
