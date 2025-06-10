# 📅 Day 7️⃣: File Handling in Python

## 🗒️ Topics Covered
- Reading files using `open()` and `read()`
- Writing and appending files
- Working with `.txt` files
- Counting word frequencies using `collections.Counter`

---

## 🎯 Challenge

**Task:** Count the frequency of each word in a given text file.

---

## ✅ Code Example

```python
from collections import Counter

# Open the file in read mode
with open("sample.txt", "r") as f:
    # Read content and convert to lowercase
    text = f.read().lower()

    # Split into words
    words = text.split()

    # Count word frequencies
    word_counts = Counter(words)

# Display word frequencies
print("📊 Word Frequencies:")
for word, count in word_counts.items():
    print(f"{word}: {count}")
