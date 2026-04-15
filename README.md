# Number-System-Converter-in-C-Programming-Language
A C-based number system converter that converts decimal integers into binary, octal, and hexadecimal numbers. The program has an interactive console menu and supports logic for ASCII-based character conversion. This program is ideal for students learning computer architecture and basic C programming concepts.
Since you are preparing for your BCA first-semester exams and practicing C programming, a well-structured README is a great way to show your understanding of the logic you've implemented.

Here is a professional README.md file tailored for your project. You can copy and paste this directly into a new file named README.md in your GitHub repository.

Number System Converter (C Language)
A lightweight and interactive console application developed in C to perform conversions between different number systems. This tool is designed to help students and developers understand the underlying logic of base conversions.

🚀 Features
Decimal to Binary: Converts base-10 integers to base-2.

Decimal to Octal: Converts base-10 integers to base-8.

Decimal to Hexadecimal: Converts base-10 integers to base-16 (includes A-F logic).

Interactive Menu: User-friendly navigation using keyboard inputs.

Continuous Execution: Option to perform multiple conversions without restarting the program.

🛠️ How It Works
The program uses the successive division method:

It takes a decimal number as input.

It repeatedly divides the number by the target base (2, 8, or 16).

The remainders are converted to characters (using ASCII values like +48 for digits and +55 for Hex letters) and stored in an array.

The array is reversed using strrev() to display the correct result.

📋 Prerequisites
To run this program, you will need a C compiler. Since this code uses conio.h and system("cls"), it is optimized for Windows environments like:

Turbo C++

Dev-C++

Code::Blocks (Windows)

💻 How to Run
Download the Number System converter.c file.

Open it in your preferred C IDE.

Compile the code (usually F9 or the Compile button).

Run the executable and follow the on-screen menu.

📚 Academic Context
This project was developed as part of the BCA Semester 1 curriculum, specifically for the C Programming and Computer Architecture modules.

## 🖼️ Screenshots

### Main Menu
<img src="https://github.com/user-attachments/assets/53305093-3c92-42fd-b875-ec9bded7f404" width="600" alt="Main Menu">

### Conversion Examples
| Decimal to Binary | Decimal to Octal | Decimal to Hexadecimal |
| :---: | :---: | :---: |
| ![Binary](https://github.com/user-attachments/assets/9a1f5c31-3db1-499e-bfb6-f17fa309345f) | ![Octal](https://github.com/user-attachments/assets/e10d4e37-2370-4381-b8d1-be4b0a0e7ae7) | ![Hex](https://github.com/user-attachments/assets/fe17b4fb-258c-4aad-a327-f13d8fc15b58) |
