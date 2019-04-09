Let $A\subseteq\mathbb{R}^n$, $B\subseteq\mathbb{R}^m$, $f:A\to B$ and $g:B\to\mathbb{R}^l$. Suppose $\vec{a}\in \text{int}(A)$ and $\vec{b}=f(\vec{a})\in \text{int}(B)$. If $f$ is differentiable at $\vec{a}$ and $g$ is differentiable at $f(\vec{a})$, then the composition $h:=g\circ f$ defined by $h(\vec{x})=g(f(\vec{x}))$ is differentiable at $\vec{a}$ and the derivative is 

$$D_{h}(\vec{a})=Dg(f(\vec{a}))\circ D_f(\vec{a})$$