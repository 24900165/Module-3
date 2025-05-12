# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
def palindrome(a):
    mid = (len(a)-1)//2    
    start = 0              
    last = len(a)-1
    flag = 0
    while(start <= mid):
        if(a[start]==a[last]):
            print("The entered string is palindrome")
            break
        else:
            flag = 1
            print("The entered string is not palindrome")
            break
                    
string =input()
palindrome(string)
```

## Output
![image](https://github.com/user-attachments/assets/e8584434-8e75-4662-ada4-4d10d622f322)

## Result

The program successfully checks if the string "google" is a palindrome by reversing it and comparing it to the original string.
