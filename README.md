# 🛒 Grocery Store Management System

This is a command-line grocery store management system written in Python using Object-Oriented Programming (OOP).  
The project was created as part of a college assignment.

## 👨‍💻 Author
**Majd Bisher**  
📧 MajdBisher85@gmail.com

## 📦 Features
- Add new items: `Milk` and `Pepper`
- View all items in the store
- Place items on a shelf
- Calculate total and average price of items
- Remove items by ID
- Interactive terminal interface with input validation

## 🧱 OOP Concepts Used
- Abstract base class: `Item`
- Inheritance: `Milk`, `Pepper`
- Polymorphism: Common method interface for all items
- Encapsulation: Item data is protected and accessed through methods

## 🗂️ Project Structure
```
main.py         # Main CLI program
item.py         # Abstract base class
milk.py         # Milk class
pepper.py       # Pepper class
```

## 🚀 How to Run
1. Make sure all `.py` files are in the same folder.
2. Open a terminal in that folder.
3. Run the program using:
```bash
python main.py
```

4. Available commands:
- `add_milk`
- `add_pepper`
- `print`
- `put_on_shelf`
- `total_value`
- `avg_value`
- `remove`
- `exit`

---

This program is for educational purposes and demonstrates good design using Python OOP.
