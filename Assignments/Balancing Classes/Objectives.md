# Learning Objective Being Covered: 
This assignment covers the effects of how having different mixture ratios of the different classes for classification can adversely affect your learning algorithm
It then covers SMOTE and how it can generate synthetic samples of your minority class.

# How this Assignment Achieves this Objective: 
First, we begin by generating a simple dataset where the two classes are somewhat seperable (but still overlapping a bit) and have a 
very skewed distribution for one class (1:100 ratio of samples in the training set). We then show that with a logictic regressor, the algorithm
will now do very well on the test set (which has a more reasonable ratio) because the training algorithm saw an overwhelming amount of samples
in the majority class, so it decided to be generous with its boundary. 

Then, students will be expected to implement the SMOTE algorithm from scratch using sklearn's nearest neighbors function.
Students should have seen how the algorithm is designed from the notes and the slides and should have all the tools necessary to accomplish
this task. Once they have done this, they will see that using these synthetic examples, the logistic regressor will be able to 
differentiate between the two classes more effectively (and see that the training error will be a bit higher, but that is okay because the
test error is much better that before)

Then, students will be asked to reason and think about when we should and should not apply SMOTE and class uniformization in general.
The basics to understand these concepts are also in the notes, but students should critically think about datasets where using the convex
hull of two data points might not work as well as for data points that have high corrolation between its features like images.
