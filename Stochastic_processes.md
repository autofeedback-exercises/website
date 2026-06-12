# Stochastic Processes

A stochastic processes is a mathematical model that can be used to describe systems or phenomena that evolve over time in a random, probabilitistic model.  In such models you have a collection
(or family) of random variables $\{X_t\}$ indexed by a parameter, $t$, where $t$ often represents time.  Instead of resulting in a single predictable outcome, a stochastic process generates an 
entire set of possible outcomes over time, known as an ensemble, while a single observed sequence of events is called a realization or sample path.

Stochastic processes are a powerful tool for generating models of real world phenomena. The materials below introduce you to this body of theory by first showing you how we can construct a model
to describe how the amount of money a gambler playing a game like roulette changes over the course of multiple games with a random outcome.  We then develop a more general theory of stochastic 
processes by introducing the theory of Markov chain in discrete time. We then show how we can introduce random events that occur at random times by introducing a theory of Markov chains in 
continuous time and demonstrate how this body of theory can be used to model a queue. We finish by demonstrating how to develop models where the assumption of Markovianity is relaxed. 

```mermaid
flowchart TD
   subgraph one
      direction LR
      intro("Random models, parameters and trends") --> gr("Gamblers ruin exercises")
      gr --> rep1("Example report) 
   end
   subgraph two
      direction LR
      vid("Introduction to Markov chains") --> ht("Hitting time exercises")
      ht --> rep2("Example report")
   end
   one --> two
   subgraph three
      direction LR
      back("The PageRank algorithm") --> sd("Staionary distribution exercises")
      sd --> rep3("Example report")
   end
   two --> three
   subgraph four
      direction LR
      vid2("Introduction to Markov chains in continuous time") --> ctm("Continuous time Markov chain exercises")
      ctm --> rep4("Queue report")
      ctm --> rep5("Coffee shop report")
   end
   three --> four
   subgraph five
      direction LR
      vid3("Relaxing the Markovian assumption") --> inhomo("Exercises on simulating inhomogenous Poisson processes")
   end
   click intro "stochastic/intro.html" "A discussion of when we say that a parameter has a statistically significant effect on a random model"
   click gr "https://colab.research.google.com/github/autofeedback-exercises/exercises/blob/main/New-SOR3012/Trends/Trends.ipynb" "Programming exercises that introduce you to a model for gambling in a game like roulette"
   click rep1 "stochastic/report1.pdf" "An example report showing one thing that can be investigated with the Gamblers ruin model that was introduced during the programming exercises"
   click vid "https://www.youtube.com/watch?v=1meaW5GxUbY" "A video introducing the Markov property"
   click ht "https://colab.research.google.com/github/autofeedback-exercises/exercises/blob/main/New-SOR3012/Markov_hitting_times/Markov_hitting_times.ipynb" "Programming exercises that teach you to simulate Markov chains"
   click rep2 "stochastic/report2.pdf" "Example report on calculating hitting times and hitting probabilities for a Markov chain"
   click back "stochastic/pagerank.html" "A discussion of a valuable application of the theory of Markov chains in discrete time"
   click sd "https://colab.research.google.com/github/autofeedback-exercises/exercises/blob/main/New-SOR3012/Markov_stationary_distribution/Markov_stationary_distribution.ipynb" "Programming exercises on calculating the stationary distribution of a Markov chain"
   click rep3 "stochastic/report3.pdf" "Example report on calculating and then reporting the stationary distribution of a Markov chain"
   click vid2 "https://www.youtube.com/watch?v=tbA2DnKTRxM" "A video introducing the theory of Markov chains in continuous time"
   click ctm "https://colab.research.google.com/github/autofeedback-exercises/exercises/blob/main/New-SOR3012/Event_based_simulation/Event_based_simulation.ipynb" "Exercises on Markov chains in continuous times and Queues"
   click rep4 "stochastic/report4.pdf" "An example report showing how we can analyse a simulation of a queue"
   click rep5 "stochastic/report5.pdf" "An example report demonstrating how we can simulate a coffee shop using event driven simulation"
   click vid3 "https://www.youtube.com/watch?v=q2843QDkb1Q" "A video introducing the inhomogeneous Poisson process"
   click inhomo "https://colab.research.google.com/github/autofeedback-exercises/exercises/blob/main/New-SOR3012/Inhomogeneity/Inhomogenity.ipynb" "Exercises on simulating inhomogeneous Poisson processes"
```
