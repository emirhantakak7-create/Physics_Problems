# Section 0 — Mathematical Foundations
## 1. Vector Algebra

We are given two vectors in $\mathbb{R}^3$:

$$
\vec{a} = [2,\,1,\,-3], \qquad \vec{b} = [4,\,-2,\,1]
$$

We need to calculate:

a) The magnitude of each vector  
b) The dot product $\vec{a}\cdot\vec{b}$  
c) The cross product $\vec{a}\times\vec{b}$  
d) The angle between the vectors

---

# Necessary formulas

## Magnitude of a vector

For a vector

$$
\vec{v} = [v_x,v_y,v_z]
$$

the magnitude is

$$
|\vec{v}|=\sqrt{v_x^2+v_y^2+v_z^2}
$$

---

## Dot product

For vectors

$$
\vec{a}=[a_x,a_y,a_z], \quad \vec{b}=[b_x,b_y,b_z]
$$

$$
\vec{a}\cdot\vec{b}=a_xb_x+a_yb_y+a_zb_z
$$

---

## Cross product

$$
\vec{a}\times\vec{b}=
\begin{bmatrix}
a_y b_z - a_z b_y \\
a_z b_x - a_x b_z \\
a_x b_y - a_y b_x
\end{bmatrix}
$$

---

## Angle between vectors

$$
\vec{a}\cdot\vec{b}=|\vec{a}|\,|\vec{b}|\cos\theta
$$

$$
\theta=\arccos\left(\frac{\vec{a}\cdot\vec{b}}{|\vec{a}||\vec{b}|}\right)
$$

---

# (a) Magnitude of each vector

### Magnitude of $\vec{a}$

$$
|\vec{a}|=\sqrt{2^2+1^2+(-3)^2}
$$

$$
|\vec{a}|=\sqrt{4+1+9}
$$

$$
|\vec{a}|=\sqrt{14}
$$

---

### Magnitude of $\vec{b}$

$$
|\vec{b}|=\sqrt{4^2+(-2)^2+1^2}
$$

$$
|\vec{b}|=\sqrt{16+4+1}
$$

$$
|\vec{b}|=\sqrt{21}
$$

---

# (b) Dot product

$$
\vec{a}\cdot\vec{b}=(2)(4)+(1)(-2)+(-3)(1)
$$

$$
\vec{a}\cdot\vec{b}=8-2-3
$$

$$
\vec{a}\cdot\vec{b}=3
$$

---

# (c) Cross product

Let

$$
\vec{a}=[2,1,-3], \quad \vec{b}=[4,-2,1]
$$

### x component

$$
a_y b_z - a_z b_y
$$

$$
(1)(1)-(-3)(-2)
$$

$$
1-6=-5
$$

---

### y component

$$
a_z b_x - a_x b_z
$$

$$
(-3)(4)-(2)(1)
$$

$$
-12-2=-14
$$

---

### z component

$$
a_x b_y - a_y b_x
$$

$$
(2)(-2)-(1)(4)
$$

$$
-4-4=-8
$$

---

Therefore

$$
\vec{a}\times\vec{b}=[-5,-14,-8]
$$

---

# (d) Angle between the vectors

$$
\theta=\arccos\left(\frac{\vec{a}\cdot\vec{b}}{|\vec{a}||\vec{b}|}\right)
$$

Substitute the values

$$
\vec{a}\cdot\vec{b}=3
$$

$$
|\vec{a}|=\sqrt{14}
$$

$$
|\vec{b}|=\sqrt{21}
$$

$$
\theta=\arccos\left(\frac{3}{\sqrt{14}\sqrt{21}}\right)
$$

$$
\sqrt{14}\sqrt{21}=\sqrt{294}
$$

$$
\theta=\arccos\left(\frac{3}{\sqrt{294}}\right)
$$

Approximation

$$
\theta\approx79.9^\circ
$$

---

# Final Results

$$
|\vec{a}|=\sqrt{14}
$$

$$
|\vec{b}|=\sqrt{21}
$$

$$
\vec{a}\cdot\vec{b}=3
$$

$$
\vec{a}\times\vec{b}=[-5,-14,-8]
$$

$$
\theta\approx79.9^\circ
$$
