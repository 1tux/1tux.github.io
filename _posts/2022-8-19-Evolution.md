---
layout: post
title: 'Evolution: Life’s optimization algorithm'
published: true
---
The idea that animals share similar traits because they evolved from a common ancestor is logical, but there are many contradictory examples.

Taking wings as an example of bats, birds and bees:

<center>
<img src="https://news.berkeley.edu/wp-content/uploads/2021/07/BatFeature_BN-1.jpg" alt="Bat [Mammal]" height=150px>
<img src="https://www.milford-sound.co.nz/wp-content/uploads/2017/07/milford-sound-kea-flight.jpg" alt="Kea [Aves]" height=150px>                                                                     <img src="https://i.ytimg.com/vi/AzvebsZGSHQ/maxresdefault.jpg" alt="Bee [Insects]" height=150px></center>                        
Each pair of wings was developed from scratch with no relation to  common ancestor. Evolution chose to repeat the same trick as it probably paid off for these creatures to be able to fly. In order to solve the flying problem, it was worthwhile to develop wings. This phenomenon is known as "convergent evolution", however it does not have to do with the specifics of evolution but it is rather a property of optimization.

We could think about evolution abstractly, putting aside all its biological content. As an optimization process, evolution aims to solve a problem by randomly applying changes to a given proposed solution, and eliminating those changes that negatively impact the solution.

A simplified evolutionary algorithm could be implemented to solve Sudoku quickly and efficiently. The algorithm begins by assigning random Sudoku board assignments. It then ranks them according to the number of Sudoku constraints that are being met, and merges the top results to create revised assignments.

In some initial game states, there is only one solution. Our algorithm will locate it, but it will be completely independent of the optimization process. The optimization process described above is a sophisticated general purpose method for searching for solutions. The solution is determined by the game's constraints (initial game states) and the Sudoku rules. Other initial settings with many solutions will probably have many shared values that were determined by the problem constraints and the rules of Sudoku.

As an example let's have a look on this almost solved board:
<center><img src="https://raw.githubusercontent.com/1tux/1tux.github.io/master/_posts/sudoku_multiple_solutions.jpeg" alt="sudoku with multiple solutions"></center>

It is clear this Soduko has multiple solutions, however all of them will include the 9,2,6,3,7 values at very specific places in the top left box.

In some initial game states, there is only one solution. Our algorithm will locate it, but it will be completely independent of the optimization process. The optimization process described above is a sophisticated general purpose method for searching for solutions. The solution is determined by the game's constraints (initial game states) and the Sudoku rules. Other initial settings with many solutions will probably have many shared values that were determined by the problem constraints and the rules of Sudoku.

Let's think about flying from a problem solving point of view: In order to fly one has to overcome several problems such as dealing with air pressure and gravity. While the space of solutions for flying is unknown, nature suggests that wings may be useful for solving flying. In fact, this is why evolution created them over and over, and why humans were inspired by them when designing airplanes.

Our next challenge is "the problem of intelligence", in which we want a system that can achieve goals in a variety of environments. Evolution had worked really hard on this one and converged on a single solution: a neural network. We could wonder about the set of solutions to the intelligence problem. Whether it contains many radically different solutions, or a minimized set of solutions that are very similar. By both trying out the expert systems approach for AI for decades, and observing nature, it is evident that the structure of a neural network is a well suited solution for this matter, much like the wings of birds and airplanes.

In addition, artificial neural networks incorporate an optimization scheme that is imposed on a hierarchical processing structure, much like our brains. It is critical to distinguish two aspects of the brain and artificial intelligence that may exhibit similarities: (1) the learning process and (2) the learning outcome. (1) The architecture of the network affects its learning capabilities and therefore could be inspired by the brain. (2) The learned model is made up of neuronal representations and algorithms that are implemented by the network architecture and weights. These too can be similar to the brain. For clarification, (1) comes from convergent evolution, namely the solution evolution finds for designing a neural network. (2) comes from convergent learning, namely the solutions neural networks find for solving particular tasks.

Both offer a unique approach to studying the brain, but more on that in the next post…