# File Encryption and Decryption System

This project is a secure file encryption and decryption system implemented in C++. It uses the **Caesar Cipher algorithm** to encrypt and decrypt text files, ensuring data confidentiality and integrity. The program provides a simple command-line interface for users to encrypt or decrypt files with ease.

## Features
- Encrypt text files using the Caesar Cipher algorithm.
- Decrypt encrypted files back to their original content.
- Lightweight and easy-to-use command-line interface.
- Ensures data security and integrity.

## Prerequisites
- A C++ compiler (e.g., `g++`).
- Basic knowledge of command-line operations.

## How to Run the Program

### 1. Compile the Program
Open a terminal and navigate to the project directory. Run the following command to compile the code:  
```bash
g++ main.cpp encryption.cpp -o run
```
### 2. Run the Program
After compiling, execute the program using:

bash
Copy
./run
### 3. Follow the Prompts
Enter the file name (e.g., sample.txt).

Choose encryption (e) or decryption (d).

Example:

Copy
Enter the filename: sample.txt
Encrypt (e) or Decrypt (d)? e
File encrypted successfully.

### 4. Check the Output
If you chose encryption, the encrypted file will be saved as encrypted_sample.txt.

If you chose decryption, the decrypted file will be saved as decrypted_sample.txt.

Example Workflow
Place a text file (e.g., sample.txt) in the project directory.

Encrypt the file by running the program and selecting e.

To decrypt, run the program again on the encrypted file and select d.

Files in the Repository
main.cpp: Contains the main program logic and user interface.

encryption.cpp: Implements the Caesar Cipher algorithm for encryption and decryption.

README.md: This file, providing an overview and instructions for the project.

### Notes
Ensure the input file exists in the same directory as the executable.

The program only works with text files (.txt).

### License
This project is open-source and available under the MIT License. Feel free to modify and distribute it as needed.

### Copy

This is the proper Markdown format for your `README.md` file. You can copy and paste this directly into your repository. Let me know if you need further assistance!
