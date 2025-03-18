# 📚 Personal Library Manager

## 📝 Overview

The **Book Collection Manager** is a command-line application that helps users store, manage, and track their reading materials. This program allows users to **add, remove, search, update, and display books**, as well as track reading progress. It also includes **file handling** for saving and loading book data.

---

## 🔥 Features

### 📖 Book Details

Each book in the collection includes the following attributes:

- 📌 **Title** (string)
- ✍️ **Author** (string)
- 📆 **Publication Year** (integer)
- 🏷 **Genre** (string)
- ✅ **Read Status** (boolean: True if read, False if unread)

### 📜 Menu System

The program provides an interactive menu with the following options:
1️⃣ **Add a new book** 🆕
2️⃣ **Remove a book** 🗑️
3️⃣ **Search for books** 🔍
4️⃣ **Update book details** ✏️
5️⃣ **View all books** 📚
6️⃣ **View reading progress** 📊
7️⃣ **Exit** 🚪

---

## 🛠️ Functionality

### ➕ Add a Book

- Prompt the user to enter book details.
- Save the book into the collection.
- 📌 **Example:**
  ```
  Enter book title: The Great Gatsby  
  Enter author: F. Scott Fitzgerald  
  Enter publication year: 1925  
  Enter genre: Fiction  
  Have you read this book? (yes/no): yes  
  Book added successfully! ✅
  ```

### ❌ Remove a Book

- Ask the user for the book title.
- Remove the book from the collection.
- 📌 **Example:**
  ```
  Enter the title of the book to remove: The Great Gatsby  
  Book removed successfully! 🗑️
  ```

### 🔎 Search for a Book

- Users can search by **title** or **author**.
- Display all matching results.
- 📌 **Example:**
  ```
  Search by:  
  1. Title  
  2. Author  
  Enter your choice: 1  
  Enter search term: Gatsby  
  Matching Books:  
  1. The Great Gatsby by F. Scott Fitzgerald (1925) - Fiction - Read ✅
  ```

### ✏️ Update Book Details

- Modify an existing book's information.
- Leave blank to keep existing values.
- 📌 **Example:**
  ```
  Enter the title of the book you want to edit: The Great Gatsby  
  Leave blank to keep existing value.
  New title (The Great Gatsby):  
  New author (F. Scott Fitzgerald):  
  New year (1925):  
  New genre (Fiction): Classic  
  Have you read this book? (yes/no): no  
  Book updated successfully! ✅
  ```

### 📚 View All Books

- Show all books in the collection with details.
- 📌 **Example:**
  ```
  Your Book Collection:  
  1. The Great Gatsby by F. Scott Fitzgerald (1925) - Fiction - Unread ❌
  2. 1984 by George Orwell (1949) - Dystopian - Read ✅
  ```

### 📊 View Reading Progress

- Show **total number of books**.
- Show **percentage of books read**.
- 📌 **Example:**
  ```
  Total books in collection: 2  
  Reading progress: 50.00% 📈
  ```

### 🚀 Exit

- Save the book collection to a file.
- Exit the program safely.
- 📌 **Example:**
  ```
  Library saved to file. Goodbye! 👋
  ```

---

## 💾 File Handling

- 📥 **Save Library to File**: Saves book details to `books_data.json` when exiting.
- 📤 **Load Library from File**: Loads book details when the program starts.

---



---

🚀 **Enjoy managing your personal library!** 📚✨

