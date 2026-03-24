NAME: Deepika V

REGISTER NUMBER: 212224240030

1. Built-in Functions -Binary Conversion Using Built-in Functions in Python

🎯 Aim:

To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

🧠 Algorithm:

Assign the value 16 to a variable a.

Use the built-in bin() function to convert the number to binary.

Print the result.

🧾 Program:
```
a=int(input())
z=bin(a)
print(z)
```
OUTPUT:

<img width="656" height="156" alt="image" src="https://github.com/user-attachments/assets/61edcd89-232c-4f76-a7a5-dcd804234522" />

Result:

Thus, the python program was executed successfully.

2. Functions in Python: Modulo Calculator

🎯 Aim:

To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

🧠 Algorithm:

1.Define a function called result that takes two arguments a and b.

2.Inside the function, compute the modulo using a % b.

3.Print the result of the modulo operation.

4.Get two integer inputs from the user.

5.Call the result function with the user-provided values.

🧾 Program:
```
def result(a,b):
    return a%b
a=int(input())
b=int(input())
print(f"modulo is {result(a,b)}")
```

OUTPUT:

<img width="659" height="179" alt="image" src="https://github.com/user-attachments/assets/d44a2e52-b45b-438c-9ffe-9ab45f24c20d" />


Result:

Thus, the python program was executed successfully.

3. Lambda Function in Python: Addition of Two Numbers

🎯 Aim:

To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum.

🧠 Algorithm:

1.Get two integer inputs from the user.

2.Use a lambda function to define a function f that returns a + b.

3.Call the function with the user inputs and print the result.

🧾 Program:
```
a=int(input())
b=int(input())
c=int(input())
f=a+b+c
print(f)
```
OUTPUT:

<img width="665" height="213" alt="image" src="https://github.com/user-attachments/assets/a5526935-eb12-47d7-a061-8884aa801b04" />

Result:

Thus, the python program was executed successfully.

4. Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.

🎯 Aim:

To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

🧠 Algorithm:

1.Start the program.

2.Input the number of rows from the user.

3.Loop from 0 to the number of rows.

4.For each row:

    Print appropriate spaces to shape the triangle.

    Compute values using the formula:

[ C(n, k) = \frac{n!}{k!(n-k)!} ]

7.Print all rows of Pascal’s Triangle.

8.End the program.


Program:
```
a=int(input())
for i in range(a):
    
    for j in range(a-i-1):
        print(end=" ")
    for m in range(i+1):          
             ncr=1
             if(i>0):
                ncr=1
                for k in range(1,m+1):
                     c=(i-k+1)/k
                     ncr=ncr*c
             print(int(ncr), end=" ")
    print("")
```
OUTPUT:

<img width="664" height="542" alt="image" src="https://github.com/user-attachments/assets/9c796b29-4ccb-45ed-a8ed-72e173ab81bc" />

Result:

   Thus, the python program was executed successfully.

5. Loops in Python: Palindrome Number Checker

🎯 Aim:

To write a Python program that checks whether a given number is a palindrome using loops.


🧠 Algorithm:

1.Get input from the user and assign it to a variable num.

2.Assign the value of num to a temporary variable temp.

3.Initialize a variable rev to 0 (used to store the reversed number).

4.Use a while loop to reverse the digits:

5.While temp > 0:
  rev = (10 * rev) + temp % 10
  temp = temp // 10

5.After the loop, compare rev with num:
   If equal, print that the number is a palindrome.
   Else, print that it is not a palindrome.
 
 🧾 Program:
 ```

num=int(input())
rev=0
temp=num

while temp>0:
    rem=temp%10
    rev=rev*10+rem
    temp//=10
    
if rev==num:
        print(f"The given number {num} is a Palindrome")
else:
        print(f"The given number {num} is not a palindrome")
```
Output:

<img width="664" height="129" alt="image" src="https://github.com/user-attachments/assets/2be33e71-3024-4eed-98cd-1b21383146e3" />

Result:

Thus, the python program was executed successfully.





