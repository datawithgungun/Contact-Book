# Contact-Book

---

# 📇 Contact Book CLI using MySQL

This is a simple **Command-Line Contact Book** application built using **Python** and **MySQL**. It allows users to **add**, **view**, **search**, and **delete** contacts stored in a MySQL database.

---

## 🚀 Features

* 🔐 Connects securely to a local MySQL database
* 🧾 Add new contacts (name, phone, email)
* 📋 Display all saved contacts
* 🔍 Search for a contact by name
* ❌ Delete a contact
* 🧭 Easy-to-use command-line menu interface

---

## 🛠️ Technologies Used

* Python 3
* MySQL
* `mysql-connector-python` library

---

## 📁 Database Schema

Make sure you have a MySQL database named `contact_book` with a table called `contacts` using the following schema:

```sql
CREATE DATABASE contact_book;

USE contact_book;

CREATE TABLE contacts (
    name VARCHAR(255),
    phone VARCHAR(20),
    email VARCHAR(255)
);
```

---

## 🔧 Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/contact-book-cli.git
   cd contact-book-cli
   ```

2. **Install required library**

   ```bash
   pip install mysql-connector-python
   ```

3. **Update your MySQL credentials**
   In the `get_connection()` function of the script, replace:

   ```python
   host="localhost", database="contact_book", user="root", password="2002"
   ```

   with your own MySQL connection details.

4. **Run the program**

   ```bash
   python contact_book.py
   ```

---

## 📷 Example Usage

```
1. Add Contact
2. Display Contact
3. Search Contact
4. Delete Contact
5. Exit
Enter choice:
```

---

## 🙋‍♂️ Author

* **Gungun Anant Chavan**
* [LinkedIn](https://www.linkedin.com/in/gungun-chavan-822440259/)
* [GitHub](https://github.com/Gungunachavan)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

