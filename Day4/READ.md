# ✅ Day 4/30: Control Flow in Python

## 🗒️ Topics Covered:
- `if-else` statements
- `for` loops
- `while` loops
- `break` and `continue`

## 🎯 Challenge: Prime Number Checker

Write a program to check whether a number entered by the user is a prime number.

### 💡 Python Code:
```python
print(f" Check if a user-entered number is prime")

# To take input from the user
num = int(input("Enter a number "))

if num == 0 or num == 1:
    print(num, "is not a prime number")
elif num > 1:
   # check for factors
   for i in range(2,num):
       if (num % i) == 0:
           print(num,"is not a prime number")
           break
   else:
       print(num,"is a prime number")
else:
   print(num,"is not a prime number")
```
###📢 Please check out the Day 3 post on [LinkedIn!](https://www.linkedin.com/posts/karthiga-lakshmanan_day4of30-python-30daysofpython-activity-7335486387850289152-SkcL?utm_source=share&utm_medium=member_desktop&rcm=ACoAACQ2IrAB4tvB8B6NZStCzsJHzXhLsxGLlPI)
