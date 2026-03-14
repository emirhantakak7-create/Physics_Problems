## Step 2: Check for path intersection and collision

First, do their paths intersect in space? Yes, they do. But do they collide at the same time? 
For a collision, both x and y coordinates must be equal at the exact same time `t`.

Set x-coordinates equal:
2 + t = 2t - 1
t = 3

Set y-coordinates equal:
8 - 3t = 2t + 2
6 = 5t
t = 6/5

Since the required times (t=3 and t=6/5) are different, they do not occupy the same point at the same time. 
So, **their paths intersect geometrically, but Alice and Bob do not collide.**

---

## Step 3: Find the distance between them

The position difference is:
A(t) - B(t) = ((2 + t) - (2t - 1), (8 - 3t) - (2t + 2))
A(t) - B(t) = (3 - t, 6 - 5t)

The squared distance is:
D^2(t) = (3 - t)^2 + (6 - 5t)^2
D^2(t) = 26t^2 - 66t + 45

---

## Step 4: Minimize the squared distance

Differentiate:
d/dt [D^2(t)] = 52t - 66

Set equal to zero:
52t - 66 = 0
t = 33/26

---

## Step 5: Find the minimum distance

Substitute t = 33/26 into the squared distance formula:
D^2(33/26) = 26(33/26)^2 - 66(33/26) + 45
D^2(33/26) = 1089/26 - 2178/26 + 1170/26
D^2(33/26) = 81/26

So the minimum distance is:
D_min = sqrt(81/26) = 9 / sqrt(26)

---

## Final Result

The paths intersect in space, but Alice and Bob **do not collide** because they reach the intersection at different times.
The minimum distance between them occurs at:
t = 33/26
and the minimum distance is:
D_min = 9 / sqrt(26)
