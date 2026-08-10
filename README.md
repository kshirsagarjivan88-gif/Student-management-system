# 🎓 Student Management System

A simple **Student Management System** built with **Python** and **OpenPyXL**.
The program allows users to add, view, and delete student records, with all data stored in an Excel file.

## 📌 Features

* ➕ Add a new student
* 👀 View all student records
* 🗑️ Delete a student by name
* 💾 Automatically store student data in an Excel file
* 📊 Uses Excel (`student.xlsx`) as a simple database
* 🖥️ Easy-to-use command-line menu

## 🛠️ Technologies Used

* **Python 3**
* **OpenPyXL**
* **Microsoft Excel / `.xlsx`**

## 📂 Project Structure

```text
Student-Management-System/
│
├── student_management.py
├── student.xlsx
└── README.md
```

> `student.xlsx` is automatically created when the program is run if it does not already exist.

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/student-management-system.git
```

### 2. Navigate to the Project Folder

```bash
cd student-management-system
```

### 3. Install Required Library

Install `openpyxl` using pip:

```bash
pip install openpyxl
```

## ▶️ How to Run

Run the Python program using:

```bash
python student_management.py
```

The program will display the following menu:

```text
1. New Student
2. View Data
3. Delete Student
4. Exit
```

Enter the number corresponding to the operation you want to perform.

## 📝 Example

### Add a Student

```text
Enter choice: 1

Enter Name: Rahul
Enter Class: 12
Enter Address: Pune
Enter Contact: 9876543210

Data stored in Excel successfully!
```

### View Student Data

```text
Enter choice: 2

--- Student Data ---

('Name', 'Class', 'Address', 'Contact')
('Rahul', '12', 'Pune', '9876543210')
```

### Delete a Student

```text
Enter choice: 3

Enter Name to delete: Rahul
Student deleted successfully!
```

## 📊 Excel Data Format

Student records are stored in `student.xlsx` with the following columns:

| Name  | Class | Address | Contact    |
| ----- | ----- | ------- | ---------- |
| Rahul | 12    | Pune    | 9876543210 |
| Priya | 11    | Mumbai  | 9123456780 |

## 🔄 How It Works

1. When the program starts, it checks whether `student.xlsx` exists.
2. If the file does not exist, a new Excel workbook is created.
3. The user selects an operation from the menu.
4. New student information is added as a new row.
5. Existing student records can be viewed from the terminal.
6. A student can be deleted by entering their name.
7. All changes are saved directly to the Excel file.

## 🚀 Future Improvements

Some features that can be added in future versions:

* ✏️ Update student information
* 🔍 Search students by name or class
* 🆔 Add a unique Student ID
* 📱 Create a graphical user interface (GUI)
* 🗄️ Replace Excel with a database such as SQLite or MySQL
* 🔐 Add user authentication
* 📋 Add input validation
* 📈 Generate student reports

## ⚠️ Limitations

* Student names are currently used to identify records when deleting.
* If multiple students have the same name, the first matching student will be deleted.
* The system is command-line based.
* Excel is used as the data storage system rather than a dedicated database.

## 👨‍💻 Author

**Jivan Vijay Kshirsagar**


## 📄 License

This project is open-source and available under the **MIT License**.
