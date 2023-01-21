# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
```
step1: Define a function.
step2: Get the two numbers from the user.
step3: Compare the two values, to find the smaller number.
step4: Use for() and if() loop to find the GCD of the two numbers.
```
## Program:
```
def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
        smaller=n2
    else:
        smaller=n1

    for i in range(1,smaller+1):
        if(n1%i==0)and(n2%i==0):
           hcf=i

    print("GCD of two numbers is:" ,hcf)
```

## Output:
![Screenshot (28)](https://user-images.githubusercontent.com/118708624/213877687-f48853cc-5315-4934-8819-5e141032bca4.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
