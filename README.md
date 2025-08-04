# 🧮 BMI Calculator – Mini Project

This is a simple **BMI (Body Mass Index) Calculator** built using Python's OOP concepts. It calculates a person's BMI based on their height and weight, and categorizes them as underweight, normal weight, overweight, or obese.

---

## 🚀 Features

- Takes **user details** (name, weight in kg, height in meters)
- Calculates **BMI**
- Classifies BMI into:
  - Underweight
  - Normal weight
  - Overweight
  - Obese
- Uses **Object-Oriented Programming (OOP)** concepts:
  - Class
  - Methods
  - Constructor (`__init__`)

---

## 🛠️ How It Works

The script contains a `BMICalculator` class with the following methods:

- `BMIcal()`: Calculates BMI = weight / (height)^2
- `yourCategory()`: Determines BMI category
- `info()`: Displays all the user information with BMI and category

---

## 📌 Sample Output

```python
Name:  Saksham
Weight in kg:  55
Height:  1.75
BMI:  17.96
Category:  Underweight

person = BMICalculator("Your Name", weight_in_kg, height_in_meters)
person.info()
```
---

## 🌐 Flask Web Version
If you're using the Flask-based web version of the BMI Calculator:

## 🔧 Setup & Run
Install Flask (if not already installed):

```bash
pip install flask
```
Run the Flask app (example: bmi_flask.py):

```bash
python bmi_flask.py
```
Open your browser and visit:
```cpp
http://127.0.0.1:5000/
```

---

# 📜 License
This project is licensed under the MIT License.

---

# 🙌 Acknowledgments
Created using Python and OOP concepts as a part of learning Data Science

---

# Author
Developed by Saksham Sharma

