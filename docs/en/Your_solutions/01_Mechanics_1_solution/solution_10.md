# 10. Kinematics

Point M moves according to the parametric equation:
r(t) = (a*cos(wt), b*sin(wt), bt)
where a, b, and w (omega) are positive constants.

---

## Step 1: Equation of the trajectory

To find the path equation, we need to eliminate the time parameter 't' from the x and y coordinates.
x = a*cos(wt)  =>  x/a = cos(wt)
y = b*sin(wt)  =>  y/b = sin(wt)

Using the trigonometric identity cos^2(wt) + sin^2(wt) = 1, we get:
(x/a)^2 + (y/b)^2 = 1

This is the equation of an ellipse in the xy-plane. Since the z-coordinate increases linearly with time (z = bt), the particle moves upwards while tracing this ellipse. 
**The trajectory is an Elliptical Helix.**

---

## Step 2: Compute the path length from t=0 to t=t_0

Path length (S) is the integral of the magnitude of velocity (speed).
First, find the velocity vector by taking the derivative of r(t):
v(t) = dr/dt = (-a*w*sin(wt), b*w*cos(wt), b)

The magnitude of velocity (speed) is:
|v(t)| = sqrt((-a*w*sin(wt))^2 + (b*w*cos(wt))^2 + b^2)
|v(t)| = sqrt(a^2*w^2*sin^2(wt) + b^2*w^2*cos^2(wt) + b^2)

The path length S is the integral of this speed from 0 to t_0:
S = ∫ [from 0 to t_0] sqrt(a^2*w^2*sin^2(wt) + b^2*w^2*cos^2(wt) + b^2) dt

*Note: Because 'a' and 'b' can be different, this integral is an "Elliptic Integral of the Second Kind" and generally cannot be solved with elementary functions unless a = b.*

---

## Step 3: Special Cases

**Case 1: a = b (Circular Helix)**
If a = b, the base becomes a perfect circle. The speed simplifies to a constant:
|v| = sqrt(a^2*w^2*(sin^2(wt) + cos^2(wt)) + b^2) = sqrt(a^2*w^2 + b^2)
Path length becomes simple: S = t_0 * sqrt(a^2*w^2 + b^2)

**Case 2: b = 0 (Simple Harmonic Motion)**
If b = 0, the y and z components vanish. The motion becomes x(t) = a*cos(wt), which is simple harmonic motion along the x-axis.

---

## Step 4: Python Code to Draw the Trajectory

```python
import numpy as np
import matplotlib.pyplot as plt

# Define constants
a, b, w = 3.0, 1.5, 2.0
t = np.linspace(0, 10, 500)

# Parametric equations
x = a * np.cos(w * t)
y = b * np.sin(w * t)
z = b * t

# Plotting the trajectory
fig = plt.figure()
ax = fig.add_subplot(111, projection='3d')
ax.plot(x, y, z, label='Elliptical Helix', color='b')
ax.set_xlabel('X axis')
ax.set_ylabel('Y axis')
ax.set_zlabel('Z axis')
ax.set_title('Trajectory of Point M')
plt.legend()
plt.show()
