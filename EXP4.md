# Ex.No: 4 check the given number is Armstrong number or not and inspect for failures.
### DATE:27.03.2025                                                                            
### REGISTER NUMBER : 212224230106
### AIM: 
Write a python program to check the number is Armstrong number or not and inspect for failures.

### Algorithm:
1.  Start the program.
2.	Read an integer input number.
3.	Initialize the variables current_digit, sum = 0, and num = number.
4.	Repeat Steps 5 to 7 until num > 0
5.	current_digit = (num % 10).
6.	sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7.	num = num / 10.
8.	Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9.	Stop the program.

### Program:

```
x = input("Enter the input: ")

if x.isnumeric():
    x = int(x)
    temp = x
    cube = 0

    while temp > 0:
        digit = temp % 10
        cube += digit ** 3
        temp //= 10

    if cube == x:
        print("Armstrong Number")
    else:
        print("Not Armstrong Number")
else:
    print("Enter a Positive Integer.")

```
### Output:

![Screenshot 2025-03-27 081528](https://github.com/user-attachments/assets/dd5f2eb5-8bfb-4a7a-b5f4-9caf119b00df)

![Screenshot 2025-03-27 081556](https://github.com/user-attachments/assets/a6d5d3d0-88ed-41c3-a346-eea677d10a76)

![Screenshot 2025-03-27 081651](https://github.com/user-attachments/assets/caa886bf-5163-4756-be4b-1fd2a3147ca7)

![Screenshot 2025-03-27 081720](https://github.com/user-attachments/assets/3deba781-2dcd-4b97-91eb-d3980f111fa3)

![Screenshot 2025-03-27 081822](https://github.com/user-attachments/assets/727375b1-4f58-4f9c-9a96-2b0fa4b05085)

![Screenshot 2025-03-27 081900](https://github.com/user-attachments/assets/654c4915-5189-4382-b086-5cdef423d297)

![Screenshot 2025-03-27 082555](https://github.com/user-attachments/assets/73a8f657-aca2-426b-bd98-15cefe8e7ea1)

![Screenshot 2025-03-27 082806](https://github.com/user-attachments/assets/f57ff153-1749-4ddd-ba98-c1cdf9b1a892)

![Screenshot 2025-03-27 083217](https://github.com/user-attachments/assets/95d0be4e-5a3f-483a-9478-0c5c6d10ebf2)

![Screenshot 2025-03-27 083229](https://github.com/user-attachments/assets/7068d46e-c03d-41c2-b2bd-ae7767eaa6a3)

### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.


