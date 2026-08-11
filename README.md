#  Student Management System

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)
[![Database](https://img.shields.io/badge/database-SQL-lightgrey.svg)](https://www.sqlite.org/)

A lightweight, beginner-friendly desktop application designed to streamline student record administration, course assignments, and grade tracking.

---

##  Project Overview

Maintaining student records manually or using bloated spreadsheets often leads to errors and lost data. The **Student Management System** provides an intuitive Interface to add, update, search, and delete student information seamlessly in real time.

---

##  Objectives

*  **Simplicity**: Offer a clean, no-fuss interface for fast record entry.
*  **Quick Retrieval**: Enable rapid searching by Student ID or Name.
*  **Data Integrity**: Store data securely using a local database backend.

---

##  Key Features

-  **Student Registration**: Add new students with personal and contact details.
-  **Course Enrollment**: Assign subjects/courses to individual students.
-  **Smart Search**: Filter student records by ID, Department, or Enrollment Year.
-  **Grade & GPA Tracker**: Calculate and update student grades automatically.
-  **Record Management**: Safely edit or remove outdated entries.

---

##  Technologies Used

| Layer | Technology | Description |
| :--- | :--- | :--- |
| **Language** | Python 3.10+ | Core application code and logic |
| **Database** | SQL |  database for storing records locally |
| **Data Export** | Pandas | CSV / Excel export functionality |

---

##  Folder Structure

```text
student-management-system/
├── assets/                  # Icons, images, and logos
│   └── logo.png
├── database/                # Local SQLite database files
│   └── students.db
├── src/                     # Core application source code
│   ├── components/          # GUI windows and frames
│   ├── models/              # Database models and queries
│   ├── utils/               # Helper functions (export, validation)
│   └── app.py               # Main application entry point
├── .gitignore
├── requirements.txt         # Project dependencies
└── README.md
