# JavaScript Bug: Loose Comparison and Null Values

This repository demonstrates a common JavaScript bug involving loose comparison (==) and null values. Loose comparison can lead to unexpected results when comparing values of different types.  The bug shows how this can happen and provides a solution.

## Bug Description
The `foo` function is intended to handle null values gracefully. However, the original implementation may produce unexpected behavior due to loose comparison of null with other values, including 0 and empty strings.

## Solution
The solution addresses the problem by using strict equality (===) to avoid type coercion.