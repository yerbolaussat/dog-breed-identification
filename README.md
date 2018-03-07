# Dog Breed Identification from an Image Using CNN, Transfer Learning and Data Augmentation


In this project we attempted to build a classifier capable of identifying a dog’s
breed based on its photo. Considering that on a high level dogs of different breeds
can look very similar, it is a challenging task even for humans. To train and eval-
uate the model the ”Columbia Dogs with Parts” dataset, containing 8,351 real-
world images of 133 dog breeds, was used. The number of photos per breed
ranged from 33 to 96. To tackle this problem, transfer learning, data augmenta-
tion and ensemble learning techniques were employed. As a result, the ensemble
meta model averaging predictions of five transfer learning models that was trained
on an augmented training dataset achieved a testing accuracy rate of 88.40%. In
addition, a small CNN that was trained from scratch on an augmented training
dataset achieved a testing accuracy rate of 54.42%.
