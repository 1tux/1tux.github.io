---
layout: post
title: 'Evolution: Life’s optimization algorithm'
published: true
---
The idea that animals share similar traits because they evolved from a common ancestor is logical, but there are many contradictory examples.

Taking wings as an example of bats, birds and bees:

<center>
<img src="https://news.berkeley.edu/wp-content/uploads/2021/07/BatFeature_BN-1.jpg" alt="Bat [Mammal]" width=200px>
<img src="https://www.milford-sound.co.nz/wp-content/uploads/2017/07/milford-sound-kea-flight.jpg" alt="Kea [Aves]" width=200px>                                                                     <img src="https://i.ytimg.com/vi/AzvebsZGSHQ/maxresdefault.jpg" alt="Bee [Insects]" width=200px></center>                        
Each pair of wings was developed from scratch with no relation to  common ancestor. Evolution chose to repeat the same trick as it probably paid off for these creatures to be able to fly. In order to solve the flying problem, it was worthwhile to develop wings. This phenomenon is known as "convergent evolution", however it does not have to do with the specifics of evolution but it is rather a property of optimization.

We could think about evolution abstractly, putting aside all its biological content. As an optimization process, evolution aims to solve a problem by randomly applying changes to a given proposed solution, and eliminating those changes that negatively impact the solution.

A simplified evolutionary algorithm could be implemented to solve Sudoku quickly and efficiently. The algorithm begins by assigning random Sudoku board assignments. It then ranks them according to the number of Sudoku constraints that are being met, and merges the top results to create revised assignments.

In some initial game states, there is only one solution. Our algorithm will locate it, but it will be completely independent of the optimization process. The optimization process described above is a sophisticated general purpose method for searching for solutions. The solution is determined by the game's constraints (initial game states) and the Sudoku rules. Other initial settings with many solutions will probably have many shared values that were determined by the problem constraints and the rules of Sudoku.

As an example let's have a look on this almost solved board:
<center>![sudoku with multiple solutions]({{site.baseurl}}/_posts/sudoku_multiple_solutions.jpeg)</center>
