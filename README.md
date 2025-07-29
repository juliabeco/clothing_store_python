# 🛒 Store Management Project


## 📌 Description

This project simulates a management system for a retail store using **Python** and **Jupyter Notebook**. It is designed to practice fundamental programming concepts such as:

- Lists and dictionaries
- Functions and loops
- Error handling
- User interaction

It implements a basic system for inventory, customers, and sales—ideal as an introductory exercise for learning Python programming.

---

## 📁 Project Structure

```
clothing_store_python/
├── Clothing_store.ipynb # Main notebook with logic and tests
└── README.md            # This documentation file
```

---

## ⚙️ Implemented Features

### 📦 Inventory Management
- Add products
- View complete inventory
- Search products by name
- Update stock
- Delete products
- Calculate total inventory value

### 👤 Customer Management
- Add new customers
- View list of registered customers

### 💰 Sales Management
- Simulate interactive purchases
- Payment processing with validation
- Record purchases in customer history
- View purchase history
- Calculate total sales

---

## 🧱 Data Structures Used

- **Inventory:** `list` of `dict`, each with product name, price, and quantity.
- **Customers:** `dict` with names as keys, and values as `dict` containing email and purchase history.
- **Total Sales:** Numeric accumulator variable.

---

## ▶️ How to Run the Project

1. Clone this repository to your computer:
   ```bash
   git clone https://github.com/yourusername/clothing_store_python.git
   cd clothing_store_python
   ```
2. Open the file `Clothing_store.ipynb` with Jupyter Notebook or JupyterLab.

3. Run the cells step by step to initialize the data structures and test the functions.

4. Feel free to explore, modify, and extend the functionalities as needed!

---

| Tool                | Description                              |
| ------------------- | ---------------------------------------- |
| 🐍 Python 3.7+      | Main programming language                |
| 📓 Jupyter Notebook | Interactive development environment      |
| 🧮 Core structures  | Lists, dictionaries, functions, etc.     |

---

## 🧪 Usage Example

```python
# Add a new product to the inventory
add_product("T-shirt", 15.99, 30)

# Display the current inventory
view_inventory()

# Register a new customer
add_customer("Alice", "alice@email.com")

# Make a purchase
make_purchase()

# View Alice's purchase history
view_customer_purchases("Alice")
```

---

📝 **Notes**
- The system is designed to be run in interactive environments.
- Each function includes explanatory comments for easier understanding.
- Integrated tests and usage examples are included in the notebook.

---

👩‍💻 **Author**

Project by Julia Becaria Coquet  
🌐 [LinkedIn](https://www.linkedin.com/in/juliabecaria/)


![Python](https://img.shields.io/badge/Python-3.7+-blue)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)
![Status](https://img.shields.io/badge/Status-In%20development-yellow)
