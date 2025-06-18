# 🚀 Day 1️⃣2️⃣: Regular Expressions in Python

📂 **Topic**: Working with Regex in Python using the `re` module

---

## 🧠 Concepts Covered

- What are Regular Expressions (Regex)?
- Matching text patterns with `re` module
- Common regex symbols:
  - `\d` → Matches any digit (0–9)
  - `\D` → Matches any non-digit
  - `\w` → Matches alphanumeric characters
  - `.` → Matches any character except newline
  - `+`, `*`, `?` → Repetition qualifiers

---

## 🛠️ Challenge: Gmail Address Validator

```python
import re

# Define the pattern
pattern =r"^[\w\.-]+@[\w\.-]+\.\w{2,3}$"

# User input
email = input("Enter your Gmail address: ")

# Pattern matching
if re.search(pattern, email):
    print("✅ Valid Gmail address")
else:
    print("❌ Invalid Gmail address")
```
### 📢 Please check out the Day 11 post on [LinkedIn!](https://www.linkedin.com/posts/karthiga-lakshmanan_30daysofpython-python-regex-activity-7340930251817947137-CZwK?utm_source=share&utm_medium=member_desktop&rcm=ACoAACQ2IrAB4tvB8B6NZStCzsJHzXhLsxGLlPI)


