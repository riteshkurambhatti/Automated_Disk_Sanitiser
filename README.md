# Automated Disk Sanitiser (Duplicate File Removal System)

A Python automation tool that scans directories, detects duplicate files using MD5 checksum hashing, and safely removes redundant copies to optimize disk space.

This project demonstrates real-world system programming concepts such as file system traversal, binary file handling, hashing, dictionary-based data organization, and safe automation practices.

---

## 📌 Project Overview

Over time, systems accumulate duplicate files due to downloads, backups, file sharing, and poor file management. These duplicates waste valuable disk space and reduce system efficiency.

The **Automated Disk Sanitiser** is a command-line Python utility that:

- Traverses the entire file system using `os.walk()`
- Reads files in binary mode
- Generates MD5 checksums for each file
- Detects duplicate files using hash comparison
- Safely deletes redundant copies
- Helps maintain disk hygiene and optimize storage

This type of tool is commonly used in **servers**, **backup systems**, and **enterprise storage management**.

---

## 🎯 Learning Objectives Demonstrated

This project combines multiple important automation and system programming concepts:

- File system traversal
- Directory scanning using `os.walk()`
- File handling in binary mode
- Checksum generation using MD5 hashing
- Duplicate file detection logic
- Dictionary-based data organization
- Safe file deletion
- Disk space optimization
- Writing production-style system utilities

---

## 🚀 Features

✔️ Recursively scans folders and subfolders  
✔️ Detects duplicates using MD5 hash comparison  
✔️ Uses efficient dictionary mapping for tracking files  
✔️ Safe deletion of duplicate files  
✔️ Improves disk space usage automatically  
✔️ Simple command-line interface  

---

## 🛠️ Technologies Used

- Python 3
- `os` module for directory traversal
- `hashlib` for MD5 hashing
- File handling in binary mode
- Dictionaries for data storage

---

▶️ Usage

Run the script:

python Automated_Disk_Sanitiser.py

Provide the directory path when prompted. The script will:

1.Scan all files

2.Generate MD5 hashes

3.Identify duplicate files

4.Remove duplicates safely

---

⚙️ How It Works

1.Directory Traversal
The script walks through directories using os.walk().

2.Binary File Reading
Each file is opened in binary mode to ensure accurate hashing.

3.MD5 Hash Generation
A unique MD5 hash is generated for every file.

4.Duplicate Detection
Files with identical hashes are considered duplicates.

5.Dictionary Storage
Hashes are stored as keys and file paths as values.

6.Safe Deletion
Only duplicate copies are deleted, preserving one original file.

---

⚠️ Important Note

Ensure you provide the correct directory path.

Deleted files cannot be recovered.

Recommended to test on a sample folder first.

---

💡 Real-World Applications

Server storage maintenance

Backup system cleanup

Personal system disk optimization

Enterprise file management

---

🙌 Author
Ritesh Kurambhatti
