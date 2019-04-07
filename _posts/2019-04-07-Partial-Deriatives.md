Let $\\{\vec{e}_j:1\leq j\leq n\\}$ be the standard basis for $\mathbb{R}^n$. Let $A\subseteq\mathbb{R}^n$ and $f:A\to\mathbb{R}^m$. Given a point $\vec{a}\in\text{int}(A)$, we define the **partial derivative** of $f$ with respect to $x_j$ at $\vec{a}$ as 

$$\frac{\partial f}{\partial x_j}(\vec{a}):=D_{\vec{l}_j}f(\vec{a}).$$

This is also denoted by $\partial x_j f(\vec{a})$, $\partial_j f(\vec{a})$, or $f_{\vec{x}_j}(\vec{a})$.

This definition of the partial derivative an eventually be expressed as 

$$\frac{\partial f}{\partial x_j}(\vec{a})=\lim_{h\to 0}\frac{f(a_1, \dots, a_{j}+h, \dots, a_n)-f(a_1, \dots, a_j, \dots, a_n)}{h}.$$

This can be thought of a new function $g$ with a variable $a_j$ and the rest of the variables held constant. 