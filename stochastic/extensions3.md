# Extension activities: Limiting stationary distribution of a Markov chain

The exercises in this notebook have been concerned with Markov chains that only contain recurrent states. The obvious thing to do 
to take these ideas further is to devise a Markov chain with all recurrent states of your own design and then investigate it. 
You can do any one of the following analyses on your Markov chain:

* You can calculate the $n$ step transition probability matrix by sampling and compare it with the result you obtain using the Chapmann Kolmogorov relation.
* You can calculate the limiting stationary distribution by sampling and you can compare it with the top eigenvector of the transition matrix.

Remember that any time that you estimate a quantity by sampling it multiple times you must also include the error on your estimate to make your result reproducible. If you are estimating the  $n$-step transition probability matrix the error can be obtained in the usual way. If you are estimating the limiting stationary distribution this error must be obtained using the block averaging technique.

If you want to challenge yourself and investigate this subject further, you can investigate a Markov chain that has a stationary distribution that is not limiting. If you want to understand what this means you can watch [this video](https://www.youtube.com/watch?v=1v-GEdV8zys). 
Alternatively, the transition matrix that is described by the following problem statement has this property:

_Suppose that you have two cups a pink one and a blue one and that you also have six
numbered balls. Suppose that three of these balls are in the blue cup and that the remaining
three balls are in the pink cup. You next roll a roll a fair dice to generate a random number
X that is between 1 and 6. Having rolled an $X$ you then take the $X$th ball and if it is in
the blue cup you move it to the pink cup. If by contrast the $X$th ball is in the pink cup you
move it to the blue cup._

Notice, that this, Ehrenfest Urn, problem also works if you you have $n$ balls in the two cups. You just 
need to replace the dice that generated $X$ with a uniform discrete random variable that generates an integer $1\le X <\le n$.  
You then move the $X$th ball.

Lastly, you can also investigate the other eigenvectors of the transition matrix. In doing so you might encounter the spectral theory of Markov chains.   
