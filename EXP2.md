# Ex.No: 2   Matrix Multiplication 

### DATE:20.03.2025                                                                            
### REGISTER NUMBER : 212224230106

### AIM: 
Write a python program for matrix multiplication and inspect for failures.
 
### Algorithm:

1. Start the program.
2. Create empty list formatrix1, matrix2 and result.
3. Get the rows and columns count from the user.
4. Get the values of two matrix.
5. Perform matrix multiplication and store the answer in result.
6. Stop the program.
   
### Program:
```
r1, c1 = input("Enter row and column count in matrix 1: ").split()
r2, c2 = input("Enter row and column count in matrix 2: ").split()

matrix1 = []
matrix2 = []
result = []

if r1.isnumeric() and c1.isnumeric() and r2.isnumeric() and c2.isnumeric():
    r1 = int(r1)
    c1 = int(c1)
    r2 = int(r2)
    c2 = int(c2)

    if c1 != r2:
        print("Matrix multiplication not possible")
    elif max(r1, c1, r2, c2) > 20 or min(r1, c1, r2, c2) == 0:
        print("Matrix multiplication not possible")
    else:
        for i in range(r1):
            a = []
            for j in range(c1):
                a.append(int(input("<-- ")))
            matrix1.append(a)

        for i in range(r2):
            a = []
            for j in range(c2):
                a.append(int(input("<-- ")))
            matrix2.append(a)

        for i in range(r1):
            inter = []
            for j in range(c2):
                sum = 0
                for k in range(r2):
                    sum += matrix1[i][k] * matrix2[k][j]
                inter.append(sum)
            result.append(inter)

        for i in range(r1):
            for j in range(c2):
                print(result[i][j], end=" ")
            print()

else:
    print("Enter a valid number")
```
### Output:

![Screenshot 2025-03-20 091029](https://github.com/user-attachments/assets/d872e67a-accc-4f16-954f-ae6bdeacedc1)

![Screenshot 2025-03-20 091143](https://github.com/user-attachments/assets/2e9a7421-cfc8-42b0-a2c5-76956cd5b5b6)

![Screenshot 2025-03-20 091318](https://github.com/user-attachments/assets/888f93cd-c0dc-49e7-8279-329a19401d49)

![Screenshot 2025-03-20 091358](https://github.com/user-attachments/assets/885cb16e-6ccd-49e6-8aa0-2f1be2df2ffe)

![Screenshot 2025-03-20 091432](https://github.com/user-attachments/assets/c547ad22-e11e-4aad-8c34-c0dd963344e6)

![Screenshot 2025-03-20 092008](https://github.com/user-attachments/assets/b8f04907-0c53-40c8-b658-7f050a116638)

![Screenshot 2025-03-20 092018](https://github.com/user-attachments/assets/6911e0f0-9c82-4618-8a3c-b016846ebe7e)

![Screenshot 2025-03-20 092144](https://github.com/user-attachments/assets/eeb84aa6-d314-4c80-b1dd-08554da83d64)

![Screenshot 2025-03-20 092152](https://github.com/user-attachments/assets/3c4c514b-f2f5-4973-9c8c-b3865abcf123)

![Screenshot 2025-03-20 092234](https://github.com/user-attachments/assets/18ad93d1-0077-4655-825e-f774c445932e)

![Screenshot 2025-03-20 092332](https://github.com/user-attachments/assets/f32495f3-9dc8-4db6-992b-221d9cc32655)

![Screenshot 2025-03-20 092427](https://github.com/user-attachments/assets/eb4496c4-6278-4cb3-a517-adef8cdb26d0)

![Screenshot 2025-03-20 092435](https://github.com/user-attachments/assets/eed7ea37-d818-475f-9e82-3b45729c4f4d)

### Result:
Thus, the python program for matrix multiplication is implemented and the causes for its failure is introspected successfully.

