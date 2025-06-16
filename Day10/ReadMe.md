# 🚀 Day 10: Exception Handling in Python

---

## 🧠 Topics Covered

- `try` and `except` blocks  
- Handling specific exceptions (`ValueError`, `TypeError`, `ZeroDivisionError`)  
- `finally` clause for cleanup  
- Real-world error-handling examples (like file reading)

---

## 🔧 Task

**Challenge**:  
Read a list of values from a file. If the value is an integer, print it.  
If not, handle it using `try-except` and print a friendly message.

---

```python
# Read and validate integers from a file
try:
    with open("numbers.txt", "r") as file:
        for line in file:
            value = line.strip()
            try:
                res = int(value)
                print(f"It's a number: {res}")
            except ValueError:
                print(f"Not an integer: {value}")
except FileNotFoundError:
    print("The file was not found.")
except Exception as e:
    print(f"Unexpected error: {e}")
finally:
    print("✅ Done reading the file.")
```
### 📢 Please check out the Day 10 post on [LinkedIn!](https://www.linkedin.com/posts/karthiga-lakshmanan_python-dataanalytics-exceptionhandling-activity-7340241174726701057-rokH?utm_source=share&utm_medium=member_desktop&rcm=ACoAACQ2IrAB4tvB8B6NZStCzsJHzXhLsxGLlPI)


