# 1. Projectile Motion

A projectile is fired from the ground with an initial velocity of 100 m/s at an angle of 37° above the horizontal. Assume no air resistance.

We need to:

- derive the differential equations of motion in the horizontal and vertical directions
- determine the time of flight
- determine the maximum height
- determine the range

---

## Step 1: Resolve the initial velocity into components

Initial speed:

v0 = 100 m/s

Launch angle:

θ = 37°

Horizontal component:

v0x = v0 cos(37°)

Vertical component:

v0y = v0 sin(37°)

Using approximate values:

cos(37°) ≈ 0.7986  
sin(37°) ≈ 0.6018

So:

v0x ≈ 100(0.7986) = 79.86 m/s  
v0y ≈ 100(0.6018) = 60.18 m/s

---

## Step 2: Differential equations of motion

### Horizontal direction

Since there is no air resistance, the horizontal acceleration is zero:

d²x/dt² = 0

So the horizontal velocity is constant:

dx/dt = v0x = 79.86

Integrating:

x(t) = 79.86 t

assuming x(0) = 0.

---

### Vertical direction

The only acceleration is gravity acting downward:

d²y/dt² = -g

Using g = 9.8 m/s²:

d²y/dt² = -9.8

Then:

dy/dt = v0y - 9.8t = 60.18 - 9.8t

Integrating:

y(t) = 60.18 t - 4.9 t²

assuming y(0) = 0.

---

## Step 3: Time of flight

The projectile lands when y(t) = 0.

So:

60.18 t - 4.9 t² = 0

Factor out t:

t(60.18 - 4.9t) = 0

So:

t = 0
or
60.18 - 4.9t = 0

4.9t = 60.18

t = 60.18 / 4.9

t ≈ 12.28 s

So the time of flight is:

T ≈ 12.28 s

---

## Step 4: Maximum height

At maximum height, the vertical velocity is zero.

So:

dy/dt = 60.18 - 9.8t = 0

9.8t = 60.18

t = 60.18 / 9.8

t ≈ 6.14 s

Now substitute this into y(t):

y(t) = 60.18 t - 4.9 t²

y_max = 60.18(6.14) - 4.9(6.14)²

y_max ≈ 184.8 m

So the maximum height is:

H ≈ 184.8 m

---

## Step 5: Range

The range is the horizontal distance traveled during the full time of flight.

R = x(T)

R = 79.86(12.28)

R ≈ 980.7 m

So the range is:

R ≈ 980.7 m

---

## Final Results

Differential equations:

d²x/dt² = 0  
d²y/dt² = -9.8

Position functions:

x(t) = 79.86 t  
y(t) = 60.18 t - 4.9 t²

Time of flight:

T ≈ 12.28 s

Maximum height:

H ≈ 184.8 m

Range:

R ≈ 980.7 m
