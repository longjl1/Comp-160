---
description: '''''''''Lecture note #1 - Jan 18, 2024'''''''
---

# 🚩 Sorting Task

## \[1] Problem statement

1. What does the "sorted" mean  -> for example: alphabetically by name (first name or last name)... region ..
   1. Sorting is for ordering? complete? or grouping?
2. Explain your input
3. State your assumptions&#x20;

{% hint style="info" %}
Sorting techniques:

Divide-and-conquer&#x20;

`(Bucket sort`&#x20;

`Insertion sort`

`Bubble sort) comparison-based sorting`

Counting sort&#x20;
{% endhint %}



### Problem 1

Given an unsorted array  A \[1,2,...,n] if int, what is the largest value that can be obtained by multiplying all but are entry of A. Restriction: Can not use division.&#x20;

\[15, 3, -2, 7,-9, 1, 4]

Algorithm options:

Brute force: eliminate each A, multiply rest and track max,  $$O(n^2)$$

Count number of negative numbers

1. If 0, removes smallest number&#x20;
2. if odd, remove smallest in abs value
3. if even, possible ending: remove smallest non-negative&#x20;





