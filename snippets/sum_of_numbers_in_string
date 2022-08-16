---
title: Sum of numbers in a string
tags: string, 
expertise: intermediate
firstSeen: 2022-08-16T14:00:00:000
---

The function calculates the sum of all the numbers in the given string.

- The function traverses through all the characters if the string.
- If the chracter is a number, the function adds its value to the result.
- Multiple consecutive numbers are considered as one number.

```py
def findSum(str1):
    temp = "0"
    Sum = 0
    for ch in str1:
        if (ch.isdigit()):
            temp += ch
        else:
            Sum += int(temp)
            temp = "0"
    return Sum + int(temp)
```

```py
print(findSum("12ab20z40")) #72
print(findSum("120nb")) #120
print(findSum("1m2n2")) #5
```
