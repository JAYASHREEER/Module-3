# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

### AIM  
To write a Python program that matches a string that begins with an `'a'` followed by **zero or more `'b'` characters** using regular expressions.

### ALGORITHM
1.Start the program.
2.Import the re module to use regular expressions.
3.Define a function match_ab_pattern(input_string) to:
Create a regular expression pattern ^ab*$ which matches:
A string that starts with 'a'
Followed by zero or more 'b' characters
And contains only these characters
Use re.fullmatch() to check if the entire string matches the pattern.
Return "Match found" if it matches, otherwise return "No match".
4.Test the function with various input strings.
5.Display whether each string matches the pattern or not.
6.End the program.

### PROGRAM
import re
str=input()
x=re.match("^a(b*)$",str)
if x:
    print("Found a match!")
else:
    print("Not matched!")

### OUTPUT
![image](https://github.com/user-attachments/assets/0cf300e2-f167-45a6-982f-32dc80c648b2)

### RESULT
Thus, Python program that matches a string that begins with an `'a'` followed by **zero or more `'b'` characters** using regular expressions was implemented and successfully executed.
