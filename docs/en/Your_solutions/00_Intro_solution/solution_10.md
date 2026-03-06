# Section 0 - Mathematical Foundations
## 10. Infinite Series

An ant starts at the origin (0,0) and moves in the following pattern:

1 m east  
1/2 m north  
1/3 m west  
1/4 m south  
1/5 m east  
1/6 m north  
1/7 m west  
1/8 m south  
and so on.

We need to determine the final position of the ant.

---

## Step 1: Separate horizontal and vertical motion

Horizontal motion:
- east is positive
- west is negative

Vertical motion:
- north is positive
- south is negative

---

## Step 2: Horizontal displacement

The horizontal movements are:

1 − 1/3 + 1/5 − 1/7 + 1/9 − ...

This is a known alternating series:

1 − 1/3 + 1/5 − 1/7 + ...

This series equals:

π / 4

So the final horizontal position is:

x = π / 4

---

## Step 3: Vertical displacement

The vertical movements are:

1/2 − 1/4 + 1/6 − 1/8 + ...

Factor out 1/2:

(1/2)(1 − 1/2 + 1/3 − 1/4 + ...)

The series inside the parentheses is the alternating harmonic series:

1 − 1/2 + 1/3 − 1/4 + ...

This series equals:

ln(2)

So the vertical displacement is:

y = (1/2) ln(2)

---

## Final Position

The final position of the ant is:

(x , y) = (π/4 , (1/2)ln(2))
