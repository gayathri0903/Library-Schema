
# 📚 Library Management System — SQL Schema

## 📌 About the Project
This project defines the database design for a Library Management System. It allows libraries to track books, members, borrow/return transactions, and manage staff records. It can be used in schools, universities, or public libraries.

## 🛠 Tools Used
- MySQL Workbench — for designing and executing SQL scripts
- ER Diagram tool — to visually represent relationships between tables

## 📂 What’s Included
- `schema.sql` — Contains the SQL code to create all necessary tables
- `ERD.png` — A diagram showing how the tables are connected
- `README.md` — This file

## 🧾 Tables Overview

- 📗 Books: Information about each book (title, author, ISBN, category, copies available)
- 👤 Members: People who borrow books (name, contact, registration date)
- 📋 Borrowings: Records of which member borrowed which book and when
- 👥 Staff: Library employees who manage the system
- 📬 Returns: Records of returned books and any fines (if applicable)
- 🗃 Categories: Book genres or subjects (e.g., Fiction, Science, History)

## 🔗 How Tables Are Connected

- A member can borrow multiple books → Borrowings table
- Each book can belong to a category → Categories table
- Staff members may be linked to check-ins/returns
- Borrowings and Returns are tied together using BookID and MemberID

## 🚀 How to Use
1. Open MySQL Workbench
2. Run the script inside `schema.sql` to create the database and tables
3. Refer to `ERD.png` for a visual layout of how tables relate

## 🖼 ER Diagram
See the file ERD.png in this folder to understand the table relationships

## ✅ Status
This database is ready to be integrated into a web or desktop-based library management system.
