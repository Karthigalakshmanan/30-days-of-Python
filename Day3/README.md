# 📘 Day 3: Lists, Tuples, Dictionaries & Sets

## 🧠 Topics Covered

### 🔹 Lists
- A collection of ordered, mutable elements.
- Defined using square brackets `[]`
- Supports slicing, indexing, and various methods (`append()`, `remove()`, etc.)

### 🔸 Tuples
- Immutable ordered collection.
- Defined using parentheses `()`
- Only supports `count()` and `index()` methods.

### 📘 Dictionaries
- Stores data in key-value pairs.
- Defined using curly braces `{}` with syntax: `{"key": value}`
- Useful for mapping and lookups.

### 🟢 Sets
- Unordered collection of unique elements.
- Defined using curly braces: `{"A", "B"}`
- Does not support indexing, removes duplicates automatically.

---

## 🎯 Challenge: Logistics Warehouse Inventory System

### ✅ Problem Statement:
Build an inventory tracker for a logistics warehouse using **list, tuple, dictionary, and set**.

### 💡 Specifications:
- Create a **list** of items.
- Use a **tuple** for fixed item categories.
- Use a **dictionary** for inventory quantities.
- Use a **set** for warehouse zone labels (observe behavior with duplicates).

### 💻 Code:

```python
# Item Catalog (List)
item_list = ["helmets", "gloves", "jackets", "boots", "flashlights", "toolkits"]
print("Preview:", item_list[:3])

# Item Categories (Tuple)
item_categories = ("Electronics", "Furniture", "Safety Gear")
print("Categories:", item_categories)

# Inventory Quantities (Dictionary)
inventory = {
    "helmets": 45,
    "gloves": 120,
    "jackets": 60,
    "flashlights": 30,
    "toolkits": 25,
    "Safetylight": 30
}
inventory.pop("boots")  # Remove out-of-stock item

# Warehouse Zones (Set)
warehouse_zones = {"Zone X", "Zone Y", "Zone Z", "Zone X"}  # Duplicates auto-removed
warehouse_zones.add("Zone A")

# Output
print("\n--- Final Inventory System ---")
print("Item List:", item_list)
print("Item Categories:", item_categories)
print("Inventory Items:")
for item, qty in inventory.items():
    print(f" - {item.title()}: {qty}")
print("Warehouse Zones:", warehouse_zones)

--------------------------------------------------
📢 Please check out the Day 3 post on LinkedIn!
--------------------------------------------------

