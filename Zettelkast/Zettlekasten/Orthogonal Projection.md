202207181248
Status: #idea
Tags: [[Linear Algebra]]
 

# Orthogonal Projection

![[Pasted image 20220718133803.png|300]]

Think about the **projection** of x as the shadow of the line onto the line **L**, which is all the scalar multiples of the vector **v**.

$$Proj_{L}(x) = \frac{x\cdot v }{v\cdot v}v 
$$

### Example1  *finding projection vector*

Let **y** = $\bigg\{\begin{array}{rcl} 7 \\ 6 \\ \end{array}\bigg\}$ and and **u** = $\bigg\{\begin{array}{rcl} 2 \\ 1 \\ \end{array}\bigg\}$. Find the orthogonal projection of y onto **u**. Then write **y** as the sum of two orthogonal vectors, one in span {**u**} and one orthogonal to to **u**.

###### **Step 1: Find projection**
![[Pasted image 20220718143722.png]]

###### **Step 2: Determine the component of y orthogonal to u, y- projy**

The vector in the span was just found being $\bigg\{\begin{array}{rcl} 8 \\ 4 \\ \end{array}\bigg\}$ , remember this is in the line of the scalar multiples of u.

$y-projy$ is $\bigg\{\begin{array}{rcl} 7 \\ 6 \\ \end{array}\bigg\}$ - $\bigg\{\begin{array}{rcl} 8 \\ 4 \\ \end{array}\bigg\}$ = $\bigg\{\begin{array}{rcl} -1 \\ 2 \\ \end{array}\bigg\}$ .

##### Step 3: Verify that {projy, y- projy} is an [[Orthogonal Set]].

![[Pasted image 20220718144154.png]]




---


## Reference
[Linear Algebra 6.2.2 Orthogonal Projections](https://www.youtube.com/watch?v=fqbwErsP8Xw)