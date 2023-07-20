# Image-Classification-with-Transfer-Learning
A [Kaggle competition](https://www.kaggle.com/competitions/dogs-vs-cats-redux-kernels-edition/overview) to distinguish images of dogs from cats

## Overview
I have tried two different aproaches:

- manually build a CNN and
- use transfer learning based on different existing model.

For transfer learning, I have tried:
- Xception,
- VGG16,
- EfficientNetB3 and
- EfficientNetB7.

For each model, I will first freeze the original parameters in the first train, and then train all the parameters together in the second train, so as to tune the existing model fit this problem better.

After comparing the performance, the best submission is Xception.
