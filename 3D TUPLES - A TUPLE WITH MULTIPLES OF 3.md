# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 3

### AIM  
To write a Python program that creates a tuple containing all multiples of 3 up to a given number N and prints the sum of the elements in the tuple.

### ALGORITHM
1.Start the program.
2.Input the number N from the user.
3.Create an empty list multiples_of_3.
4.Loop through the range of numbers from 3 to N:
If a number is divisible by 3, append it to the list multiples_of_3.
5.Convert the list multiples_of_3 to a tuple.
6.Calculate the sum of the tuple elements.
7.Print the tuple and its sum.
8.End the program.

### PROGRAM
N = int(input())
multiples_of_3 = tuple(i for i in range(3, N, 3))
print(multiples_of_3)
sum_of_elements = sum(multiples_of_3)
print("Sum is", sum_of_elements)

### OUTPUT
![image](https://github.com/user-attachments/assets/c3e8719f-a85d-43ef-b318-1d23c13e9960)

### RESULT
Thus, the Python program that creates a tuple containing all multiples of 3 up to a given number N and prints the sum of the elements in the tuple was implemented and successfully executed.
