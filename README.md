# Activated-Gradients-for-Deep-Neural-Networks
This is an offitial implementation of the paper "Activated Gradients for Deep Neural Networks". 

Run your code. 

## Useage in MindSpore

LeNet uses SGDM with embedded GAF for training on MNIST dataset

Before running the code, you need to download the MNIST dataset in advance.

\MindSpore\datasets\MNIST_Data\train: train-images.idx3-ubyte; train-labels.idx1-ubyte

\MindSpore\datasets\MNIST_Data\test: t10k-images.idx3-ubyte; t10k-labels.idx1-ubyte

```python
python run  LeNet_SGDM_GAF.py
```

Based on MindSpore, you can easily replace models, optimizers, and implement other functions instead of GAF.

