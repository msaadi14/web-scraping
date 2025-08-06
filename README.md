
# 📘 Reading and Tabulating Web Data with Python

This repository contains a Jupyter Notebook titled `Class 6.ipynb`, which demonstrates how to retrieve and tabulate structured data from web sources using Python. It covers essential data handling techniques using JSON and HTML formats and how to process them using `pandas`.

---

## 🔍 Contents Overview

### 1. 📥 Reading JSON Data
The notebook uses the `pandas.read_json()` method to read structured data from a JSON API (`https://dummyjson.com/products`). JSON is widely used in APIs to transmit data between a server and web application.

- Demonstrates how to import JSON data directly from a URL.
- Shows the structure and layout of the JSON data once it's loaded into a DataFrame.

### 2. 🌐 Reading HTML Table Data
The notebook uses `pandas.read_html()` to scrape and load HTML tables from the W3Schools page:
[https://www.w3schools.com/html/html_tables.asp](https://www.w3schools.com/html/html_tables.asp)

- Shows how many tables exist on the page.
- Demonstrates selecting specific tables by index.
- Applies string transformations to column data (e.g., converting company names to lowercase).

### 3. 📊 Tabulating and Processing Data
After retrieving the data:
- DataFrames are used to tabulate the data.
- The `.apply()` method is used to process and transform columns.
- Demonstrates basic iteration techniques using Python generators and `next()`.

---

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- `pandas` for data handling
- `numpy` for random data generation (minor usage)

---

## 📎 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open the notebook using Jupyter:
   ```bash
   jupyter notebook Class\ 6.ipynb
   ```

---

## 📚 Learning Outcomes

By exploring this notebook, you'll learn:
- How to read JSON and HTML data from the web.
- How to inspect and manipulate tabular data using `pandas`.
- The basics of using Python generators and iterators.
- Fundamental data cleaning techniques (e.g., lowercasing text).

---

## ✍️ Author

**Muhammad Saadi**

---

## 🌟 Feel free to fork or star the repo if you found it useful!
