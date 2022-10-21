# Gradient Descent

Our goal is to get a solution to the problem $\min f(x)$ where $x\in\mathbb{R}^n$. The algorithm is described as follows: $$x_{k+1} = x_{k}-\alpha_k \nabla f(x_k)$$

## Convergence Rate

**Theorem:** Let $f$ be a convex function definied on $\mathbb{R}^n$. The updates of the algorithm guarantee that $$f(x_k)-f^{*} = \mathcal{O}(1/k)$$ 
