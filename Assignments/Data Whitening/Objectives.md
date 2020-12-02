# Learning Objective Being Covered: 
This assignment teaches students about data decorrolation and whitening. Students will be able to see how decorrolation and whitening are based around SVD/PCA
and use them to whitten data to get standard normal data. They should also be able to reason on the difference between PCA and ZCA and why we should use them.
Students will also be exposed to whitening images and they can see how whitening images changes the features and how it makes edges and boundaries easier to see.

# How this Assignment Achieves this Objective: 
First, we go through the rote code and visualizations that we used in the slides and notes to see how decorrolation, PCA whitening and ZCA whitening work. 
Students should take the annotated data and use the U matrix along with the singular vlaues to accomplish all of the whitening graphs. They should be able
to cross reference with the notes to see if they are doing it correctly. In addition, they will be asked questions about how the SVD matrices make the
whitening algorithms work as expected. They should see the connection between the column space of the matrix and decorrolating the matrices. These are
also elaborated on in the notes, so students should be fine. From there, they answer questions on when we should whiten data and when we should use PCA over
ZCA and etc. These reasons should be clear if they read the standarization/ normalization notes and they should be able to extrapolate from the notes to here.

Then they will use cifar10 data to look at what happens when you whiten images. The important things for them to see is that after whitening, the data looks like
white noise except for specific features that exagerate the boundaries and the different shapes. They will be expected to write the ZCA transform on the images
and to properly normlize the images for visualization. 
