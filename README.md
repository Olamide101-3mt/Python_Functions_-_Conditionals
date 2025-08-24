# Python_Functions_-_Conditionals

## 📌 Overview
This project is a simple Python program that demonstrates the use of **functions, conditionals, and user input**.  
It defines a function called `calculate_discount(price, discount_percent)` which calculates the final price of an item after applying a discount if the discount percentage is **20% or higher**. Otherwise, the original price is returned.

This project highlights how to:
- Work with **functions** in Python
- Use **conditional statements**
- Handle **user input**
- Apply basic **mathematical calculations**

---

## 📝 Function Description
```python
def calculate_discount(price, discount_percent):
    if discount_percent >= 20:
        discount_amount = (discount_percent / 100) * price
        final_price = price - discount_amount
        return final_price
    else:
        return price
