# [Pneumonia detection](https://github.com/dipam7/fastai/blob/master/deep_learning/course1/lesson1/pneumonia_detection.ipynb)

In this project, we use a pretrained model on a bunch of X-rays and try to predict whether the patient has Pneumonia or not.

[Learn more about how pretrained models work.](https://becominghuman.ai/how-do-pretrained-models-work-11fe2f64eaa2)

![Sample image](https://github.com/dipam7/fastai/blob/master/deep_learning/course1/lesson1/images/image_4.png)

**Future scope**: Use stanford's CheXpert dataset and predict multiple diseases from the dataset

# [Mixed precision training](https://github.com/dipam7/fastai/blob/master/deep_learning/course1/lesson1/mixed-precision-on-pneumonia-using-fastai.ipynb)

In neural nets, all the floats i.e. our inputs, weights and activations are stored using 32 bits. Using 32 bits gives us a high amount of precision. But higher precision also means more computation time and more memory required to store these variables. We can also do these computations in half (FP16) or mixed precision (both). Read the detailed explanation in [my article here](https://becominghuman.ai/mixed-precision-training-using-fastai-435145d3178b).

Results show that we've reduced the training time without much decrease in accuracy

![Sample image](https://github.com/dipam7/fastai/blob/master/deep_learning/course1/lesson1/images/image_1.png)


![Sample image](https://github.com/dipam7/fastai/blob/master/deep_learning/course1/lesson1/images/image_2.png)
