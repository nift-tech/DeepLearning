# What is Supervised Learning?

In machine learning and artificial intelligence, supervised learning refers to a class of systems and algorithms that determine a predictive model using data points with known outcomes.  The model is learned by training through an appropriate learning algorithm (such as linear regression, random forests, or neural networks) that typically works through some optimization routine to minimize a loss or error function.

Put another way, supervised learning is the process of teaching a model by feeding it input data as well as correct output data. This input/output pair is usually referred to as "labeled data." Think of a teacher who, knowing the correct answer, will either reward marks to or take marks from a student based on the correctness of her response to a question. Supervised learning is often used to create machine learning models for two types of problems.

* Regression - The model finds outputs that are real variables (number which can have decimals.) 
* Classification - The model finds classes in which to place its inputs.


### Training, Test, and Validation

The first step in the supervised learning process is to gather labeled training data. The label is the output and provides feedback for the algorithm. Provided enough data is available, the next step is to split this labeled data into three sets: training, testing, and validation. The algorithm uses training set to adjust the model to minimize the error.   For example the training set may contain a variety of animal pictures with a label associated to each picture, allowing the algorithm to compare the predicted label with the correct one.

The validation set is disjoint from the training set and allows one to independently measure the progress of the learning algorithm. This measure can be used to determine a cutoff point in the training algorithm to balance the accuracy of the learned model versus overfitting.

The test set is the final set and it is meant to be used only when the model has been found to be optimal on the validation set. This set provides a ‘real world’ evaluation of the model’s performance on never-before-seen data. Test data is a kind of ‘final exam’ for a model which has learned its training data effectively and can generalize to new data.

# Supervised Learning vs Unsupervised Learning

If supervised learning may be compared to a teacher-student relationship, unsupervised learning can be thought of as how a child might learn language by independently finding structure from the given input.   No labels are supplied during training for unsupervised learning, and hence different learning algorithms are required.  




------------------------------(https://deepai.org/machine-learning-glossary-and-terms/supervised-learning)
