# Audio Encryption & Decryption using AES and RSA Algorithms
This project demonstrates a simple web application for encrypting and decrypting audio files using Python with Flask and the PyCrypto library for encryption. It provides a user-friendly interface for uploading audio files, encrypting them with AES encryption, and decrypting them using RSA encryption.
## Features
### Encryption:
        Users can upload an audio file, which is then encrypted using AES encryption with a randomly generated key. The AES key is then encrypted using RSA encryption with a public key.
### Decryption: 
        Encrypted audio files can be uploaded along with the corresponding private key file, allowing users to decrypt the audio and download the decrypted version.
### Download Options: 
        Users can download the encrypted audio file and the private key for decryption.

## Technologies Used
### Flask: 
        A lightweight web framework for Python used to develop the backend server and handle HTTP requests.
### PyCrypto: 
        A Python library providing cryptographic functions, including AES and RSA encryption.
### HTML/CSS/JavaScript: 
        Used for the frontend to create the user interface and handle dynamic interactions.\


## Usage
        1.)Navigate to the homepage ('/') to access the main menu.
        2.)Click on "Encrypt Audio" to go to the encryption page.
        3.)Upload an audio file and click "Encrypt" to encrypt the file.
        4.)After encryption, you can download the encrypted audio file.
        5.)Click on "Decrypt Audio" from the main menu to access the decryption page.
        6.)Upload the encrypted audio file and the corresponding private key file.
        7.)Click "Decrypt" to decrypt the audio file, and then you can download the decrypted audio file.

## Notes
        Make sure to keep the private key file secure, as it is required for decryption and should not be shared publicly.
        This project is intended for educational purposes and may require additional security measures for production use.
