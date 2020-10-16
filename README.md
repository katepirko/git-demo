# README for HomeTask1 on EPAM Online Python course

## 1. PEP8
I've got acquainted with the standarts of PEP8

---

## 2. Python program
I've written a program for calculating area of triangle with given sides
```
"""
Calculate the area of triangle with sides a = 4.5, b = 5.9 and c = 9.
Print calculated value with precision = 2.
"""

A = 4.5
B = 5.9
C = 9.0


def triangle_area(x, y, z):    # Heron`s formula
    p = (x+y+z) / 2
    temp = p * (p-x) * (p-y) * (p-z)
    return pow(temp, 0.5)

print("Area of triangle: %.2f" % (triangle_area(A, B, C)))

```

Result: `Area of triangle: 11.58`
