202207181249
Status: #idea
Tags: [[Linear Algebra]]

# Least Square Approximation
This is an application of the [[Orthogonal Projection Matrix]].

We want to get the line :$$y = a_{0} +a_{1}x$$
With two given points, we will set up the linear system as follows: $$\bigg\{\begin{array}{rcl} 1&x_{1} \\ 1&x_{2} \\ \end{array}\bigg\} \bigg\{\begin{array}{rcl} a_{0} \\ a_{1} \\ \end{array}\bigg\} = \bigg\{\begin{array}{rcl} y_{1} \\ y_{2} \\ \end{array}\bigg\}$$ and solve for the formula: $$x^{*} = (A^{T}A)^{-1}A^{T}b$$
This only has a solution when the cols of A are [[Linearly Independent]].
#### Example:
![[Pasted image 20220719162528.png]]

---


## Reference
