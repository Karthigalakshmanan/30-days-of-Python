# 🚗 Day 0️⃣9️⃣: Object-Oriented Programming – Part 2   

## 🧠 Topics Covered  
- **Inheritance** – Reuse code from parent classes  
- **Polymorphism** – Override methods to behave differently in subclasses  

---

## 🎯 Challenge  
**Create a `Car` class and extend it into an `ElectricCar` subclass with an extra attribute `battery_capacity`.**  
Override the `display_info()` method to include battery details and demonstrate **polymorphism**.

---

## ✅ Solution  

```python
# Parent class
class Car:
    def __init__(self, brand, model, year, color):
        self.brand = brand
        self.model = model
        self.year = year
        self.color = color

    def display_info(self):
        print(f"Brand: {self.brand}")
        print(f"Model: {self.model}")
        print(f"Year: {self.year}")
        print(f"Color: {self.color}")

# Subclass demonstrating inheritance and polymorphism
class ElectricCar(Car):
    def __init__(self, brand, model, year, color, battery_capacity):
        super().__init__(brand, model, year, color)
        self.battery_capacity = battery_capacity

    def display_info(self):  # Overridden method
        super().display_info()
        print(f"Battery Capacity: {self.battery_capacity} kWh")

# Test the ElectricCar class
ev = ElectricCar("Tesla", "Model S", 2024, "Red", 100)
ev.display_info()
```
