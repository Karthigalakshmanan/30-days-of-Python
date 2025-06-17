# 📅 Day 11: Working with Dates and Times

 -Datetime module, formatting, time differences

---

## 🗒️ Topics Covered

- Using Python’s built-in `datetime` module
- Converting strings to `datetime` objects using `strptime()`
- Calculating date differences
- Formatting output with `f-strings` and `.date()`

---

## 🧪 Challenge

**Task:**  
Write a program that calculates how many days have passed between two dates.  
*Example use case:* Calculate how many days you’ve been alive from your birthdate until today!

---

## ✅ Solution

```python
import datetime
startdate=input("Enter the start date (YYYY-MM-DD):")
enddate=input("Enter the end date (YYYY-MM-DD):")

try:

 d1=datetime.datetime.strptime(startdate, "%d-%m-%Y")
 d2=datetime.datetime.strptime(enddate, "%d-%m-%Y")

 diff =abs((d2-d1).days)


 print(f"days between {d1.date()} and {d2.date()} : {diff} days")

except Exception as e:
 print(f"Unexpected error: {e}")

finally:    
  print("dates calculated")

```
