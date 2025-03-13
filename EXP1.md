# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 212224230106

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

1.do..While:
```
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        
        while True:
            print(start, end=' ')
            if start < end:
                start += 1
            else:
                break
    else:
        print("Please enter valid positive numbers.")

display()
```
2.while..do:
```
start = input("Enter a positive value for START: ")
end = input("Enter a positive value for END: ")

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)
    
    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")
```
3.switch:
```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }
    
    n = input('Enter a value for N: ')
    
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()
```
4.if..else:
```
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)
        
        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")
        
compare()
```
5.for:
```
def iterate():
    string = input("Enter a string: ")
    for i in string:
        print(ord(i), end=" ")

iterate()
```


### Output:

1.do..while:

![Screenshot 2025-03-13 082817](https://github.com/user-attachments/assets/c3984f1a-6f62-4f12-bd6a-615989d357c2)
![Screenshot 2025-03-13 082847](https://github.com/user-attachments/assets/21fcf46c-a261-419c-acfd-545f93f9651e)

2.while..do:

![Screenshot 2025-03-13 084400](https://github.com/user-attachments/assets/ad000931-7ed5-4f67-9d6b-e02fc934f197)
![Screenshot 2025-03-13 084412](https://github.com/user-attachments/assets/e27ef1e2-04e4-43e5-9c09-7832a4d2c951)
![Screenshot 2025-03-13 084423](https://github.com/user-attachments/assets/5dba9dc3-692e-4cca-b7ed-a5dcbea7945c)
![Screenshot 2025-03-13 084441](https://github.com/user-attachments/assets/903a39bc-533b-48ee-b0de-68bca710ed6e)
![Screenshot 2025-03-13 084454](https://github.com/user-attachments/assets/bfa9ec86-dfd9-4091-a4d5-ef205d095d9b)

3.switch:

![Screenshot 2025-03-13 085018](https://github.com/user-attachments/assets/0413fa88-526f-40b3-9cf6-3c93827d4c79)

4.if..else:

![Screenshot 2025-03-13 085632](https://github.com/user-attachments/assets/ac988cdf-96d5-4066-bc95-887a803e3e74)
![Screenshot 2025-03-13 085801](https://github.com/user-attachments/assets/3f26b3cd-e174-4a1d-8bda-d2ab4317121a)

5.for:

![Screenshot 2025-03-13 090341](https://github.com/user-attachments/assets/a7702b9f-2ab9-468a-b2ba-5c4f81f0bd18)


### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


