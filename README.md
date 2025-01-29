# JavaScript Type Coercion Bug

This repository demonstrates a common, yet often unexpected, behavior in JavaScript: type coercion during arithmetic operations. Specifically, this example highlights the implicit type conversion that occurs when adding a number and a string.

## The Bug

The `foo` function intends to add two numbers. However, when one of the arguments is a string, JavaScript concatenates the values instead of performing numerical addition.

## The Solution

The solution involves explicitly converting both arguments to numbers before the addition operation, thus avoiding the unintended string concatenation.