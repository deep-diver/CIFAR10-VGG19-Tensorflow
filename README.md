# Transfer Learning on CIFAR-10 using VGG19 in Tensorflow

This repository shows the simple steps for transfer learning. In particular, CIFAR-10 dataset is chosen, and VGG19 model is used to train. The model is pre-trained and borrowed from https://github.com/taehoonlee/tensornets.git. The best accuracy I could get is about 91%.

## Important concepts to know (in general)

While writing the notebook, I have noticed that I should be able to answer the following questions to perform transfer learning. The answers to them in implementation could be slightly different, but the concept is the same. In my choice of the pre-trained model, I will show my own answers.

1. Choose the model (VGG16, VGG19, ResNet, DenseNet, ...)
2. Search for the implementation for the model (Github)
3. Know how to create the model
4. Know how to load the pre-trained weights
5. Know what the model outputs at the last layer
6. Know the shape of the input data 
7. Know how to re-scale the original image(data) to fit into the model

## References

- [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)
- [Tensornets Github Repo](https://github.com/taehoonlee/tensornets.git)
- [Udacity Deep Learning Github Repo](https://github.com/udacity/deep-learning)
- [CIFAR-10 img classification by me](https://github.com/deep-diver/CIFAR10-img-classification-tensorflow)