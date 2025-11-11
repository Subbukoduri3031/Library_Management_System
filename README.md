# 📚 Library Management System

### 👨‍💻 Group-17
- **Chandan Byanna Venkatesh** – 02167738 – 05  
- **China Subba Rao Koduri** – 02190693 – 17  
- **Abhishek Reddy Surkanti** – 02187989 – 43  

---

## 🧩 Problem Statement
Traditional library systems are often slow, error-prone, and rely on manual recordkeeping.  
This project automates library operations using Python, MySQL, and Tkinter to manage books, users, and transactions efficiently.

---

## ⚙️ Technologies Used
- **Python** → Backend logic  
- **Tkinter** → GUI development  
- **MySQL** → Data storage  
- **PyMySQL** → Database connector  
- **Pillow (PIL)** → Image handling for GUI

---

## 🗄️ Database Design
Tables used:
- **books** → Book ID, Title, Author, Status  
- **issued_books** → Logs book issue details  
- *(optional)* **login** → User credentials  

Database relationships enforce primary and foreign key constraints to maintain integrity.

---

## 🧱 System Architecture
Each module handles a specific operation:
| File | Function |
|------|-----------|
| `main.py` | Launches the GUI and connects all modules |
| `AddBook.py` | Adds new books to the database |
| `ViewBooks.py` | Displays all books and availability |
| `DeleteBook.py` | Removes a book from the system |
| `IssueBook.py` | Issues books and updates status |
| `ReturnBook.py` | Returns books and restores availability |

---

## 💡 Features
- Add, view, delete, issue, and return books  
- Real-time MySQL updates  
- Error handling for invalid operations  
- GUI interface for easy interaction  

---

## 🎯 Benefits
- Reduces manual effort and errors  
- Maintains organized records  
- Immediate reflection of data changes  
- Scalable and easy to extend  

---

## 🔮 Future Enhancements
- User login and registration system  
- Integration with barcodes/RFID  
- Fine calculation for overdue books  
- Due-date notifications  
- Cloud-based MySQL support  

---

## 🧾 Conclusion
The **Library Management System** demonstrates practical use of Python and database design for a real-world scenario.  
It simplifies operations, promotes data consistency, and provides a structured approach to managing library resources.

---

## 📁 Files Included
- `main.py`  
- `AddBook.py`  
- `ViewBooks.py`  
- `DeleteBook.py`  
- `IssueBook.py`  
- `ReturnBook.py`  
- `Library_Management_Report.pdf`
