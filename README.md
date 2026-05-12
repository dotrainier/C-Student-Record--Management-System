# C++ Student Record Management System

A comprehensive desktop application for managing student academic records and grades, built with C++ using object-oriented programming principles.

## Screenshot

![Student Record Management System](https://user-images.githubusercontent.com/121743449/213120919-2f29463b-a099-46d3-b339-559cd8f4d3bc.png)

## Features

- **Student Record Management**: Add, view, edit, and delete student records
- **Grade Tracking**: Manage grades across multiple courses including:
  - Kontekstwalisadong Komunikasyon sa Filipino (KomFil)
  - Art Appreciation
  - Computer System Servicing
  - Data Structures
  - Introduction to Computing
  - C++ Programming
  - Mathematics in the Modern World
  - Understanding the Self
  - Physical Fitness
  - Civic Welfare Training Service
- **GPA Calculation**: Automatic grade average computation
- **Grade Remarks**: Automatic remarks based on grade performance
- **File Persistence**: All records stored in local file system
- **User-Friendly Interface**: Interactive console-based menu system

## Technology Stack

- **Language**: C++
- **Standard Library**:
  - `<fstream>` - File I/O operations
  - `<iostream>` - Console input/output
  - `<iomanip>` - Output formatting
  - `<string>` - String manipulation
- **Platform**: Windows (uses Windows-specific features)

## Prerequisites

- C++ Compiler (GCC, MSVC, or Clang)
- Windows OS
- Basic command-line knowledge

## Getting Started

### Compilation

```bash
g++ MyRecordBook.cpp -o MyRecordBook.exe
```

### Running the Application

```bash
./MyRecordBook.exe
```

## Usage

1. **Run the application** to launch the main menu
2. **Select an option**:
   - Add new student record
   - View all records
   - Search for a student
   - Edit student information
   - Delete a record
3. **Follow the prompts** to enter student details and grades
4. Records are automatically saved to `file.txt`

## System Requirements

- **OS**: Windows
- **Memory**: Minimal (~5MB)
- **Storage**: Depends on number of records

## File Structure

- `MyRecordBook.cpp` - Main application source code
- `file.txt` - Data storage file (auto-generated)
- `emoji.txt` - Emoji resources for UI

## Project Details

This project demonstrates:

- Object-oriented programming with C++ classes
- File I/O operations using fstream
- User input validation and error handling
- Data persistence and management
- Menu-driven application design

---

**Status**: Active | **Last Updated**: 2024
