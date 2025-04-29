# Exp.No:3c
## LIST - EVEN NUMBERS LIST

### AIM  
To write a Python function that accepts a number N, creates a list containing all even numbers from 12 to N, and then prints the sum of all the elements in the list.

### ALGORITHM
1.Start the program.
2.Input the number N from the user.
3.Initialize an empty list even_numbers to store the even numbers.
4.Loop through the range of numbers from 12 to N:
If a number is divisible by 2 (i.e., even), add it to the even_numbers list.
5.Calculate the sum of the numbers in the even_numbers list using the sum() function.
6.Print the list of even numbers.
7.Print the sum of the even numbers.
8.End the program.

### PROGRAM
def createlist(N):
    even_list = [i for i in range(12, N) if i % 2 == 0]
    print("List =", even_list)
    print("Sum of the list", sum(even_list))

### OUTPUT
![image](https://github.com/user-attachments/assets/558efe7b-4a6d-4002-9bcd-3495296816a7)

### RESULT
Thus,the Python function that accepts a number N, creates a list containing all even numbers from 12 to N, and then prints the sum of all the elements in the list was implemented and successfully executed.
