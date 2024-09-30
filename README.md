# Caesar Cipher Program

This repository contains a Python implementation of the Caesar Cipher, a classic encryption technique that allows users to encrypt and decrypt messages using a customizable shift value.

## Overview

The Caesar Cipher operates by shifting letters in the alphabet. For example, with a shift of 3, 'A' becomes 'D', 'B' becomes 'E', and so on. This straightforward method is perfect for those looking to understand the basics of encryption.

## Features

- **Encrypt and Decrypt**: Users can choose to encrypt a plaintext message or decrypt a previously encrypted one.
- **Custom Shift Value**: The program allows for a user-defined shift, giving flexibility in the encryption process.
- **Input Validation**: It checks that the shift value is an integer and provides error messages for invalid inputs.

## How to Use

1. **Run the Program**: Execute the script to open the Caesar Cipher interface.
2. **Choose an Option**:
   - **Encrypt**: Input a message and a shift value to get the encrypted text.
   - **Decrypt**: Enter an encrypted message and the corresponding shift value to retrieve the original text.
   - **Quit**: Exit the application.
   
3. **Error Handling**: If an invalid shift value is entered, the program prompts the user to try again.

## Example

```bash
$ python caesar_cipher.py
Caesar Cipher Program
---------------------
Options:
1. Encrypt
2. Decrypt
3. Quit
Choose an option: 1
Enter a message to encrypt: Hello, World!
Enter a shift value: 3
Encrypted message: Khoor, Zruog!
```

## Functions

### `caesar_cipher(text, shift, direction)`

- **Parameters**:
  - `text` (str): The text to encrypt or decrypt.
  - `shift` (int): The shift value for the cipher.
  - `direction` (str): Either 'encrypt' or 'decrypt'.
  
- **Returns**: The resulting encrypted or decrypted string.

### `main()`

This function manages user interaction, helping users navigate the encryption and decryption process.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests for enhancements or new features.

## License

This project is open-source and licensed under the MIT License.
