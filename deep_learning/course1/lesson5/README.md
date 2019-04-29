# [Multiclass classification and weight decay](https://github.com/dipam7/fastai/tree/master/deep_learning/course1/lesson5)

On the data side of things, we use data augmentation to help models generalize better. On the model side of things, we use **weight decay**. Learn more about it in my article [here](https://medium.com/@dipam44/this-thing-called-weight-decay-a7cd4bcfccab).
In this notebook we demonstrate training a model with 3 different weight decays and their results are as expected.

![Sample image](https://github.com/dipam7/fastai/blob/master/deep_learning/course1/lesson5/images/image_1.png)

1. Default wd = 0.01: Takes time to train but doesn't overfit (see diff b/w train & val loss) (12 epochs)

![Sample image](https://github.com/dipam7/fastai/blob/master/deep_learning/course1/lesson5/images/image_2.png)

2. Best wd = 0.1: Fits well (10 epochs)

![Sample image](https://github.com/dipam7/fastai/blob/master/deep_learning/course1/lesson5/images/image_3.png)

3. Too much weight decay, wd = 10: model never fits well (10 epochs)

![Sample image](https://github.com/dipam7/fastai/blob/master/deep_learning/course1/lesson5/images/image_4.png)
