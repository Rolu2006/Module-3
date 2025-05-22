# EX-09-String
## AIM:
To write a python function "remove" that accepts a string and removes all the vowels from the string.
## EQUIPMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
Step 1: Start the function and take a string a as input.

Step 2: Initialize an empty string b to store the result.

Step 3: Loop through each character i in the input string a.

Step 4: If i is not a vowel (not in 'aeiouAEIOU'), add it to string b.

Step 5: After the loop ends, print the final string b.


## PROGRAM:
```
def remove(a):
    b=""
    for i in a:
        if i not in 'aeiouAEIOU':
            b+=i
    print(b)

```
## OUTPUT:
![Screenshot 2025-05-22 223036](https://github.com/user-attachments/assets/a9b31292-68e8-4c04-93cf-d8eb1a2e5f28)





## RESULT:
Thus the program to write a python function "remove" that accepts a string and removes all the vowels from the string  has been executed successfully.
# EX-10-Regex
## AIM:
To write a Python program to check that a string contains only a certain set of characters (in this case a-z, A-Z and 0-9).
## EQUIPMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
Step 1: Import the re module for using regular expressions.

Step 2: Define a function check() and take a string input s from the user.

Step 3: Use re.fullmatch() to check if s contains only letters (a–z, A–Z) and digits (0–9).

Step 4: If the input matches the pattern [a-zA-Z0-9]+, print "True".

Step 5: Otherwise, print "False".
## PROGRAM:
```
import re
def check():
    s=input()
    if re.fullmatch(r'[a-zA-Z0-9]+',s):
        print("True")
    else:
        print("False")
check()
```
## OUTPUT:
![Screenshot 2025-05-22 223332](https://github.com/user-attachments/assets/f9e36d14-3aab-4a33-a0a5-96f931b22d5c)

## RESULT:

Thus the program to write a Python program to check that a string contains only a certain set of characters (in this case a-z, A-Z and 0-9) has been executed successfully.
# EX-11-List
## AIM:
To write a non parameterized function to print the list in descending order that is entered by the user.
## EQUIPMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
Step 1: Define a function sortlist().

Step 2: Take input from the user and evaluate it as a list using eval().

Step 3: Sort the list a in descending order using a.sort(reverse=True).

Step 4: Print the sorted list.

Step 5: End the function.


## PROGRAM:
```
def sortlist():
    a=eval(input())
    a.sort(reverse=True)
    print(a)
```
## OUTPUT:





![Screenshot 2025-05-22 223610](https://github.com/user-attachments/assets/e5a02772-bdf9-4fb1-a776-1aa2d770c625)

## RESULT:
Thus the program to write a non parameterized function to print the list in descending order that is entered by the user has been executed successfully.
# EX-12-Tuples
# (a)
## AIM:
To write a python program to create the tuple using the numbers entered by the user, get the size of the tuple from the user.
## EQUIPMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
Step 1: Read an integer s as the number of elements to be added to the tuple.

Step 2: Initialize an empty tuple tp.

Step 3: Loop s times to take s individual inputs from the user.

Step 4: In each iteration, convert the input to a string and add it to tp using tuple concatenation.

Step 5: After the loop ends, print the final tuple tp.
## PROGRAM:
```
s=int(input())
tp=()
for i in range(s):
    element=input()
    tp=tp+(element,)
print(tp)
```
## OUTPUT:




![Screenshot 2025-05-22 223900](https://github.com/user-attachments/assets/9569af1a-ece9-4380-9b1a-9c2c1d5f4778)

## RESULT:
Thus the program to write a python program to create the tuple using the numbers entered by the user, get the size of the tuple from the user has been executed successfully.
# (b)
## AIM:
To write a python program to create the tuple by the multiples of 3 up to N and the print sum of the elements of the list. Get the N value from the user.
## EQUIPMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
Step 1: Read an integer input N from the user.

Step 2: Create a tuple multiples_of_3 containing all multiples of 3 from 3 up to (but not including) N.

Step 3: Calculate the sum of all elements in the tuple and store it in sum_of_elements.

Step 4: Print the tuple multiples_of_3.

Step 5: Print the sum using a formatted string.
## PROGRAM:
```
N = int(input())
multiples_of_3 = tuple(i for i in range(3, N, 3))
sum_of_elements = sum(multiples_of_3)
print(multiples_of_3)
print(f"Sum is {sum_of_elements}")
```
## OUTPUT:




![Screenshot 2025-05-22 224144](https://github.com/user-attachments/assets/3e9523a1-daa5-4f2a-8043-277904aa567d)



## RESULT:
Thus the program to write a python program to create the tuple by the multiples of 3 up to N and the print sum of the elements of the list. Get the N value from the user has been executed successfully.




