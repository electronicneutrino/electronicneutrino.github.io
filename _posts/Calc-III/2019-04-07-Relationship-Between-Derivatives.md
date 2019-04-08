Let $A\subseteq\mathbb{R}^n$, $\vec{a}\in\text{int}(A)$, $f:A\to\mathbb{R}^m$. Suppose $f$ is differentiable at $\vec{a}$. Let $T:=Df(\vec{a})$ be the derivative of $f$ at $\vec{a}$. Then 

1. For every unit vector $\vec{u}\in\mathbb{R}^n$ (why not $\vec{u}\in A$?), the directional derivative of $f$ at $\vec{a}$ in the direction $\vec{u}$ exists and is equal to $D_{\vec{u}}f(\vec{a})=T(\vec{u})$.

2. All partial derivatives $\frac{\partial f_i}{\partial x_i}(\vec{a})$, $1\leq i\leq m, 1 \leq j\leq n$ exists. 

3. The $m\times n$ matrix representing $T$ in the standard basis is the Jacobian matrix

   $$\begin{align} J:=\begin{bmatrix}\frac{\partial f_1}{\partial x_1}({\vec{a}} )& \dots & \frac{\partial f_1}{\partial x_n}(\vec{a}) \\ \vdots & \ddots &\vdots \\ \frac{\partial f_m}{\partial x_1}(\vec{a}) & \dots & \frac{\partial f_m}{\partial x_n}(\vec{a})\end{bmatrix}\end{align}$$

   

