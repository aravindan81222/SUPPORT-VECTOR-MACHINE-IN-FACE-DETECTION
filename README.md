# SUPPORT-VECTOR-MACHINE-IN-FACE-DETECTION

Support vector machine(SVM) is a supervised machine learning algorithm used for classification and regression tasks. Most commonly used in classification objectives. It uses the technique known as ‘The kernel Trick’ to transform the data and finds an optimal boundary between the possible outputs.

The objective is to find a hyperplane in an N-dimensional space(N is no of features/attributes) that distinctively classifies the data points.
They can be linear separable and non-linear separable too.
To separate the data points, many possible hyperplanes can be chosen but the most effective is the one with maximum margin.
Maximizing the margin provides some reinforcement so that future data points can be classified with more confidence.

Hyperplanes are nothing but decision boundaries that help classify the data points.
Data points falling on either side of the hyperplane can be attributed to different classes.
As already said, the dimension depends upon the number of features/attributes we have for any given data.
Support vectors are data points that are closer to the hyperplane and influence the position and orientation of the hyperplane.

Advantages:
Most effective in high dimensional spaces, because we can use any other algorithm when it comes to 2D and 3D.
Effective in cases where number of dimensions is greater than number of samples.
Versatile, different kernel functions can be specified for the decision function. Common kernels are provided, also possible to specify custom ones.

Disadvantages:
If number of features is much greater than number of samples, avoid over-fitting in choosing kernel functions.
Long training time for large datasets.
Choosing a good kernel function is not easy.


