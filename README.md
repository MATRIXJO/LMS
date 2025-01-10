# Library Management System (LMS)

## 📚 Overview
The **Library Management System (LMS)** is an open-source project aimed at streamlining library operations by providing functionalities such as adding/removing books, searching and borrowing books, managing user records, and handling overdue notifications. This collaborative project promotes experience in open-source development and teamwork through GitHub.

---

## 🎯 Objectives
- Facilitate the management of library operations.
- Provide an intuitive interface for librarians and users.
- Enable students to gain hands-on experience in collaborative development using GitHub.

---

## ⚙️ Features
### For Librarians:
1. **Add and Remove Books**: Add, delete, or update book records.
2. **Manage User Records**: Track registered users and their borrowed books.
3. **Issue Management**: Handle overdue books and notify users.

### For Users:
1. **Search Books**: Search by title, author, or ISBN.
2. **Borrow Books**: Borrow books if available.
3. **Return Books**: Update records upon returning books.

---

## 🛠️ Technologies Used
- **Backend**: PHP
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript
- **Version Control**: GitHub for collaboration

---

## 🚀 Getting Started

### 1. Prerequisites
- Install **PHP** (v7.4 or higher).
- Install **MySQL** (v8.0 or higher).
- Install **Git** for version control.

### 2. Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/MATRIXJO/LMS.git
2. Navigate to the project directory:
   ```bash
   cd LMS
3. Configure the database:
- Import the ```lms_database.sql``` file into MySQL.
- Update the database connection settings in config.php. 
4. Start the PHP server:
   ```bash
   php -S localhost:8000
5. Open the application in your browser at http://localhost:8000.

---


## 📂 Project Structure

```plaintext
📁 LMS/
├── 📁 Admin/
    ├── 📁 assets/
         ├── 📁 css/         
         ├── 📁 fonts/
         ├── 📁 img/
         ├── 📁 js          # JavaScript files
    ├── 📁 bookingimg/
    ├── 📁 include/              
         ├── 📄 config.php  # Backend configuration php scripts
    ├── 📄 php files        # Admin related backend PHP scripts
├── 📁 assets/
    ├── 📁 css/
    ├── 📁 fonts/
    ├── 📁 img/
    ├── 📁 js               # JavaScript files
├── 📁 includes/
    ├── 📄 config.php       # Backend PHP scripts   
├── 📁 sql/                 # Database files
├── 📄 Studentid.txt        # Student id's
├── 📄 README.md            # Project documentation
├── 📄 php files            # All php files



