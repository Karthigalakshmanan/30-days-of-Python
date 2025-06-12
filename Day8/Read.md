# 📘 Day 08: Object-Oriented Programming (OOP) — Part 1

**Challenge Series:** 30 Days of Python Learning

---

## 🖊️ Topics Covered

* What is OOP?
* Class and Object Concepts
* Defining Classes and Constructors
* Attributes and Methods
* The `__init__()` Method (Constructor)

---

## 🔍 Overview

Object-Oriented Programming (OOP) is a programming paradigm centered around **objects** and **classes**. Python supports OOP and allows developers to build applications with modular, reusable code using objects that represent real-world entities.

A **class** acts as a blueprint, and an **object** is an instance of that blueprint. Each object can have **attributes** (data) and **methods** (functions/behavior).

---

## 📚 Concepts in Practice

### 🔎 What is a Class?

A class is a user-defined blueprint for creating objects. It defines attributes and methods that will belong to any instance created from it.

### 🔰 The `__init__()` Constructor

Python classes have a special method called `__init__()` that gets executed automatically when an object is created. It is used to initialize object attributes.

---

## 🔧 Challenge:  Create a Car class with attributes and a display method

```python
class Car:
    def __init__(self, brand, model, year, color):
        self.brand = brand
        self.model = model
        self.year = year
        self.color = color

    def display_info(self):
        print(f"Brand: {self.brand}\nModel: {self.model}\nYear: {self.year}\nColor: {self.color}")

# Creating car objects
car1 = Car("Honda", "Civic", 2020, "Blue")
car2 = Car("Tesla", "Model 3", 2023, "White")

# Displaying car information
car1.display_info()
print()  # Adding a blank line between outputs
car2.display_info()
```

---

## 📈 Output:

```
Brand: Honda
Model: Civic
Year: 2020
Color: Blue

Brand: Tesla
Model: Model 3
Year: 2023
Color: White
```

---

## ✅ What I Learned

* Defined a class with attributes and methods
* Created objects from the class
* Learned the purpose of the constructor `__init__()`
* Practiced calling methods and accessing object attributes

---

## 📚 Next Steps (Coming Up in Day 9)

* Inheritance: Create child classes
* Encapsulation: Hiding internal details
* Polymorphism: Same method, different behavior

---

## 🔗 Stay Connected
### 📢 Please check out the Day 8 post on [LinkedIn!](https://www.linkedin.com/posts/karthiga-lakshmanan_python-oop-30daysofpython-activity-7338388370940665856-zcp4?utm_source=share&utm_medium=member_desktop&rcm=ACoAACQ2IrAB4tvB8B6NZStCzsJHzXhLsxGLlPI)

---

**Happy Learning! 🚀**
