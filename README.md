# Encryption-and-Decryption
This Python project integrates Caesar Cipher and Image Steganography for secure encryption and decryption. It ensures confidentiality by embedding encrypted messages within images. Featuring a user-friendly Tkinter GUI, it enables seamless interaction while leveraging cryptographic techniques for secure communication.


# Features

. Text Encryption & Decryption using Caesar Cipher

. Image Steganography for hiding messages inside images

. Graphical User Interface (GUI) for easy interaction

. Supports Secure Communication through encryption methods

# Technologies Used

. Python

. Tkinter (for GUI)

. PIL (Pillow) (for image processing)

. Stegano (for image steganography)

. NumPy

# Working of the Project

# 1. User Interface (GUI) Initialization
   
  . The project starts with a Graphical User Interface (GUI) built using Tkinter.
  . The user is given two options:
 1. Text Encryption & Decryption (Caesar Cipher)
 2. Image-based Steganography

# 2. Caesar Cipher (Text Encryption & Decryption)
   
 Encryption Process:
  . The user inputs a text message.
  . A shift key is provided (e.g., shift = 3).
  . The program shifts each letter forward in the alphabet based on the shift key.
    Example: "HELLO" with shift 3 → "KHOOR".
  . The encrypted text is displayed and can be copied/saved.

 Decryption Process:
  . The user enters the encrypted text.
  . The same shift key is provided.
  . The program shifts each letter backward to retrieve the original message.
    Example: "KHOOR" with shift 3 → "HELLO".
  . The decrypted message is displayed.

# 3. Image Steganography (Hiding and Extracting Messages in Images)
    
 Hiding a Message (Encoding):
  . The user selects an image file (e.g., PNG, JPEG).
  . A text message is entered.
  . The Stegano library encodes the text into the image without visibly altering it.
  . The modified image is saved as an output file.
  
Extracting a Hidden Message (Decoding):
  . The user selects the image with the hidden message.
  . The program extracts the message from the image.
  . The hidden text is displayed.
 
# 4. Secure Communication & Confidentiality
  . By combining Caesar Cipher and Steganography, users can first encrypt a message using Caesar Cipher and then hide it inside an image for added security.
  . This ensures confidentiality and secure communication over untrusted channels.


   
