![diffractive-deep-neural-network](Images/diffractive-deep-neural-network.png)



In this exercise, we will implement one-vs-all logistic regression and Neural Networks to recognize hand-written digits. That assignment is from **Andrew NGs** Machine Learning Class. However, i have implemented it in Python.


## Data Set
We are given a data set in ex3data1.mat that contains 5000 training exam- ples of handwritten digits.2 The .mat format means that that the data has been saved in a native Octave/MATLAB matrix format, instead of a text (ASCII) format like a csv-file.


There are 5000 training examples in ex3data1.mat, where each training example is a 20 pixel by 20 pixel grayscale image of the digit. Each pixel is represented by a floating point number indicating the grayscale intensity at that location. The 20 by 20 grid of pixels is “unrolled” into a 400-dimensional vector. Each of these training examples becomes a single row in our data matrix X. This gives us a 5000 by 400 matrix X where every row is a training example for a handwritten digit image.

![sigmoid](Images/sigmoid.png)


The second part of the training set is a 5000-dimensional vector y that contains labels for the training set. To make things more compatible with Octave/MATLAB indexing, where there is no zero index, we have mapped the digit zero to the value ten. Therefore, a “0” digit is labeled as “10”, while the digits “1” to “9” are labeled as “1” to “9” in their natural order.


 

 
