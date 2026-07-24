# Extension activities: Relaxing the Markov assumption

Much like in the last set of exercises the suggested extensions here involve using these ideas for event driven simulations.
If you have managed to implement the M/G/1, M/D/1 or G/G/1 queue then you have already studied a system where the Markov assumption 
is relaxed. These are examples of so called Semi-Markov chains.

Notice that there is also a massive body of theory on so called Hidden Markov chains where each state returns a random signal when it 
is visited.  It would be relatively easy to write an event driven simulation model for studying a hidden Markov chain. You should even 
know enough to implement a hidden, Semi-Markov chain.

All of these complicated models can be analysed by computing histograms, averages, error bars and so on using the tools that by now should
be extremely familiar. You may also find theory for deriving analytic results for these various types of system online. Don't be put off if 
that theory is hard. Writing and analysing a numerical model of an event driven simulation will be easier than deriving analtic results for 
its properties. Furthermore, the folks who do research to develop those analytic frameworks likely start off with the easy business of 
writing a numerical model. Ideas for how to proceed with deriving results analytically often emerge __after__ results
from numerical simulations have beeen analysed.
