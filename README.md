## Statistics 101     December 2018

I appreciate comments. Shoot me an email at noel_s_cruz@yahoo.com!

Hire me!

Describing any data set may simply be the data itself:

   num_friends = [10, 49, 4, 40, 25,
                   # ... and many more 
                 ]
                 
For a small enough data set this might even be the best description. But for 
a larger data set, this is unwieldy(Imagine staring at a list of 1 million
numbers.). For that reason we use statistics to distill and communicate
relevant features of our data.

Central Tendencies

Usually, we'll want some notion of where our data is centered. Most commonly 
we'll use the mean(or average), which is just the sum of the data divided by
its count. As you add more points, the mean shifts around, but it always
depends on the value of every point.

We'll also sometimes be interested in the median, which is the middle-most
value(if the number of data points is odd) or the average of the two 
middle-most values(if the number of data points is even). Notice that unlike 
the mean, the median doesn't depend on every value in our data. For example,
if you make the largest point larger(or the smallest point smaller), the 
middle points remain unchanged which means so does the median.
Clearly, the mean is simpler to compute, and it varies smoothly as our data
changes. Whereas if we have to find the median, we have to sort the data. At
the same time, the mean is very sensitive to outliers in our data.

A generalization of the median is the quantile, which represents the value less 
than which a certain percentile of the data lies.

Less commonly you might want to look at the mode, or most common value[s].

But frequently we'll just use the mean.

Dispersion

Dispersion refers to measures of how spread out our data is. Typically they're
statistics for which values near zero signify not spread out at all and for 
which large values(whatever that means) signify very spread out. For instance,
a very simple measure is the range, which is just the difference between the 
largest and the smallest elements. A more complex measure of dispersion is the
variance. Variance is the square of the original units so it is more common
sense to look at the standard deviation is is the square root of variance.

Correlation

We'd like to investigate the relationship between two metrics and that is 
correlation. We'll look first at covariance, the paired analogue of variance.
Whereas variance measures how a single variable deviates from the mean, 
covariance measures how two variables vary in tandem from their means. A "large"
positive covariance means that x tends to be large when y is large and small
when y is small. A "large" negative covariance means the opposite. A covariance
close to zero means that no such relationship exists. This number can be hard to
interpret so we look at correlation.

Correlation divides out the standard deviations of both variables. The
correlation is unitless and always lies between -1(perfect anti-correlation)
and 1(perfect correlation). A number like 0.25 represents a relatively weak
positive correlation.

Correlation can be sensitive to outliers. Without the outlier, there is much
stronger correlation = 0.57.

### Pattern Recognition

december 30, 2018

##############
Far better results can be obtained by adopting a machine learning approach in
which a large set of N digits {x1, . . . , xN} called a training set is used to tune the
parameters of an adaptive model. The categories of the digits in the training set
are known in advance, typically by inspecting them individually and hand-labelling
them. We can express the category of a digit using target vector t, which represents
the identity of the corresponding digit. Suitable techniques for representing categories
in terms of vectors will be discussed later. Note that there is one such target
vector t for each digit image x.
The result of running the machine learning algorithm can be expressed as a
function y(x) which takes a new digit image x as input and that generates an output
vector y, encoded in the same way as the target vectors. The precise form of the
function y(x) is determined during the training phase, also known as the learning
phase, on the basis of the training data. Once the model is trained it can then determine
the identity of new digit images, which are said to comprise a test set. The
ability to categorize correctly new examples that differ from those used for training
is known as generalization. In practical applications, the variability of the input
vectors will be such that the training data can comprise only a tiny fraction of all
possible input vectors, and so generalization is a central goal in pattern recognition.

For most practical applications, the original input variables are typically preprocessed
to transform them into some new space of variables where, it is hoped, the
pattern recognition problem will be easier to solve. For instance, in the digit recognition
problem, the images of the digits are typically translated and scaled so that each
digit is contained within a box of a fixed size. This greatly reduces the variability
within each digit class, because the location and scale of all the digits are now the
same, which makes it much easier for a subsequent pattern recognition algorithm
to distinguish between the different classes. This pre-processing stage is sometimes
also called feature extraction. Note that new test data must be pre-processed using
the same steps as the training data.

Applications in which the training data comprises examples of the input vectors
along with their corresponding target vectors are known as supervised learning problems.
Cases such as the digit recognition example, in which the aim is to assign each
input vector to one of a finite number of discrete categories, are called classification
problems. If the desired output consists of one or more continuous variables, then
the task is called regression. An example of a regression problem would be the prediction
of the yield in a chemical manufacturing process in which the inputs consist
of the concentrations of reactants, the temperature, and the pressure.
In other pattern recognition problems, the training data consists of a set of input
vectors x without any corresponding target values. The goal in such unsupervised
learning problems may be to discover groups of similar examples within the data,
where it is called clustering, or to determine the distribution of data within the input
space, known as density estimation, or to project the data from a high-dimensional
space down to two or three dimensions for the purpose of visualization.

I included some posts for reference.

https://github.com/noey2020/How-to-Write-Multitasking-STM32

https://github.com/noey2020/How-to-Generate-Triangular-Wave-STM32-DAC

https://github.com/noey2020/How-to-Generate-Sine-Table-LUT

https://github.com/noey2020/How-to-Illustrate-Multiple-Exceptions-

https://github.com/noey2020/How-to-Blink-LED-using-Standard-Peripheral-Library

I appreciate comments. Shoot me an email at noel_s_cruz@yahoo.com!

Hire me!

Have fun and happy coding!



