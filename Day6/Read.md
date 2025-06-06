# 📘 Day 6/30: Modules and Packages

---

## 🧠 Topics Covered

- ✅ What are Modules and Packages?
- ✅ Types of modules: built-in, third-party, and custom
- ✅ Importing modules using `import`, `from`, `as`
- ✅ Useful built-in modules:
  - `math` – mathematical operations
  - `random` – for generating random numbers
  - `string` – useful constants like letters, digits, punctuation
  - `calendar`, `sys`, and more
- ✅ Creating and importing custom modules

---

## 🧪 Challenge Task

### 👉 Task:
**Generate a random 8-character password** using Python’s `random` and `string` modules.

### ✅ Solution:
```python
import random
import string

def password_generator(length=8):
    characters=string.ascii_letters + string.digits +string.punctuation
    password = ''.join(random.choices(characters, k =length))
    return password

print("Random password:", password_generator())
```

### 📢 Please check out the Day 6 post on [LinkedIn!](https://www.linkedin.com/posts/karthiga-lakshmanan_30daysofpython-python-dataanalytics-activity-7336576243984695297-EfkR?utm_source=share&utm_medium=member_desktop&rcm=ACoAACQ2IrAB4tvB8B6NZStCzsJHzXhLsxGLlPI)
