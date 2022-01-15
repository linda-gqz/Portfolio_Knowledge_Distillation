# Knowledge Distillation for Efficiency


## Abstract
In reality, a practical problem arises when we train a model with high capacity source but fail to compress it to smaller devices due the cum- bersome structure. In such situations, we want to distill knowledge to keep most of the model’s performance by training a smaller model. In other words, we transfer knowledge from a teacher network to a student network. One way to do this is that, instead of predicting the hard labels (real targets), in the student network, we predict the soft targets, which are the probabilities of the hard labels in the teacher network. In this project, we distill knowledge to learn a classifier in two scenarios: the training data of the teacher network is available and the training data of the teacher network is not available.

##### Keywords: teacher network, student network, hard labels, soft labels, temperature
