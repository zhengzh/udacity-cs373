# lines segments  $x_{i-2} \rightarrow x_{i-1} \rightarrow x_{i} \rightarrow x_{i+1} \rightarrow x_{i+2}$

# minmal vector difference,(direction and length)
# $vectdiff(\langle x_{i},x_{i+1} \rangle, \langle x_{i-1},x_{i} \rangle) = [(x_{i+1}-x_{i})-(x_{i}-x_{i-1})]^2$
# $=(x_{i+1}+x_{i-1}-2x_{i})^2$
# $\frac{\partial vectdiff}{\partial x_i}=4(x_{i+1}+x_{i-1}-x_{i})$

# we have
# $\frac{\partial vectdiff}{\partial x_i}=-2(x_{i+2}+x_{i}-2x_{i+1})$

# $\frac{\partial vectdiff}{\partial x_i}=-2(x_{i}+x_{i-2}-2x_{i-1})$

# $(1)+(2)+(3)$