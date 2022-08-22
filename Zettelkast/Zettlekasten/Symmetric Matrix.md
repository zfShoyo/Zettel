202207201948
Status: #idea
Tags: [[Linear Algebra]]

# Symmetric Matrix
A matrix is symmetric if it is equal to the transpose of itself, and it has to be square.
$A = A^T$

If we find D diagonal and P orthogonal such that $A=PDP^T$ , we can super diagonalize the matrix.

### Steps
1. Find the eigenvalues of A
2. Find eigenspaces by plugging in eigenvalues
3. [[Gram-Schmidt process]] both eigenspaces
4. D is the eigenvalues on a diagonal
5. P is the normalized eigenvectors plus the orthonormal basis in one matrix


### Connection to [[Spectral decomposition]]
![[Pasted image 20220720203324.png]]

---


## Reference