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

# Collatz Conjecture Calculator

This [program](./subViProj/subVis/collatzSequence.vi) calculates the sequence described by the **Collatz conjecture** (also known as the **3n + 1 problem**).

## Description
The Collatz conjecture sequence is calculated using the following rules:

- If the number is **even**, the next number is `n / 2`.
- If the number is **odd**, the next number is `3 * n + 1`.

The sequence continues until it reaches **1**.

## Example
For a starting value of `6`:
```
6 → 3 → 10 → 5 → 16 → 8 → 4 → 2 → 1
```

## Notes
- The program assumes the starting value is a positive integer.
- The sequence is guaranteed to reach 1 based on the conjecture's assumptions, though this has not been formally proven for all integers.
