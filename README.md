# crossword-solver
Goal: build an end-end crossword solver using deep learning

Solver has 2 steps:

1) clue answer ranking
2) combining rank lists

Step1:
reimplement 1: https://www.aclweb.org/anthology/P15-2033
as it is the best clue answer ranking till now. try to improve upon it.

Step2:
similar to previous approaches model combining rank lists as a weighted csp and try to solve using deep learning.
extremely preliminary work : http://www.hong.me/papers/xu2018c.html. They only solve binary csp we need to solve more complicated ones.

link to data: https://ikernels-portal.disi.unitn.it/projects/webcrow/





Other solvers:

First crossword solver: http://www.oneacross.com/proverb/papers/aij02-proverb.pdf

Current best solver: https://arxiv.org/abs/1401.4597
