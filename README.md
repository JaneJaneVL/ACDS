# ACDS
Accelerated by Coupling Directional Search (ACDS) Method
Computer Experiments with number of iterations required

Article: https://arxiv.org/abs/1710.00162  (in Russian)

Accelerated Directional Search Method with non-euclidian prox-structure

Eduard Gorbunov, Alexander Gasnikov, Evgeniya Vorontsova  

In the paper we propose an accelerated directional search method with non-euclidian prox-structure. We consider convex unconstraint optimization problem in Rn. For simplicity we start from the zero point. We expect in advance that 1-norm of the solution is close enough to its 2-norm. In this case the standard accelerated Nesterov's directional search method can be improved. In the paper we show how to make Nesterov's method n-times faster (up to a logn-factor) in this case. The basic idea is to use linear coupling, proposed by Allen-Zhu & Orecchia in 2014, and to make Grad-step in 2-norm, but Mirr-step in 1-norm. We show that for constraint optimization problem this approach stable upon an obstacle. We generalize this result to accelerated gradient-free methods with inexact oracle (here we use the very recent work of Dvurechensky, Gasnikov, Tiurin, 2017).

