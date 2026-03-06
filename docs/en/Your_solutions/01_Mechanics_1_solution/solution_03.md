# 3. Path Intersection

Alice moves along the path:

A(t) = (2 + t, 8 - 3t)

Bob moves along the path:

B(t) = (2t - 1, 2t + 2)

We need to determine whether their paths intersect. If yes, we must find when and where they collide. If not, we must find the minimum distance between them and when it occurs.

---

## Step 1: Write the coordinates of each path

For Alice:

x_A(t) = 2 + t  
y_A(t) = 8 - 3t

For Bob:

x_B(t) = 2t - 1  
y_B(t) = 2t + 2

---

## Step 2: Check for intersection

If they intersect at the same time, then both x-coordinates and y-coordinates must be equal.

So we solve:

2 + t = 2t - 1  
8 - 3t = 2t + 2

From the first equation:

2 + t = 2t - 1

3 = t

From the second equation:

8 - 3t = 2t + 2

6 = 5t

t = 6/5

Since the two equations give different values of t, there is no common time at which both coordinates are equal.

So Alice and Bob do not collide.

---

## Step 3: Find the distance between them

The position difference is:

A(t) - B(t) = ((2 + t) - (2t - 1), (8 - 3t) - (2t + 2))

Simplify:

A(t) - B(t) = (3 - t, 6 - 5t)

So the squared distance is:

D^2(t) = (3 - t)^2 + (6 - 5t)^2

Expand:

D^2(t) = (9 - 6t + t^2) + (36 - 60t + 25t^2)

D^2(t) = 26t^2 - 66t + 45

---

## Step 4: Minimize the squared distance

Differentiate:

d/dt [D^2(t)] = 52t - 66

Set equal to zero:

52t - 66 = 0

52t = 66

t = 33/26

---

## Step 5: Find the minimum distance

Substitute t = 33/26 into:

D^2(t) = 26t^2 - 66t + 45

D^2(33/26) = 39/26 = 3/2

So:

D_min = sqrt(3/2)

This can also be written as:

D_min = sqrt(6) / 2

---

## Step 6: Find the positions at that time

At t = 33/26:

Alice:

A(33/26) = (2 + 33/26, 8 - 3(33/26))

A(33/26) = (85/26, 109/26)

Bob:

B(33/26) = (2(33/26) - 1, 2(33/26) + 2)

B(33/26) = (20/13, 59/13)

---

## Final Result

The paths do not intersect at the same time, so Alice and Bob do not collide.

The minimum distance occurs at:

t = 33/26

and the minimum distance is:

D_min = sqrt(3/2) = sqrt(6)/2
