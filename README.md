# AEStool

AEStool is a simple command-line tool written in Python that allows you to encrypt and decrypt text using AES (Advanced Encryption Standard).

## Features

- Encrypt text files
- Decrypt encrypted files
- Encrypt manually entered text
- Decrypt manually entered encrypted text
- Clipboard support for easy copying
- Colored terminal output

## Requirements

Install the required Python packages:

pip install pyperclip colorama termcolor

## Usage

Run the script from your terminal:

python aestool.py [options]

### Available Options

- -ef, --encrypt-file     Encrypt a file
- -df, --decrypt-file     Decrypt a file
- -e,  --encrypt-text     Encrypt text input
- -d,  --decrypt-text     Decrypt text input
- -s,  --show-encrypted   Display encrypted output

## Examples

Encrypt a file:

python aestool.py -ef file.txt

Encrypt text:

python aestool.py -e "Hello World"

Decrypt a file:

python aestool.py -df encrypted.txt

Decrypt text:

python aestool.py -d "encrypted_string_here"

## Notes

- On Windows, use Command Prompt or PowerShell for best compatibility.
- Keep the encryption key and IV (Initialization Vector) safe. They are required for decryption.

## License

This project is licensed under the MIT License.
