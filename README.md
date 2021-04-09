# ACDS
Accelerated by Coupling Directional Search (ACDS) Method
Computer Experiments with number of iterations required

Article: https://arxiv.org/abs/1710.00162  (in Russian)

Accelerated Directional Search Method with non-euclidian prox-structure

In the paper we propose an accelerated directional search method with non-euclidian prox-structure. We consider convex unconstraint optimization problem in $R^n$. We expect that 1-norm of the solution is close enough to its 2-norm. In this case the standard accelerated Nesterov's directional search method can be improved. In the paper we show how to make Nesterov's method n-times faster (up to a logn-factor) in this case. The basic idea is to use linear coupling, proposed by Allen-Zhu & Orecchia in 2014, and to make Grad-step in 2-norm, but Mirr-step in 1-norm. We show that for constraint optimization problem this approach stable upon an obstacle. 

