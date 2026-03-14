# 6. Variable Velocity

The velocity of an object as a function of time is:
v(t) = t^2 + 2t - 5

Initial condition: At t = 0, the position is x(0) = 4.
We need to find the object's acceleration a(t) and position x(t) at time t = 3.

---

## Step 1: Find the acceleration at t = 3

Acceleration is the first derivative of velocity with respect to time:
a(t) = d[v(t)] / dt
a(t) = d/dt (t^2 + 2t - 5)
a(t) = 2t + 2

Now, substitute t = 3 into the acceleration function:
a(3) = 2(3) + 2
a(3) = 6 + 2
a(3) = 8

So, the acceleration at t = 3 is 8.

---

## Step 2: Find the position function x(t)

Position is the integral of velocity with respect to time:
x(t) = ∫ v(t) dt
x(t) = ∫ (t^2 + 2t - 5) dt
x(t) = (1/3)t^3 + t^2 - 5t + C

To find the integration constant C, we use the initial condition x(0) = 4:
x(0) = (1/3)(0)^3 + (0)^2 - 5(0) + C = 4
C = 4

So the complete position function is:
x(t) = (1/3)t^3 + t^2 - 5t + 4

---

## Step 3: Find the position at t = 3

Substitute t = 3 into the position function:
x(3) = (1/3)(3)^3 + (3)^2 - 5(3) + 4
x(3) = (1/3)(27) + 9 - 15 + 4
x(3) = 9 + 9 - 15 + 4
x(3) = 18 - 15 + 4
x(3) = 7

So, the position at t = 3 is 7.

---

## Final Result

At time t = 3:
Acceleration: **a(3) = 8**
Position: **x(3) = 7**
