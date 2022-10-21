# Gradient Descent

Our goal is to get a solution to the problem $\min f(x)$ where $x\in\mathbb{R}^n$. The algorithm is described as follows:
\+
fdfd 
\]
$$
\begin{align*}
\sum_{i = 1}^{n} | (f + g )(x_i) - (f + g)(x_{i-1}) | &= \sum_{i = 1}^{n} | \{ f(x_i) + g(x_i) \} - \{ f(x_{i - 1} + g(x_{i-1}) \} |
\\  &\leq \sum_{i = 1}^{n} | f(x_i) - f(x_{i - 1} | + \sum_{i = 1}^{n} | g(x_i) - g(x_{i - 1})|
\\  &\leq  V(f, P) + V(g, P)
\end{align*}
$$ 

