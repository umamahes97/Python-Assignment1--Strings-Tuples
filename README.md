# Python Assignment1
## Title
## Data Structures - Strings & Tuples
### Strings (Concatenation, Slicing and Other methods) :
### 1. String Concatenation: 
Write a Python program that takes two strings i.e string 1 “Hello ”, string 2 get name as input from the user and concatenates them together. Display the concatenated string as the output.  
### Output: 
Enter your Name: Umamaheswari
Hello Umamaheswari
Now concatenate string 3 “, Welcome to Python programming” to the existing string and display the output string. 
### Hello Umamaheswari, Welcome to Python programming.

### 2. String Slicing and Indexing: 
Write a Python program using the above concatenated string as input and performs the 
following tasks:  
### a. Print the first character of the string. 
print("First Character:",message[0])
### First Character: H

### b. Print the last character of the string.
print("Last Character:",message[48])
### Last Character: g
### c. Print the first 5 characters of the string.
print("First 5 Characters:",message[0:5])
### First 5 Characters: Hello

### d. Print the last 11 characters of the string. 
print("Last 11 Characters:",message[38:49])
### Last 11 Characters: Programming

### e. Print the string in reverse.
print("Reverse the string:",message[::-1])
### Reverse the string:gnimmargorP nohtyP ot emocleW ,irawsehamamU olleH

### f. Use slicing and print the word “Python” from the existing string.
print("print the string:",message[31:37])
### print the string: Python

### 3. String Methods: 
Write a Python program that takes a string, strM = “Python beginner tutorial” and perform the following tasks: 
### a. Convert the sentence to uppercase. 
print("Uppercase:",strM.upper())
### Uppercase: PYTHON BEGINNER TUTORIAL

### b. Convert the sentence to lowercase. 
print("Lowercase:",strM.lower())
### Lowercase: python beginner tutorial

### c. Use Capitalize and return the sentence to the original input form.
print("Capitalize:",strM.capitalize())
### Capitalize: Python beginner tutorial

### d. Count the total number of occurrences of character ‘t’  in the string.
print("Count of t:",strM.count("t"))
### Count of t: 3

### e. Replace all occurrences of “Python” with “Machine Learning”  in the input string strM = “Python beginner tutorial”
print("Replace the string:",strM.replace("python","Machine Learning"))
### Replace the string: Machine Learning beginner tutorial

### Tuples (Creation, Modification and Access) :  
Create 1st tuple with values -> (10, 20, 30), 2nd tuple with values -> (40, 50, 60):  
### a. Concatenate the two tuples and store it in “t_combine” 
tuple1=(10,20,30)
tuple2=(40,50,60)
t_combine=tuple1+tuple2  
print(t_combine)
### (10, 20, 30, 40, 50, 60)

### b. Repeat the elements of “t_combine” 3 times  
print(t_combine*3)
### (10, 20, 30, 40, 50, 60, 10, 20, 30, 40, 50, 60, 10, 20, 30, 40, 50, 60)

### c. Access the 3rd element from “t_combine”
print(t_combine[2])          
### 30

### d. Access the first three elements from “t_combine” 
print(t_combine[0:3])        
### (10, 20, 30)

### e. Access the last three elements from “t_combine”
print(t_combine[3:6]) 
### (40, 50, 60)
