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

### Encoding
./stego -e input.bmp secret.txt output.bmp

### Decoding
./stego -d output.bmp

## Author
Afifa Tabassum
