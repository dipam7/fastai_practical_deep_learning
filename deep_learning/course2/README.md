# Fastai_foundations

This repository contains notebooks which build the fastai library. Explanations can be found on [my blog](https://medium.com/@dipam44).

### Quick links
1. Matrix multiplication [[notebook]](https://github.com/dipam7/fastai_practical_deep_learning/blob/master/deep_learning/course2/notebooks/01_matmul.ipynb)[[article]](https://medium.com/@dipam44/matrix-multiplication-the-pytorch-way-c0ad724402ed)

In this notebook, we start by implementing matrix multiplication in a naive way which is super slow. We then try and improve it iteratively to achieve PyTorch like speed.

2. Initializing neural networks [[notebook]](https://github.com/dipam7/fastai_practical_deep_learning/blob/master/deep_learning/course2/notebooks/02_fully_connected.ipynb) [[article]](https://becominghuman.ai/initializing-neural-networks-3a774eb63745)

In this notebook, we learn how different initializations affect how deep our neural network can go without the gradients exploding.

3. The PyTorch training loop [[notebook]](https://github.com/dipam7/fastai_practical_deep_learning/blob/master/deep_learning/course2/notebooks/03_minibatch_training.ipynb) [[article]](https://becominghuman.ai/the-pytorch-training-loop-3c645c56665a)

In this notebook, we write our own classes for things like DataSets, DataLoaders and Optimzers to recreate the PyTorch training loop from scratch.

4. Customize your training loop using callbacks [[notebook1]](https://github.com/dipam7/fastai_practical_deep_learning/blob/master/deep_learning/course2/notebooks/04_callbacks.ipynb) [[notebook2]](https://github.com/dipam7/fastai_practical_deep_learning/blob/master/deep_learning/course2/notebooks/05a_foundations.ipynb) [[article]](https://medium.com/@dipam44/customize-your-training-loop-with-callbacks-9d93b415a602)

When we train deep learning models, we would want to do many different things. Discriminative learning rates, one cycle train policy, data augmentations and so on. To do these things, we don't want to write a different loop every time. We want to write the same basic loop and include these functionalities in that. This is where callbacks come into the picture. Using callbacks we can perform various tasks at various stages of training without having to change our training loop.

5. Convolutional neural networks and hooks [[notebook]](https://github.com/dipam7/fastai_practical_deep_learning/blob/master/deep_learning/course2/notebooks/06_cuda_cnn_hooks_init.ipynb) - In this notebook we use nn.Sequential to build a basic convolutional neural network. We then learn how to use PyTorch's hooks to access data during training. This can be used to figure out how the mean and standard deviation of the output of every layer varies with respect to number of epochs. Check the notebook for more information.
