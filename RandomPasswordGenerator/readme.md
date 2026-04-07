# 🔐 Password Generator (Python)

A simple and secure **Password Generator** built using Python. This program allows users to generate random passwords based on their preferences such as length and character types.

---

## 📌 Features

- Generate passwords of any desired length  
- Option to include:  
  - ✅ Letters (A–Z, a–z)  
  - ✅ Numbers (0–9)  
  - ✅ Symbols (!, @, #, etc.)  
- Input validation with error handling  
- Easy-to-use command-line interface  

---

## 🛠️ Technologies Used

- Python  
- Built-in modules:  
  - `random`  
  - `string`  
- Visual Studio Code (for development and execution)  

---

## 🚀 How to Run

1. Install Python (if not already installed)  
2. Download or clone this repository  
3. Open the project folder in Visual Studio Code  
4. Open the terminal in VS Code (`Ctrl + ~`)  
5. Run the script:

```bash
python password_generator.py

Example Usage
=== Password Generator ===
Enter password length: 10
Include letters? (y/n): y
Include numbers? (y/n): y
Include symbols? (y/n): n

Generated Password: aK9xP2LmQ1

Error Handling

The program displays appropriate messages if:

Password length is less than or equal to 0
Invalid input is entered (non-numeric value)
No character type is selected

password-generator/
│
├── password_generator.py
└── README.md

🎯 Future Improvements
Add GUI (using Tkinter or PyQt)
Option to copy password to clipboard
Password strength checker
Secure password storage
📜 License

This project is open-source and free to use.
