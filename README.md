# OOP_Exercise_Shopping_Cart.ipynb

---

# 🛒 Shopping Cart Lab - OOP Practice

## 📌 Objectives

By completing this lab, you will be able to:

- ✅ Define and call **instance methods**
- ✅ Define and access **instance attributes**
- ✅ Call instance methods **within other methods**
- ✅ Create methods that **calculate statistics** based on attributes
- ✅ Design a **domain model using Object-Oriented Programming**

---

## 🧠 What You'll Be Doing

You will be modifying the `shopping_cart.py` file to build out a basic shopping cart system using Python classes. The focus is on practicing object-oriented programming (OOP) principles such as:

- Class and instance creation
- Working with attributes and methods
- Internal method calls
- Encapsulation of logic
- Simple statistics on cart data

---

## 📂 File Structure

```
project/
├── shopping_cart.py   # Your main Python class to modify
├── notebook.ipynb     # Notebook to experiment with the class
└── README.md          # You’re here!
```

---

## ⚙️ Getting Started

Inside your Jupyter Notebook, set it up to **autoreload** packages so any changes you make to `shopping_cart.py` are reflected immediately.

Example setup in your notebook:

```python
%load_ext autoreload
%autoreload 2

from shopping_cart import ShoppingCart

cart = ShoppingCart()
```

> ⚠️ Note: After making changes to the Python file, be sure to **reinitialize** your class instance in the notebook to see the updates take effect.

---

## 💡 Tips

- Use instance attributes to store items, quantities, and prices.
- Define instance methods for adding/removing items, calculating totals, and printing summaries.
- Test often using your notebook to make sure everything works as expected.
- Think of this cart as a real-world object — what actions would you want it to perform?

---

## 🚀 Goal

By the end of this lab, you should have a functional, class-based shopping cart that can:

- Add items with quantities and prices
- Remove or update items
- Calculate total price and item count
- Print out a summary of the cart's contents

---

