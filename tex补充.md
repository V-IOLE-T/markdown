可以用于计算方阵C的特征多项式和特征根。

$ C=
\begin{pmatrix}
  a_1b_1&a_1b_2  &\cdots  &a_1b_n \\
  a_2b_1&a_2b_2  &\cdots  &a_2b_n \\
  \cdots&\cdots  &  &\vdots \\
  a_nb_1&a_nb_2  &\cdots  &a_nb_n
\end{pmatrix}$

令$A=(a_1,a_2,\cdots,a_n)^T,B=(b_1,b_2,\cdots,b_n),$

则$C=AB$
$$\frac{\left|\lambda E-AB\right|}{\lambda^n}=\frac{\left|\lambda E-BA\right|}{\lambda}$$
而$BA=\sum a_ib_i$

因此可得。