# 📔 Personal Journal Manager

A simple yet powerful **Command-Line Personal Journal Manager** built with Python. This application allows users to securely record daily thoughts, view saved entries, search for specific memories using keywords, and manage journal records efficiently through file handling.

---

## ✨ Features

✅ **Add Journal Entries**

* Write and save personal thoughts, experiences, or notes.
* Entries are automatically timestamped.

✅ **View All Entries**

* Display all saved journal records in a clean format.

✅ **Search Entries**

* Find specific journal entries using keywords.
* Quickly locate memories and notes.

✅ **Delete Entries**

* Remove all journal records with confirmation.
* Helps maintain privacy and manage storage.

✅ **User-Friendly Menu**

* Simple command-line interface with clear navigation.

---

## 🛠️ Technologies Used

* **Python 3**
* **File Handling**

  * Reading files
  * Writing files
  * Searching file content
  * Deleting files
* **Datetime Module**

  * Automatic timestamp generation

---

## 📂 Project Structure

```text
Personal-Journal-Manager/
│
├── journal.txt          # Stores journal entries
├── journal_manager.py   # Main Python program
└── README.md
```

---

## 🚀 Sample Execution

### Main Menu

```text
--- Personal Journal Manager ---
1. Add Entry
2. View Entries
3. Search Entry
4. Delete Entries
5. Exit
```

---

### ➕ Add Entry

```text
Enter choice: 1
Enter your journal entry:
Today was a productive day. I learned about file handling in Python.

Entry added successfully!
```

---

### 📖 View Entries

```text
Your Journal Entries:

[2026-06-05 16:43:27]
Today was a productive day. I learned about file handling in Python.
```

---

### 🔍 Search Entry

```text
Enter keyword to search: productive

[2026-06-05 16:43:27]
Today was a productive day. I learned about file handling in Python.
```

---

### 🗑️ Delete Entries

```text
Delete all entries? (yes/no): yes

All journal entries have been deleted.
```

---

### ⚠️ Error Handling

#### File Not Found

```text
Error: The journal file does not exist.
```

#### Invalid Menu Option

```text
Enter choice: 6

Invalid option!
```

---

### 👋 Exit Program

```text
Enter choice: 5

Thank you for using Personal Journal Manager.
```

## 👨‍💻 Author

Developed as a Python File Handling Project to practice real-world data storage and management concepts.

**Happy Journaling! 📔✨**
