Let $I\subseteq\mathbb{R}^n​$ be a box and let $P​$ be a partition with indexing set $J​$ and sub-boxes $\{I^{(\vec{a})}:\vec{a}\in J\}​$. Then 

$$\mu(I)=\sum_{\vec{a}\in J}(I^{(\vec{a})})​$$



Proof: 

By definition, 

$$\mu(I)=\prod_{k=1}^{n} (b_k-a_k),​$$ 

$$(b_k-a_k)=\sum_{i=1}^{l_k}(x_k^{i}-x_k^{i-1}),$$

and 

$$\mu(I^{(\vec{a})})=\prod_{k=1}^n(x_k^{(a_k)}-x_k^{(a_k-1)})$$

for each $k\in\\{1, \dots, n\\} ​$  (see volume of box and partition of box). 

Then 

$\begin{align}\mu(I) &= \prod_{k=1}^n\sum_{i=1}^{l_k}(x_k^i-x_k^{i-1}) \\\\ &=\left[ \sum_{j=1}^{l_1}(x_k^{a_1}-x_k^{a_1-1}) \right]\cdot \dots \cdot \left[ \sum_{j=1}^{l_n}(x_k^{a_n}-x_k^{a_n-1}) \right] \\\\ &=\sum_{a_1=1}^{l_1}\dots\sum_{a_n=1^{l_n}}\prod_{k=1}^{n}(x_k^{a+k}-x_k^{(a_k-1)}) \\\\ &=\sum_{a\in J}\prod_{k=1}^{n} (x_k^{a_k}-x_k^{a_k-1}) \\\\ &=\sum_{a\in J} \mu(I^{\vec{a}}) \end{align} ​$

as desired. 

