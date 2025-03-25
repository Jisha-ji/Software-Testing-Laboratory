# Ex.No: 3 To check the number is prime or not and inspect for failures.
 
### DATE: 27.03.2025                                                                           
### REGISTER NUMBER : 212224230106
### AIM: 
Write a python program to check the number is prime or not and inspect for failures.
 
### Algorithm:
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
6. If the number is divisible by the current iteration value, return "Not Prime".
7. If the number is not divisible by any value from 2 to the square root, return "Prime".
8. Stop the program.

### Program:

```
num = input()
flag = 0

if num.isnumeric():
    z = int(num)
    if z == 2:
        flag = 1
    if z > 2:
        for i in range(2, z // 2):
            if z % i == 0:
                flag = 0
                break
        else:
            flag = 1
    if flag == 1:
        print("Prime Number")
    else:
        print("Not a Prime Number")
else:
    print("Enter a Positive Number")

```

### Output:

![Screenshot 2025-03-25 104656](https://github.com/user-attachments/assets/47bde981-6cdc-4a51-93af-b03b8faf3439)
![Screenshot 2025-03-25 104739](https://github.com/user-attachments/assets/391ef320-c9ac-4f48-923f-3a0a1fada168)
![Screenshot 2025-03-25 104842](https://github.com/user-attachments/assets/86d62e82-9d6c-45b9-8e42-42591090e667)
![Screenshot 2025-03-25 104925](https://github.com/user-attachments/assets/192348ba-be11-4772-abb3-6c2815238d6b)
![Screenshot 2025-03-25 105004](https://github.com/user-attachments/assets/dcdcda4b-e173-4893-aca4-a61c586e735f)
![Screenshot 2025-03-25 105040](https://github.com/user-attachments/assets/1def7ec3-bae3-475a-9a2b-7894e971966a)
![Screenshot 2025-03-25 105128](https://github.com/user-attachments/assets/cd2dde23-3654-4eb2-9504-e67509fbf5ef)
![Screenshot 2025-03-25 105158](https://github.com/user-attachments/assets/d689ad55-71c9-48bc-a682-ba4a98f3516f)
![Screenshot 2025-03-25 105332](https://github.com/user-attachments/assets/7051486c-bec0-4508-b8a1-7dfc30c5e058)
![Screenshot 2025-03-25 105227](https://github.com/user-attachments/assets/8e10ff52-715a-48ea-af3b-17203c9d95a3)


### Result:
Thus, the python program to check the number is prime or not is implemented and the output is verified successfully.
