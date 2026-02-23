# AEStool

AEStool is a simple command-line program written in Python that lets you encrypt and decrypt text using AES (Advanced Encryption Standard).

## What It Does

AEStool can:

- Encrypt the content of a text file - -ef or --encrypt-file
- Decrypt an encrypted file - -df or --decrypt-file
- Encrypt text you type manually - -e or --encrypt-text
- Decrypt text you enter manually - -d or --decrypt-text
- Displays the encrypted text - -s or --show-encrypted
It works entirely in your terminal or command prompt.

## Requirements

Before you use AEStool, you need to install these Python packages:

- `pyperclip` – lets the program copy text to your clipboard
- `colorama` – adds color support in the terminal
- `termcolor` – lets the program print colored text

You can install them with:

```bash
pip install pyperclip colorama termcolor
