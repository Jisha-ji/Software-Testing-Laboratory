# Ex.No: 6 To check whether the string is Palindrome and generate test cases.

### DATE: 21-04-2025                                                                           
### REGISTER NUMBER : 212224230106
### AIM: 
Write a Python program to check whether the string is Palindrome and generate test cases. 
### Algorithm:
1. Start
2. Get an input from the user by prompting 
3. Run a loop form 0 to len/2.
4. Check if the characters are the same both from the start and the end till len/2. 
5. If it is, return the result that it is a palindrome.
6. Else, return that it is not a palindrome. 
7. Stop the program.
### Program:
```
def Palindrome(string):
    for i in range(0, int(len(string)/2)): 
        if(string[i] != string[len(string)-i-1]): 
            return False 
    return True 

s = input("Enter a string: ") 

c = 1 
for i in s: 
    if not(i.isalpha()): 
        c = 0 
        break # Added to stop checking once an invalid character is found

if(c == 0): 
    print("Enter a valid string") 
else:
    answer = Palindrome(s)
    if(answer == True): 
        print("The given string is a palindrome") 
    else: 
        print("The given string is not a palindrome")

```
### Output:

![Screenshot 2025-04-10 085334](https://github.com/user-attachments/assets/eb3e4289-68e1-41c8-b45b-514e1023cbbd)
![Screenshot 2025-04-10 085359](https://github.com/user-attachments/assets/51fcf531-bb53-4ecf-a4ee-10bfecef91b8)
![Screenshot 2025-04-10 085448](https://github.com/user-attachments/assets/ea9df2f7-4cf8-4be8-acc0-6aad7b6de3c8)
![Screenshot 2025-04-10 085738](https://github.com/user-attachments/assets/64721e00-06d0-48c0-95e1-d2c4a199dd37)
![Screenshot 2025-04-10 085959](https://github.com/user-attachments/assets/1c77045f-2b7a-421f-baea-a852a4ffdfe1)
![Screenshot 2025-04-10 090134](https://github.com/user-attachments/assets/367f2641-3223-4e7c-90ff-58b1403db9a2)
![Screenshot 2025-04-10 090240](https://github.com/user-attachments/assets/bbdc1d88-3543-481f-8a35-4eceac840f2f)
![Screenshot 2025-04-10 090316](https://github.com/user-attachments/assets/451dc5fa-e0a9-4d32-a377-d40db3a8d99f)
![Screenshot 2025-04-10 090439](https://github.com/user-attachments/assets/085881ac-8347-494a-87ab-de0a4b624d37)
![Screenshot 2025-04-10 090643](https://github.com/user-attachments/assets/f70dd2a9-47fe-4ff8-bff5-b78a55dfebb9)

### Result:
Thus, a program to check palindrome has been written and test cases have been written and verified successfully.
