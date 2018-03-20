

Resampling
========================================================
author: Wim van der Ham
date: 2018-03-19
autosize: true

Resampling
========================================================

> Evaluate the model performance on a different set than the set used to train the model. This way the performance of the model with new data can be assest.

1. Cross-Validation
1. Bootstrap

The Validation Set Approach
========================================================

> Randomly dividing the available set of observations into two parts, a training set and a validation set. The model is fit on the training set, and the fitted model is used on the validation set.

The Validation Set Approach
========================================================

![Validation Set](./validation_set.jpg)

The Validation Set Approach
========================================================

Downsides:

1. **Highly variable** score depends a lot on which points ar in the test or in the validation group
2. **Overestimates the test error** because only half of the data is used for training