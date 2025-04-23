# Regex-Based User Details Collector

A command-line Python tool that collects and validates user information using regular expressions. It ensures that all inputs like name, date of birth, email, mobile number, and gender are in the correct format before saving them to a file.

## 📋 Features

- ✅ Name validation (letters and spaces only)
- 📅 Date of Birth in `DD-MM-YYYY` format
- 📧 Email format check using regex
- 📱 Validates Indian mobile numbers (starting with 7, 8, or 9)
- 🚻 Gender selection: only "Male" or "Female"
- 📝 Appends validated info to `details.txt`

## 🛠️ How to Use

### 🔧 Prerequisites

- Python 3.x

### ▶️ Running the Script

Clone the repository and run:
https://github.com/AshokSai1999/regex-based-user-details-collector

💾 Output Format
After successful input, the details are saved to a file named details.txt like this:
Details: 

Name: Jane Doe
Date of Birth: 01-01-2000
Email Id: jane.doe@example.com
Gender: Female
Mobile Number: 9876543210

📁 Files Included
details.py — Main script

details.txt — Output file created after running the script

📌 Notes
Built using Python’s built-in re module — no external dependencies.

Useful for learning regex validation in CLI apps.
