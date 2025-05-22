# Reema-praba-V-Module-4
# 19CS301-Module4
### Register No - 212222020020
### Name - Reema praba V

# ExNo: 4.1 Dictionary
### Aim: To write a Python script to check whether a given key  5,9 already exists in a dictionary. d = {1: 10, 2: 20, 3: 30, 4: 40, 5: 50, 6: 60}
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Create a dictionary `d` with some key-value pairs.

**STEP 3:** Create a list `keys` containing keys to check.

**STEP 4:** Use a `for` loop to iterate through each key `i` in the `keys` list:
- If `i` is present in the dictionary `d`, print `"Key is present in the dictionary"`.
- Otherwise, print `"Key is not present in the dictionary"`.

**STEP 5:** Stop.

### Program:
```
d = {1:10,2:20,3:30,4:40,5:50,6:60}
keys= [5,9]
for i in keys:
    if i in d:
        print("Key is present in the dictionary")
    else:
        print("Key is not present in the dictionary")

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/12625925-47c6-4334-a7dd-166d3b022581)

### Result: Thus, the given program is implemented and executed successfully .

# ExNo: 4.2 Exception
### Aim: To write a python program for the solution of value error in exception handling and check whether the number is even or odd.
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Use a `try` block to attempt the following:
- Get input from the user and convert it to an integer. Store it in variable `x`.

**STEP 3:** If a `ValueError` occurs (i.e., input is not a number), execute the `except` block:
- Print `"Enter only number"`.

**STEP 4:** If no exception occurs, continue with the `else` block:
- If `x % 2 == 0`, print `"You entered even number"`.
- Otherwise, print `"An odd number"`.

**STEP 5:** Stop.

### Program:
```
try:
   x = int(input())
except ValueError:
   print("Enter only number")
else:
   if x%2==0:
      print("You entered even number")
   else:
      print("An odd number")

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/4c369168-d68f-46e4-8d5b-8c042c3382ff)

### Result: Thus, the given program is implemented and executed successfully .

# ExNo: 4.4 Classes and Objects 
### Aim: To Write a Python class which has two methods get_String and print_String. get_String accept a string from the user and print_String print the string in upper case.
### Algorithm:

**STEP 1:** Start.

**STEP 2:** Define a class `string1`.

**STEP 3:** Inside the class, define the `__init__` method:
- Initialize the attribute `self.string` to an empty string `" "`.

**STEP 4:** Define the method `get_string()`:
- Get user input and store it in `self.string`.

**STEP 5:** Define the method `print_string()`:
- Print the string `self.string` in uppercase using the `upper()` method.

**STEP 6:** Create an object `manipulator` of class `string1`.

**STEP 7:** Call `manipulator.get_string()` to input a string.

**STEP 8:** Call `manipulator.print_string()` to print the string in uppercase.

**STEP 9:** Stop.

### Program:
```
class string1:
    def _init_(self):
         self.string = " "
    def get_string(self):
         self.string = input()
    def print_string(self):
         print(self.string.upper())
manipulator = string1()
manipulator.get_string()
manipulator.print_string()

```
### OUTPUT:
![image](https://github.com/user-attachments/assets/185ddc06-c8fe-4197-a6c2-abb24cebcb69)

### Result: Thus, the given program is implemented and executed successfully .
