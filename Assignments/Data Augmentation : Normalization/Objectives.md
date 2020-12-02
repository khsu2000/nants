# Learning Objectives

This notebook primarily focuses on allowing the students to gain experience augmenting image datasets. In addition, there is some light normalization work as this is a common task to be done in industry or research.

# Details

This notebook runs the student through the process of augmenting the CIFAR10 dataset in the context of training VGG11 for an image classification task. The bulk of machine learning labor, including defining the model, running the training pipeline, and downloading the dataset are done and implemented as helper functions; students just need to have a high level understanding of those workings and can treat those helper functions as black boxes. Students will need to use the PyTorch transforms API to apply augmentation techniques to CIFAR10. Then, they will do a light normalization task and find the channelwise RGB mean and stddev of the dataset as inputs for normalization. Then, they will run the provided training pipeline on the their augmented dataset and compare the performance with the raw dataset, and do some light plotting and visualization work to compare the training and validation losses side by side. Finally, as an optional extra task, students can tinker with the training pipeline itself to achieve even better performance (e.g. hyperparameter tuning, learning rate scheduler, etc.). This assignment in addition to exercises these specific skills should be a good starting point for some hands on industry machine learning frameworks experience.

# Requirements

Students are highly recommended to run the notebook on Google Colab, as the second half of the notebook involves training VGG11 on CIFAR10. This takes 30 seconds per epoch on GPU and 20 minutes per epoch on CPU, so this is rather important for completing the assignment in a timely fashion.
