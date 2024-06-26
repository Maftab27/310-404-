# 310-404-

File Encryption and Decryption Utility
This utility is a simple command-line application written in C that allows you to encrypt and decrypt text files using the Caesar cipher, a substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet.

Features
Encryption: Shifts the text in the input file by a specified number of places in the alphabet and writes the encrypted text to an output file.
Decryption: Reverses the encryption process by shifting the text in the input file back to its original form and writing the decrypted text to an output file.

Components
The application is divided into three main files:

Usage
To compile the program, you need a C compiler like GCC. Navigate to the directory containing the source files and run the following command:
gcc -o file_cipher main.c cipher.c
To encrypt a file, use:
./file_cipher encrypt <shift> <input file> <output file>
To decrypt a file, use:
./file_cipher decrypt <shift> <input file> <output file>
Where <shift> is the number of positions each letter in the text should be shifted by in the alphabet.

cipher.h: Header file with declarations for the encryption and decryption functions.
cipher.c: Contains the implementation of the encryption (cipher) and file processing functions.
main.c: Handles user input and command-line arguments to control the flow of encryption and decryption processes.

Note
The Caesar cipher is not suitable for secure encryption as it is easily broken. This utility is intended for educational purposes or for encrypting data that does not require strong security measures.




