# Image Steganography in C

A simple Image Steganography project developed in C that hides and extracts secret data inside BMP image files using the LSB (Least Significant Bit) technique.

## Features
- Encode secret data into BMP image
- Decode hidden data from image
- Command line based execution
- Error handling for invalid inputs

## Technologies Used
- C Programming
- File Handling
- Bitwise Operations

## How to Compile
gcc main.c encode.c decode.c -o stego

## How to Run

## Sample Execution

### Encoding

$ gcc *.c
$ ./a.out -e beautiful.bmp secret.txt stego.bmp

INFO: ## Encoding Procedure Started ##
INFO: Opening required files
INFO: Opened beautiful.bmp
INFO: Opened secret.txt
INFO: Opened stego.bmp
INFO: Encoding Magic String Signature
INFO: Encoding secret.txt File Extension
INFO: Encoding secret.txt File Size
INFO: Encoding secret.txt File Data
INFO: ## Encoding Done Successfully ##

Encoding is successful!

### Decoding

$ ./a.out -d stego.bmp decoded.txt

INFO: ## Decoding Procedure Started ##
INFO: Opening required files
INFO: Opened stego.bmp
INFO: Decoding Magic String Signature
INFO: Magic string verified successfully
INFO: Decoding Output File Extension
INFO: Decoding decoded.txt File Data
INFO: ## Decoding Done Successfully ##

Decoding is successful!

## Author
Afifa Tabassum
