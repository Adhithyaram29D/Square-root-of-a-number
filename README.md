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
Developed by: AdhithyaRam D
RegisterNumber:  212222230008
*/
def square(b,n=100):
    a=float(b)
    for i in range(n):
        b=0.5*(b+a/b)
    return b
a=int(input())
print("Square root of the number:",square(a))
```

## Output:
![Screenshot 2023-06-03 213843](https://github.com/Adhithyaram29D/Square-root-of-a-number/assets/119393540/ac55799e-9e5c-403e-976e-72cdbab4709d)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
