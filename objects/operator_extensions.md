# Extension Projects: Objects and operators

In example project I used the techniques that I showed you in the Colab exercises to study the distribution of angles and distances between pairs of 1D and 2D random vectors. 
To generate the random vectors in these projects I generated uniform (continuous) random variables and normal random variables.  There are two obvious ways for you to build on this 
work

* You can study random vectors that are composed of different types of random variable (e.g. exponential, Erlang, t-distribution etc)
* You can study random vectors in a 3 (or higher) dimensional space.  Notice, however, that studying the area of the triangles in these higher dimensional spaces is no longer simply a case of taking a determinant of a matrix.  You have to find the common plane in which all your random vectors lie.

As I explained in the Colab notebooks, I was able to find information on the analytic distributions of the random variables that I studied online. 
If you have computed a histogram from a sample of exotic random variables that you have generated in some way it is worth looking online to see if 
someone has derived an analytic expression for the probability density that you have estimated by sampling. You can then compare your distribution 
with the analytic one.  If they match then you can have some confidence that you have done the sampling correctly.
