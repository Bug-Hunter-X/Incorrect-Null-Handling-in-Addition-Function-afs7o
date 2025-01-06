# Incorrect Null Handling in Addition Function

This repository demonstrates a common error in JavaScript related to null value handling. The `foo` function is designed to add two numbers, but its handling of null input values is flawed.

## Bug Description
The original `foo` function returns `null` if either or both input values are `null`, regardless of whether the other input value is a number.  This is not intuitive and can lead to unexpected behavior in applications.

## Solution
The improved `foo` function handles null values appropriately, treating them as 0.  This ensures that the addition operation continues even if one or both inputs are null.