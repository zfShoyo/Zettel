202207181251
Status: #idea
Tags:[[Linear Algebra]]

# Orthogonal Diagonalization
To find a matrix Q that orthogonally diagonalizes another matrix A, given eigenvectors.
1. Find an orthonormal basis for each eigenspace
	- use each eigenvector to find a basis 
	- Perform [[Gram-Schmidt process]]  using the vectors in the basis for both, to find the orthogonal basis
	- Take each value and divide through by the [[Length(Norm)]] of the vector to get the unit vectors. ([[Normalized Vector]])
2. Put all the vectors from the [[Orthonormal Basis]]' to form matrix Q.

#### Example
![[Pasted image 20220719170449.png]]
![[Pasted image 20220720213834.png]]
![[Pasted image 20220720213800.png]]
![[Pasted image 20220720213905.png]]
![[Pasted image 20220720213918.png]]
![[Pasted image 20220720213946.png]]

---
## Reference
[Orthogonal Diagonalization Leah Howard](https://www.youtube.com/watch?v=-eKA0mYNDDQ)