# 📘 Student Marksheet Management System

## 🎯 Project Overview

This project is a Python-based marksheet management system designed for a lecturer to manage student marks. The program allows lecturers to add, search, edit, and delete student records, calculate final marks, and assign grades based on predefined criteria. The grades are displayed along with a grade distribution table, and all student data can be saved or loaded from an external file for later modifications.

---

## 🧩 Features

✅ **Class-based Design**  
- `PythonMarksheet` class stores:  
  `Student ID`, `Name`, `Test1`, `Assignment1`, `Test2`, `Assignment2`, `Final Exam`, `Total Mark`, `Final Grade`.

✅ **Final Mark Calculation**  
- `Test 1`: 10%  
- `Assignment 1`: 10%  
- `Test 2`: 10%  
- `Assignment 2`: 10%  
- `Final Exam`: 60%

✅ **Grade Assignment Scheme**

| Final Mark | Grade |
|------------|--------|
| x < 50%    | F      |
| 50 ≤ x < 55 | PS2   |
| 55 ≤ x < 60 | PS1   |
| 60 ≤ x < 65 | CR2   |
| 65 ≤ x < 70 | CR1   |
| 70 ≤ x < 75 | DI2   |
| 75 ≤ x < 80 | DI1   |
| 80 ≤ x < 85 | HD2   |
| x ≥ 85     | HD1    |

✅ **Menu Functionalities**
- ➕ Add a new student
- 🔍 Search/edit/delete a student
- 📋 Display all student records
- 💾 Save records to file (e.g., `PythonMarksheet_2022_Semester3.txt`)
- 📂 Load records from file
- 📊 Show grade distribution and histogram

✅ **No Lists or Tuples!**  
- Only **dictionaries** are used to manage multiple student records.

✅ **Robust Error Handling**
- String validation ensures no runtime errors occur.

---

## 🛠️ Technologies Used

- **Language**: Python 3.x  
- **Platform**: Jupyter Notebook (.ipynb)  
- **Libraries**:  
  - `matplotlib` 📊 (for histogram visualization)  
  - `pandas` 🐼 (for grade distribution analysis)

> 💡 *Install required packages with:*
```bash
pip install matplotlib pandas
```

## 📂 Project Structure
PythonMarksheet_Management_System/
│
├── main.ipynb                               # 📓 Main notebook
├── PythonMarksheet_2022_Semester3.txt       # 📄 Sample data file
└── README.md                                # 📝 This file

## 🚀 How to Use

1. **Launch Jupyter Notebook**  
   Open `PythonMarksheet_Management_System.ipynb` in Jupyter.

2. **Follow the Menu**  
   Input options will guide you to add/edit/delete/save/load student marks.

3. **Generate Reports**  
   View grade tables and a histogram after loading or entering data.

4. **Save Data**  
   Save data with custom filenames (e.g., `PythonMarksheet_2022_Semester3.txt`) for future reuse.

---

## 🧠 Author
Cheah Wan Xin



