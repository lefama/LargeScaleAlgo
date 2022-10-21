# Gradient Descent

Our goal is to get a solution to the problem $\min f(x)$ where $x\in\mathbb{R}^n$. The algorithm is described as follows:

$$
\begin{align}
\mbox{Input:} & \mbox{ function } f \mbox{ and } x_0\in \mathbb{R}^n \\
& \mbox{for }k=1,2,...,T \\
& \mbox{\hspace{1 cm}}x_{k+1} = x_{k}-\alpha_k \nabla f(x_k) \\
& \mbox{end }
\end{align}
$$


## Convergence Rate

**Theorem:** Let $f$ be a convex function definied on $\mathbb{R}^n$. The updates of the algorithm guarantee that $$f(x_k)-f^{*} = \mathcal{O}(1/k)$$ 
