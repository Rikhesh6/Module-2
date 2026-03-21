# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a = 16
print(bin(a))
```

## Output
<img width="432" height="150" alt="image" src="https://github.com/user-attachments/assets/1a311665-1888-4ad7-83d0-ea54f29d7b8b" />

## Result
The program successfully converts the number 16 into its binary representation and prints it.

# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a, b):
    return a % b

a = int(input())
b = int(input())
print("The result of the modulo operation is:", result(a, b))
```

## Output
<img width="443" height="193" alt="image" src="https://github.com/user-attachments/assets/a35b6fe2-19ae-42e6-bb5d-6d8141c354a3" />


## Result
The program successfully defines a function that computes the modulo of two numbers and returns the result.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
i=int(input())
j=int(input())
f = lambda a, b: a+b
print(f(i, j))
```
## Output
<img width="375" height="226" alt="image" src="https://github.com/user-attachments/assets/3683075a-a89e-42bd-b0e0-ea859ba8f3f2" />

## Result
The program successfully defines a lambda function that computes the sum of two numbers and prints the result.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
i=int(input())
j=int(input())
f = lambda a, b: a+b
print(f(i, j))
```
## Output
<img width="375" height="226" alt="image" src="https://github.com/user-attachments/assets/3683075a-a89e-42bd-b0e0-ea859ba8f3f2" />

## Result
The program successfully defines a lambda function that computes the sum of two numbers and prints the result.

## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num = int(input())
temp = num
rev = 0

while temp > 0:
    rev = (10 * rev) + temp % 10
    temp = temp // 10

if rev == num:
    print(f"{num} is a palindrome.")
else:
    print(f"{num} is not a palindrome.")
```
## Output
<img width="392" height="176" alt="image" src="https://github.com/user-attachments/assets/1576881a-f6e2-4ad8-add6-c72afcb42e55" />

## Result
The program successfully checks if a given number is a palindrome by reversing its digits and comparing it to the original number.

