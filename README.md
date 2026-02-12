# Image Steganography in C

A simple Image Steganography project developed in C that hides and extracts secret data inside BMP image files using the Least Significant Bit (LSB) technique.

---

## 📌 Features

- Encode secret data into BMP image
- Decode hidden data from stego image
- Uses LSB (Least Significant Bit) technique
- Command-line based execution
- Proper error handling
- File handling using C

---

## 🛠 Technologies Used

- C Programming
- File Handling
- Bitwise Operations
- BMP Image Processing

---

## 📂 Project Structure

- encode.c
- decode.c
- encode.h
- decode.h
- common.h
- types.h
- beautiful.bmp (sample input image)

---

## ⚙️ How to Compile
gcc *.c

---

## ▶️ How to Run

### 🔹 Encoding

./a.out -e beautiful.bmp secret.txt stego.bmp

### 🔹 Decoding

./a.out -d stego.bmp decoded.txt

---

## 🖥 Sample Execution

### Encoding

INFO: ## Encoding Procedure Started ##
INFO: Opening required files
INFO: Encoding Magic String Signature
INFO: Encoding secret.txt File Data
INFO: ## Encoding Done Successfully ##
Encoding is successful!

### Decoding

INFO: ## Decoding Procedure Started ##
INFO: Magic string verified successfully
INFO: Decoding File Data
INFO: ## Decoding Done Successfully ##
Decoding is successful!

---

## 🧠 Algorithm Used

- Least Significant Bit (LSB) Technique
- Bitwise manipulation
- File pointer operations
- BMP header preservation

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

Afifa Tabassum
