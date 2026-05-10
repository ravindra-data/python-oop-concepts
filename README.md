# 🏢 OOP Wrapper — Employee Management System

An interactive menu-driven Python project that demonstrates all core Object-Oriented Programming (OOP) concepts — Inheritance, Encapsulation, and Polymorphism — through a real-world Employee Management System.

---

## 🚀 Features

| Feature | Description |
|---|---|
| Create Employee | Add a basic employee with ID, name, age and salary |
| Create Manager | Add a manager with department (inherits from Employee) |
| Create Developer | Add a developer with programming languages (inherits from Employee) |
| Show Details | Display all employee records with their specific details |
| Encapsulated Data | Salary and Employee ID are private — accessed via getters/setters |

---

## 🧱 OOP Concepts Used

| Concept | How It's Applied |
|---|---|
| **Class & Object** | `employee`, `manager`, `developer` classes |
| **Inheritance** | `manager` and `developer` inherit from `employee` |
| **Encapsulation** | `__salary` and `__employee_id` are private attributes |
| **Polymorphism** | `display()` method overridden in each subclass |
| **`super()`** | Child classes call parent `__init__` and `display()` |

---

## 🛠️ Tech Stack

- **Language:** Python 3.13
- **Concepts:** OOP — Inheritance, Encapsulation, Polymorphism, `super()`, Private Attributes
- **Tool:** Jupyter Notebook

---

## 📁 Project Structure

```
python-oop-concepts/
│
├── OOP_Wrapper.ipynb   # Main Jupyter Notebook
└── README.md           # Project documentation
```

---

## ▶️ How to Run

1. Clone the repository
```bash
git clone https://github.com/ravindra-data/python-oop-concepts.git
```

2. Open the notebook
```bash
jupyter notebook OOP_Wrapper.ipynb
```

3. Run the cell and create employees from the menu!

---

## 📸 Sample Output

```
Python OOP Project :- Employee Management System.

==Employee Management System==
1. Create Employee
2. Create Manager
3. Create Developer
4. Show Details
5. Exit Program

--- Employee Details ---

Employee #1:
Person Created: Name :- Ravindra , Age :- 22
Employee ID: 011
Employee Salary: 35000.0

Employee #2:
Person Created: Name :- RK , Age :- 42
Department of Manager: IT
Employee ID: 001
Employee Salary: 70000.0

Employee #3:
Person Created: Name :- Ravi , Age :- 30
Programming Language: Python, C++, JavaScript
Employee ID: 123
Employee Salary: 50000.0
```

---

## 💡 What I Learned

- Designing a class hierarchy using Inheritance
- Protecting sensitive data using Encapsulation (`__private`)
- Overriding methods using Polymorphism (`display()`)
- Using `super()` to extend parent class behavior
- Building real-world systems using OOP principles

---
