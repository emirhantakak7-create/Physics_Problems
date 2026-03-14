# 1. Gravitational Dependence

We are given a simple pendulum with a period T_earth = 4 s.
The gravitational acceleration on the Moon is g_moon = (1/6) * g_earth.
We need to find the period on the Moon (T_moon) and the length (L) required for a 1-second period on Earth.

The formula for the period of a simple pendulum is:
T = 2 * pi * sqrt(L / g)

---

## Step 1: Find the period on the Moon

Since the length of the pendulum (L) and 2*pi are constant, we can see that the period T is inversely proportional to the square root of g.
T ~ 1 / sqrt(g)

We can set up a ratio:
T_moon / T_earth = sqrt(g_earth / g_moon)

Substitute the given relationship (g_moon = g_earth / 6):
T_moon / 4 = sqrt(g_earth / (g_earth / 6))
T_moon / 4 = sqrt(6)
T_moon = 4 * sqrt(6)

T_moon ≈ 4 * 2.45
T_moon ≈ 9.8 seconds

---

## Step 2: Find the length for a 1-second period on Earth

We want a new period T_new = 1 s on Earth.
We know g_earth ≈ 9.81 m/s^2.

Using the period formula:
T_new = 2 * pi * sqrt(L / g_earth)
1 = 2 * pi * sqrt(L / 9.81)

Solve for L:
1 / (2 * pi) = sqrt(L / 9.81)
Square both sides:
1 / (4 * pi^2) = L / 9.81

L = 9.81 / (4 * pi^2)
L ≈ 9.81 / (4 * 9.869)
L ≈ 9.81 / 39.478
L ≈ 0.248 meters (or 24.8 cm)

---

## Final Result

- The period of the pendulum on the Moon would be approximately **9.8 seconds**.
- To have a period of exactly 1 second on Earth, the pendulum must be approximately **0.248 meters (24.8 cm)** long.
