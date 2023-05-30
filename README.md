# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: vasanth.s
RegisterNumber:212222110052
def square(n):
    x=n
    b=1
    for i in range(20):
        b=0.5*(b+x/b)
    return b
n=int(input())
sq=square(n)
print("Square root of the number:",sq)
*/
```

## Output:
![gcd of two number](gcd.png)
![12](https://github.com/vasanth0908/Square-root-of-a-number/assets/122000018/82eb2d9c-c464-4546-bace-ea3c23a6d21b)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
