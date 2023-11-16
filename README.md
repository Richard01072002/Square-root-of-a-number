# EXP-2b Find the square root of a number
## Date: 29.08.2023
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
Program to find the square root for the given number(newton's method) using function.
Developed by: Richardson A
RegisterNumber: 23000803
def newtow_method(number,number_iters=100):
    a=float(number)
    for i in range(number_iters):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",newtow_method(a))
```
## Output:
![gcd of two number](gcd.png)

![image](https://github.com/Richard01072002/Square-root-of-a-number/assets/141472248/da2bb59b-c474-4df2-ac82-c0cff2d180ec)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
