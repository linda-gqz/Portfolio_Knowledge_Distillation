# Knowledge Distillation for Efficiency


## Abstract
As deep learning has been widely used and become increasingly important to our daily life, the efficiency of deploying a complex neural network on a small device stands out as one of the main concerns for developers and researchers. In reality, a problem arises when we train a network with high capacity source but fail to compress it to smaller devices, such as phones and tablets, due its cumbersome structure. In such situations, we want to distill knowledge to keep most of the network’s performance but train a much simpler network instead. One way to do this is to transfer knowledge learned by the cumbersome network, called a teacher network, to a simple network, called a student network. In order for the student network to carry the knowledge from the teacher network, mainly the uncertainty of the classification, instead of predicting the real classes, called hard labels, we train a student network to predict a weighted result of the hard labels and the softened probability by temperature of each class, called soft labels. The loss function is therefore a combination of the loss for the hard labels and the soft labels. A more practical situation occurs when the training data of the teacher network is not accessible due to privacy concern or company rivalry. In this case, we perform zero-shot knowledge distillation, in which we train the student network by data impressions, generated by the distribution of the softmax outputs from the teacher network and the class similarity matrix. In this project, I will explore knowledge distillation by explaining the algorithm with and without teacher network's training set and evaluating it by implementing them on three datasets to compare the performance.

##### Keywords: teacher network, student network, temperature, data impression, class similarity matrix
