This repository contains `LabVIEW` projects for the `Data Acquisition and Processing Methods` course during the 1st semester of **Electronics** (bachelor's) at **PWR**.

# Heron - Triangle Area Calculator

This [program](./subViProj/subVis/heron.vi) calculates the area of a triangle using **Heron's formula**.

## Formula
The formula used for calculating the area of a triangle is as follows:

```
Area = sqrt(p * (p - a) * (p - b) * (p - c))
```

Where:
- `a`, `b`, and `c` are the lengths of the sides of the triangle.
- `p` is the semi-perimeter of the triangle:

```
p = (a + b + c) / 2
```

## Notes
- Ensure the input values satisfy the triangle inequality theorem:
  - `a + b > c`
  - `a + c > b`
  - `b + c > a`
- Invalid side lengths will produce an error.
