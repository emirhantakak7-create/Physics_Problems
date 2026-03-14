# 4. Vector Calculus

The position of an object as a function of time is given by:
r(t) = (3t^2)i + (5t - 8t^2)j

We need to find the velocity and acceleration vectors as a function of time.

---

## Step 1: Find the Velocity Vector, v(t)

Velocity is the first derivative of the position vector with respect to time:
v(t) = d[r(t)] / dt

We differentiate the x and y components separately:
x-component: d/dt (3t^2) = 6t
y-component: d/dt (5t - 8t^2) = 5 - 16t

So, the velocity vector is:
v(t) = (6t)i + (5 - 16t)j

---

## Step 2: Find the Acceleration Vector, a(t)

Acceleration is the first derivative of the velocity vector (or the second derivative of the position vector) with respect to time:
a(t) = d[v(t)] / dt

We differentiate the x and y components of the velocity separately:
x-component: d/dt (6t) = 6
y-component: d/dt (5 - 16t) = -16

So, the acceleration vector is:
a(t) = 6i - 16j

---

## Final Result

The object's velocity and acceleration vectors are:
Velocity: v(t) = (6t)i + (5 - 16t)j
Acceleration: a(t) = 6i - 16j
