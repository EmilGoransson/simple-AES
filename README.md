# AES Encryption Implementation

## Overview
A basic implementation of the AES-128 encryption algorithm in Python for the course DD2520 Applied Cryptography. This command-line tool encrypts input data using a 16-byte key.

## Note
This is a simplified implementation and is NOT secure for real use. It is vulnerable to various attacks (side channel etc). 

## Usage
```bash
echo -n "MySixteenByteKey" | cat - mydata.txt | python3 aes_encrypt.py > encrypted.bin
```

## Features
- Basic AES-128 encryption (no decryption)
- Standard AES operations (SubBytes, ShiftRows, MixColumns, AddRoundKey)
- Key expansion for round keys
- Processes 16-byte blocks

## Requirements
- Python 3.x
