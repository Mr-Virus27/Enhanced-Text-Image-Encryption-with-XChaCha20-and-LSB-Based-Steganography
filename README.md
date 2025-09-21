# Enhanced Text & Image Encryption with XChaCha20 and LSB-Based Steganography

A Python implementation of a secure communication system that encrypts text and image data with **XChaCha20** and hides the encrypted payload within cover images using **Least Significant Bit (LSB) steganography**.

This project combines **cryptography** and **steganography** to provide dual-layer protection of sensitive data, enhancing both confidentiality and imperceptibility.

---

##  Features

- **Modern Symmetric Encryption**  
  Uses XChaCha20 (extension of ChaCha20) for fast, secure encryption with an extended nonce size to reduce risk of reuse.

- **Image Steganography**  
  Embeds encrypted text or images into cover images with minimal visual distortion using LSB substitution.

- **Decryption & Extraction**  
  Recovers the hidden encrypted payload and decrypts it back to the original message or image.

- **Key Management**  
  Handles secure generation and storage of encryption keys.

- **User Interface**  
  Simple command-line or GUI interface to encrypt, embed, extract, and decrypt data.

---

