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
**Write a function to compute the sum and average of a list of numbers.**

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

