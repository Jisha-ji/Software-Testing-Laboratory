### Ex.No:5 Binary Search
### Date: 27.03.2025
### Register Number: 212224230106

### AIM: 
Write a python program for Binary Search and inspect for failures.

### Algorithm:

1.Start the program.

2.Get the list from the user

3.Get the element to be searched

4.Compare the mid element with the key, if same return the index

5.If key is greater, search it in the right side, else search it in the left side.

6.If not found return -1

7.Stop the program.

### Program:

```
def binary_search(arr, x): 
    low = 0 
    high = len(arr) - 1 
    mid = 0 
    while low <= high: 
        mid = (high + low) // 2 
        if arr[mid] < x: 
            low = mid + 1 
        elif arr[mid] > x: 
            high = mid - 1 
        else: 
            return mid

arr = [2, 3, 4, 10, 40] 
x = input("Enter the element to be searched: ")

try: 
    x = int(x) 
    result = binary_search(arr, x) 
    if result != -1: 
        print("Element is present at index", str(result)) 
    else: 
        print("Element is not present in array") 
except: 
    print("Enter a valid input!")
```

### Output:

![Screenshot 2025-03-27 090812](https://github.com/user-attachments/assets/060d0ade-f4e9-45a3-bd3e-468c0237295b)

![Screenshot 2025-03-27 090853](https://github.com/user-attachments/assets/ad7e54fd-9957-416a-ab66-2d8d4b74860e)

![Screenshot 2025-03-27 090916](https://github.com/user-attachments/assets/4f4b591d-a99a-4512-b72a-16f8bc7571ff)

![Screenshot 2025-03-27 090959](https://github.com/user-attachments/assets/c71fa240-05b3-4f89-8071-b4baed9880f8)

![Screenshot 2025-03-27 091026](https://github.com/user-attachments/assets/ce8c5f67-537d-43e7-9084-2f902add725e)

![Screenshot 2025-03-27 091108](https://github.com/user-attachments/assets/8cbee7cc-cd29-424d-a6c3-26f0f005b572)

![Screenshot 2025-03-27 091212](https://github.com/user-attachments/assets/f12512ab-017f-4e9c-877b-9dfa757474c3)

![Screenshot 2025-03-27 091238](https://github.com/user-attachments/assets/c90d7396-1d96-422d-8c51-11479a9bcc7f)

![Screenshot 2025-03-27 091308](https://github.com/user-attachments/assets/441922c1-9d2f-4cac-8d58-23b8888d3205)

![Screenshot 2025-03-27 091543](https://github.com/user-attachments/assets/54fd3628-90c8-400d-bd6a-fc7569c61989)


### Result:
Thus, the python program for Binary Search implemented and the output is verified successfully.

