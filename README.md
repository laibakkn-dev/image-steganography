# Image Steganography Application

Author     : [Laiba jalil]
Supervisor : [Mr Ghulam Ali]
Language   : Python
Technique  : LSB (Least Significant Bit)

## What it does
This app hides secret messages inside images using the LSB technique.
Changing the last bit of each pixel color value is invisible to the human eye
but can store hidden text.

## How to run
1. Install Pillow:  pip install Pillow
2. Run the app:     python steganography.ipynb

## Features
- Hide a message inside any PNG/JPG image
- Reveal the hidden message from a stego image
- Menu keeps running until you choose Exit
