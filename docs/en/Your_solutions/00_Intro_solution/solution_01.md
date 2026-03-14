# Section 0 - Mathematical Foundations
## 1. Vector Algebra

We are given two vectors in R^3:

a = [2, 1, -3]
b = [4, -2, 1]

We need to calculate:
a) The magnitude of each vector
b) The dot product a · b
c) The cross product a × b
d) The angle between the vectors

## Necessary formulas

### Magnitude of a vector
For v = [vx, vy, vz]:

|v| = sqrt(vx^2 + vy^2 + vz^2)

### Dot product
a · b = axbx + ayby + azbz

### Cross product
a × b = [
aybz - azby,
azbx - axbz,
axby - aybx
]

### Angle between vectors
theta = arccos((a · b) / (|a||b|))

## (a) Magnitude of each vector

For vector a:

|a| = sqrt(2^2 + 1^2 + (-3)^2)
|a| = sqrt(4 + 1 + 9)
|a| = sqrt(14)

For vector b:

|b| = sqrt(4^2 + (-2)^2 + 1^2)
|b| = sqrt(16 + 4 + 1)
|b| = sqrt(21)

## (b) Dot product

a · b = (2)(4) + (1)(-2) + (-3)(1)
a · b = 8 - 2 - 3
a · b = 3

## (c) Cross product

x-component:
(1)(1) - (-3)(-2) = 1 - 6 = -5

y-component:
(-3)(4) - (2)(1) = -12 - 2 = -14

z-component:
(2)(-2) - (1)(4) = -4 - 4 = -8

Therefore:

a × b = [-5, -14, -8]

## (d) Angle between the vectors

theta = arccos((a · b)/(|a||b|))
theta = arccos(3 / (sqrt(14)sqrt(21)))
theta = arccos(3 / sqrt(294))
theta ≈ 79.9 degrees

## Final Results

|a| = sqrt(14)
|b| = sqrt(21)
a · b = 3
a × b = [-5, -14, -8]
theta ≈ 79.9 degrees
