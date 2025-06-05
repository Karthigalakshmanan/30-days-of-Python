# 📘 Day 5/30 – Python Functions & Lambda

Welcome to Day 5 of my **#30DaysOfPython** learning challenge by *Indian Data Club*.  
Today’s focus was all about mastering **functions**, their types, and how to write cleaner, reusable code in Python.

---

## 🗒️ Topics Covered

- ✅ Defining functions using `def`
- ✅ Function parameters & return values
- ✅ Global vs. Local variables
- ✅ Default arguments
- ✅ Docstrings (`"""Describe function purpose"""`)
- ✅ Lambda (anonymous) functions
- ✅ First-class functions in Python

---

## 📌 Key Concepts

> ✔️ **Functions in Python are first-class objects**  
They can be:
- Assigned to variables
- Passed as arguments
- Returned from other functions

---

## 🎯 Challenge

### 👉 Task:
** Write a function that calculates the sum and average of a list of numbers using both a regular function and a lambda expression.**

### ✅ Solution:
```python
def sum_avg(inp):
    total = sum(inp)
    avg = total / len(inp)
    return total, avg

numbers = [12, 45, 78, 34, 23, 89, 56]
total, average = sum_avg(numbers)

print("✅ The sum and average of a list of numbers:")
print(f"Sum: {total}")
print(f"Average: {average:.2f}")
```


```python
print (F"The sum and average of a list of numbers.")

def sum_avg(inp):
    total=0
    for i in inp:
        total=total+i
    avg =total / len (inp)
    return total, avg
    
  
numbers = [12, 45, 78, 34, 23, 89, 56]

total,average=sum_avg(numbers)
print (f"Sum of numbers:{total}")
print (f"Averageof numbers:{average:.2f}")
```

###📢 Please check out the Day 4 post on [LinkedIn!](https://www.linkedin.com/posts/karthiga-lakshmanan_30daysofpython-python-dataanalytics-activity-7336217186832719874-9roU?utm_source=share&utm_medium=member_desktop&rcm=ACoAACQ2IrAB4tvB8B6NZStCzsJHzXhLsxGLlPI)
