# Caesar Cipher Program

## Summary
This Python script implements a Caesar Cipher, a type of substitution cipher used for encrypting and decrypting text. The program allows the user to encode or decode a message by shifting each letter in the message by a specified number of positions in the alphabet. The program supports both lowercase and uppercase letters (converted to lowercase) and handles non-alphabetic characters (e.g., spaces, punctuation) by leaving them unchanged. The program also includes a loop for continuous use until the user chooses to exit.

## Features
- **Encryption and Decryption**: The program supports both encoding (encrypting) and decoding (decrypting) messages using the Caesar Cipher method.
- **Shift Logic**: The program shifts each letter in the message by a user-specified number of positions in the alphabet. For decryption, the shift is reversed by multiplying by `-1`.
- **Alphabet Handling**: The program uses a list of lowercase letters (`alphabet`) to determine the shifted position of each character. It wraps around the alphabet using modulo (`%`) to handle shifts that exceed the length of the alphabet.
- **Non-Alphabetic Characters**: Non-alphabetic characters (e.g., spaces, numbers, punctuation) are left unchanged in the output.
- **User Interaction**: The program prompts the user to choose between encoding or decoding, enter a message, and specify the shift amount. It also allows the user to continue using the program or exit after each operation.
- **ASCII Art**: The `ccart` module is used to display a logo or visual element at the start of the program, enhancing the user experience.
- **Loop Control**: A `while` loop is used to allow continuous use of the program until the user chooses to exit.

## How to Use
1. Run the script in a Python environment.
2. Choose to either encode or decode a message by typing `encode` or `decode`.
3. Enter the message you want to encrypt or decrypt.
4. Specify the shift number (the number of positions each letter should be shifted).
5. The program will display the encoded or decoded message.
6. Choose to continue using the program or exit by typing `Y` or `N`.

## Requirements
- Python 3.x
- The `ccart` module (for displaying the program logo).

## Running the Program
To run the program, simply execute the script in your Python environment:
```bash
python caesar_cipher.py
