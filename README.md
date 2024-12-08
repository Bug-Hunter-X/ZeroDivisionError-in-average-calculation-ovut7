# Python Average Calculation Bug

This repository demonstrates a common bug in Python code related to calculating the average of a list of numbers. The bug occurs when the input list is empty, leading to a `ZeroDivisionError`.

## Bug Description

The provided code attempts to calculate the average of numbers in a list.  However, if the list is empty, it will raise a `ZeroDivisionError` because it tries to divide by zero.  The solution involves handling the edge case where the input list is empty.