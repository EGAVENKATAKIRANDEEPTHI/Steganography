Image Steganography Using LSB Encoding
Overview
This project implements Image Steganography using Least Significant Bit (LSB) Encoding to hide a secret text file inside an image. The secret message is encoded in the BMP image format, and the process includes encoding the length of the secret and the data into the least significant bits of the image pixels. The message can later be decoded and extracted bit by bit.

Features
Encoding: Embeds a secret text file into a BMP image using LSB encoding.
Decoding: Extracts the hidden message by decoding the image pixel's least significant bits.
Secure Transmission: The secret file is hidden within the image, making it undetectable to the naked eye.

Tools & Technologies
Embedded C: The core programming language for implementing the steganography techniques.
File Operations: Handling of image and text files during the encoding and decoding processes.
Pointers: Used for memory management and efficient data handling.
Bitwise Operations: For manipulating the least significant bits of image data to hide the secret message.



Usage
Encoding:
Select an image (BMP format) where you want to embed the secret text.
Provide the path to the text file you want to hide.
The program will encode the length of the text and the text itself into the image's LSB.
Decoding:
Provide the encoded image (BMP format).
The program will decode and retrieve the hidden text.
