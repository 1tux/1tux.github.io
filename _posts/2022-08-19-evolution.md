---
layout: post
title: 'Evolution: Life’s optimization algorithm'
published: true
---
The idea that animals share similar traits because they evolved from a common ancestor is logical, but there are many contradictory examples.

Taking wings as an example of bats, birds and bees:

<center>
<img src="https://news.berkeley.edu/wp-content/uploads/2021/07/BatFeature_BN-1.jpg" alt="Bat [Mammal]" height=150px>
<img src="https://preview.redd.it/38v6nrgaqzm31.jpg?width=640&crop=smart&auto=webp&s=3902070bf1a215b09330371916ee3c724c059bd9" alt="Kea [Aves]" height=150px>                                                                     <img src="https://i.ytimg.com/vi/AzvebsZGSHQ/maxresdefault.jpg" alt="Bee [Insects]" height=150px></center>                        
Each pair of wings was developed from scratch with no relation to  common ancestor. Evolution chose to repeat the same trick as it probably paid off for these creatures to be able to fly. In order to solve the flying problem, it was worthwhile to develop wings. This phenomenon is known as "convergent evolution", however it does not have to do with the specifics of evolution but it is rather a property of **optimization**.

We could think about evolution abstractly, putting aside all its biological content. As an optimization process, evolution aims to solve a problem by randomly applying changes to a given proposed solution, and eliminating those changes that negatively impact the solution.

A simplified evolutionary algorithm could be implemented to solve Sudoku quickly and efficiently. The algorithm begins by assigning random Sudoku board assignments. It then ranks them according to the number of Sudoku constraints that are being met, and merges the top results to create revised assignments.

As an example let's have a look on this almost solved board:
<center><img src="https://mentaleap.ai/images/sudoku_multiple_solutions.jpeg" alt="sudoku with multiple solutions"></center>

It is clear this Soduko has multiple solutions, however all of them will include the 9,2,6,3,7 values at very specific places in the top left box. Now let's see how the evolutionary algorithm will tackle this problem.

Any good optimization algorithm, including the evolutionary one, will be able to solve a Sudoku that has only one solution. It is clear in this case that the solution will be indepedent of the optimization itself. Also, in the example above, the optimization algorithm will scan possible solutions until it finds some that satisfying all the rules of the game - correct solutions. Even though the solutions might be different than one another, they will all "include the 9,2,6,3,7 values at very specific places in the top left box" (as mentioed before). This prorperty is independent of the optimization process itself, it is determined by the rules of the games and the initial configuration of the board = constraints. If we had no prior knowledge of the rules of the game (https://www.youtube.com/watch?v=o1dgrvlWML4&ab_channel=defjam99b) we could learn something valuable from observing the set of solutions. In this case we learn that the values at the top left box have to be 9,2,6,3,7 to satisfy the problem's constraints, and that this setting is useful for producing good solutions for that sudoku problem. 

Now let's move from the Sudoku example to thinking about _flying_ from a problem solving point of view: In order to fly one has to overcome several problems such as dealing with air pressure and gravity. While the space of solutions for flying is unknown, nature suggests that wings may be useful for solving flying. In fact, this is why evolution created them over and over again, and why humans were inspired by them when designing airplanes. 

Our next challenge is "the problem of intelligence", in which we want a system that can achieve goals in a variety of environments. Evolution had worked really hard on this one and converged on a single solution: a neural network. We could wonder about the set of solutions to the intelligence problem. Whether it contains many radically different solutions, or a minimized set of solutions that are very similar. By trying out for decades the expert systems approach for AI, and by observing nature, it is evident that the structure of a neural network is well suited for producing intelligence, much like the wings of birds and airplanes.

> The selection of the appropriate model system for a specific problem is one of the greatest strategic decisions one makes within biology - Eric R. Kandel

In addition, artificial neural networks incorporate an optimization scheme that is imposed on a hierarchical processing structure, much like our brains. It is critical to distinguish two aspects of the brain and artificial intelligence that may exhibit similarities:
1. The learning process - The architecture of the network affects its learning capabilities and therefore could be inspired by the brain.
2. The learning outcome - The learned model is made up of neuronal representations and algorithms that are implemented by the network architecture and weights.

For clarification, (1) comes from convergent evolution, namely the solution evolution finds for designing a neural network. (2) comes from convergent learning, namely the solutions neural networks find for solving particular tasks.

It is important to stress out that most Deep Learning researchers are usually intereseted in (1), the study how to develop more efficient learning architectures. We are interested in (2), given a neural network that has already learned to solve a given task, how the solution looks like. What would be the representations and algorithms that are used by the network.
