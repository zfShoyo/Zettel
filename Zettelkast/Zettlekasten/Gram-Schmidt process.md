202207181248
Status: #idea
Tags: [[Linear Algebra]]

# Gram-Schmidt process
{${v_{1} .. v_{n}}$} serves as a [[Basis]] for [[Vector Space]] V. 

The Gram-Schmidt process takes this basis and makes it into an [[Orthogonal Basis]] for V. 

$$v_{1} .. v_{n}\rightarrow u_{1} .. u_{n}$$
Step 1:

$$v_{1} = u_{1} $$
Step 2:
$$v_{2} = u_{2} - \frac{u_{2}\cdot v_{1}}{v_{1}\cdot v_{1}}{v_1}$$
Step 3:
$$v_{3} = u_{3} - \frac{u_{3}\cdot v_{1}}{v_{1}\cdot v_{1}}v_{1} - \frac{u_{3}\cdot v_{2}}{v_{2}\cdot v_{2}}v_{2}$$


Repeat this step until $v_{n}$, then {${v_{1} .. v_{n}}$} is an [[Orthogonal Basis]].

Basically we are subtracting off any part of the **u vector** that is not orthogonal to the new vectors to leave just the **orthogonal** part.

Step 4: [[Normalized Vector]] the vectors in the basis to make an [[Orthonormal Basis]].

---


	## Reference