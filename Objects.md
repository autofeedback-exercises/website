# Mathematical objects

One way of thining about mathematics is as a language that we can use to describe to describe our experiences in the real world.
To use mathematics in this way you have to understand the various abstract objects that mathematics concerns itself with and the 
different types of phenomenon we can describe using these objects. These objects include things such as numbers, functions, vectors,
sets, matrices, operators, groups and tensors. The differences between these different types of mathematical object are often rather subtle.

The activities in this block will encourage you to think about these some different types of mathematical object. You will learn how we can 
manipulate all these types of objects in python.  Furthermore, the example reports will illustrate the different ways that these objects can 
be used.

```mermaid
flowchart TD
   subgraph one
      direction LR
      A(Example report) --> B(Colab exercises)
      B -- > C(Possible extensions)
   end
   one --> R[Random variable exercises]
   R --> two
   subgraph two
     direction LR
     D(Example report) --> E(Colab exercises)
     E --> F(Possible extensions)
   end 
   click A "objects/complex_number_report.pdf" "An example report in which complex numbers, sets, functions, vectors and matrices are explored"
   click B "https://colab.research.google.com/github/autofeedback-exercises/exercises/blob/main/Objects/Basics/Objects.ipynb" "Colab exercises on manipulating sets, tuples, lists and NumPy arrays using Python"
   click C "objects/basics_extensions.html" "Ideas for portfolio reports based on this topic"
   click D "objects/objects_and_operators_report.pdf" "An example report that uses operators to manipulate mathematical objects"
   click E "https://colab.research.google.com/github/autofeedback-exercises/exercises/blob/main/Objects/Operators/Operators.ipynb" "Colab exercises on manipulating vectors, matrices and NumPy arrays using Python"
   click F "objects/operator_extensions.html" "Ideas for portfolio reports based on this topic"
   click R "Random_variables.html" "The exercises on random variables"
```
