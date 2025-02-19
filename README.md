# Secure Data Hiding in Images using Steganography  

## 📌 Project Overview  
This project provides a secure and user-friendly way to encrypt and decrypt messages within images using steganography and password protection. The message is embedded inside an image using OpenCV and can only be retrieved with the correct password.  

## 🛠️ Technologies Used  
- **Python** – Programming language  
- **OpenCV** – Image processing  
- **NumPy** – Array manipulation  
- **PyQt6** – Graphical User Interface (GUI)  

## 🔥 Features  
- **Steganography-based encryption** – Hides messages within image pixels.  
- **Password-protected decryption** – Ensures secure message retrieval.  
- **Graphical User Interface (GUI)** – Easy-to-use interface.  
- **No need for external storage** – The message is stored directly in the image.  
- **Works with PNG images** – Saves encrypted images in a lossless format.  


## 🚀 Usage

### Encrypt an Image

1.  Run the encryption script:

    ```
    python encrypt_gui.py
    ```

2.  Enter the secret message and password in the GUI.
3.  Click on "Encrypt Image" and select the image to embed the message into. The encrypted image will be saved in the same directory.

### Decrypt an Image

1.  Run the decryption script:

    ```
    python decrypt_gui.py
    ```

2.  Enter the password used during encryption in the GUI.
3.  Select the encrypted image.
4.  If the password is correct, the hidden message will be revealed in the GUI.

## 🎯 Screenshots

### 🔐 Encryption Process

![Encryption Output](C:\Users\bthem\OneDrive\Pictures\Screenshots 1\Screenshot 2025-02-19 065610.png)  *(Replace Encryption_Output.png with the actual filename or path to your encryption output screenshot)*

### 🔓 Decryption Process

![Decryption Output](C:\Users\bthem\OneDrive\Pictures\Screenshots 1\Screenshot 2025-02-19 065432.png) *(Replace Decryption_Output.png with the actual filename or path to your decryption output screenshot)*

## 🎯 Future Scope

*   ✅ Support for multiple image formats (JPG, BMP, etc.)
*   ✅ Implementation of AES encryption for extra security
*   ✅ Development of a mobile and web application
*   ✅ AI-based image security and tampering detection
