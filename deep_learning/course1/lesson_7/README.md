# [ResNet using PyTorch and fastai](https://github.com/dipam7/fastai/blob/master/deep_learning/course1/lesson_7/resnet-mnist.ipynb)

In this notebook we first define our own [convolutional neural network](https://heartbeat.fritz.ai/heatmaps-and-convolutional-neural-networks-using-fast-ai-16d5b7d02a86) using PyTorch. We want to make it denser but just adding stride 1 convolutions doesn't make it better as shown.

![Sample Image](https://github.com/dipam7/fastai/blob/master/deep_learning/course1/lesson_7/images/image_1.png)

Hence we make use of resblocks, where for every 2 convolutions we add the input as well. `Output = x + conv2(conv1(x))`

![Sample Image](https://github.com/dipam7/fastai/blob/master/deep_learning/course1/lesson_7/images/image_2.png)
