## 📘 Overview  
This project implements **Image Steganography** — the art of hiding secret information inside digital images — using the **Least Significant Bit (LSB)** substitution technique in **MATLAB**.  

By manipulating the least significant bits of image pixels, secret messages or images can be embedded into a cover image without causing visible distortion. The main goal of this project is to **securely transmit hidden data** through digital media while maintaining image quality.


## 🔍 Key Features  
- 🧩 **Data Hiding:** Embed text or image data inside another image using LSB encoding.  
- 🕵️‍♀️ **Data Extraction:** Retrieve the hidden message or image from the stego image.  
- 🖥️ **MATLAB Implementation:** Built entirely using MATLAB image processing functions.  
- 🎨 **High Image Quality:** Minimal distortion after embedding due to LSB manipulation.  
- 🔐 **Secure Communication:** Useful for digital watermarking, authentication, and covert data transmission.  


## ⚙️ Technologies Used  
- **Programming Language:** MATLAB  
- **Concepts:** Digital Image Processing, Bit Manipulation, Steganography, Data Security  
- **Functions Used:** `imread()`, `imshow()`, `bitget()`, `bitset()`, `imwrite()`


## 🧠 Working Principle  
1. **Input:** A cover image and a secret message (text or image).  
2. **Conversion:** Convert both into binary format.  
3. **Embedding:** Replace the least significant bits of the cover image pixels with bits from the secret data.  
4. **Output:** A stego image visually identical to the original.  
5. **Extraction:** Reverse the process to recover the hidden message or image.  


## 🧩 System Flow  
**Encoding Phase:**  
- Read cover image  
- Convert secret data to binary  
- Embed data into the LSB of each pixel  
- Save the stego image  

**Decoding Phase:**  
- Read the stego image  
- Extract the LSBs  
- Reconstruct the hidden data 
