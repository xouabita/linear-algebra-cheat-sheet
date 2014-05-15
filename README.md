Linear Algebra - Review Sheet
=============================

*To print this review sheet : http://kiq.li/34K*  
*Feel free to correct, fork or open issue for any mistakes.*


Vector space, subspace, linear independence
-------------------------------------------

### 1. Axioms of a vector space

1. **Commutative :** x ⊕ y = y ⊕ x

2. **Associative ⊕ :** (x ⊕ y) ⊕ z = x ⊕ (y ⊕ z)

3. **Associative ⊙ :** (x ⊙ y) ⊙ z = x ⊙ (y ⊙ z)

4. **First distributive law :** α ⊙ (x ⊕ y) = (α ⊙ x) ⊕ (α ⊙ y)

5. **Second distributive law :** (α ⊕ β) ⊙ x = (α ⊙ x) ⊕ (β ⊙ x)

6. **Neutral element :** 1 ⊙ x = ?

7. **Null vector :** θ ⊙ x = ?

### 2. Subspace of vector space

1. **M = { (x1,x2,...,xn) } :** If (x1, x2, ..., xn) + (y1, y2, ..., yn) = (x1+y1, x2+y2, ..., xn+yn) ∈ M

2. **(0,0,...,0) ∈ M**

### 3. Lineary indepence

Three vectors : v1, v2, v3.  
If α.v1 + β.v2 + γ.v3 = θ have for only solution : α = β = γ = θ, then the three vectors are lineary independent

Basis, dimension, coordinates, subspace
---------------------------------------

### 1. Verify if a set is a basis of vector space

Set P is a basis of vector space if P is lineary independent and dim(P) = dim(vector space).

Matrices
--------

### 1. Finding the rank of a matrice

To find the rank of a matrice A, we transform this matrice by elementary row operation of GEM to the matrix B.  
The rank of the matrice A ( rk(A) ) is the number of non-zero rows in the matrice B.

Scalar product, geometry
------------------------

### 1. Axioms for a scalar product

∀ x,y,z ∈ V and ∀ α ∈ T :

1. **Linearity :** (x, αy + z) = α(x,y) + (x,z)
2. **Symmetry :**
  ![alt text](http://i.imgur.com/FPUkDTz.png)
3. **Positive deﬁniteness :** (x,x) ≥ 0 ∧ ( (x,x) = 0 ⇔ x = 0 )
