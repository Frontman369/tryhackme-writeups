# Cryptography Basics - TryHackMe Writeup

## Overview
This room introduced the foundational concepts of cryptography and explored how encryption protects data confidentiality. It covered the evolution of cryptographic methods, the differences between symmetric and asymmetric encryption, and the mathematical concepts that support modern cryptographic systems.

---

## Objectives
Throughout this room, I learned how to:
- Understand fundamental cryptography terminology  
- Explain why cryptography is essential in modern communication  
- Explore historical encryption techniques such as the Caesar Cipher  
- Differentiate between symmetric and asymmetric encryption  
- Understand the role of mathematical operations like XOR and modulo in encryption systems  

---

## Concepts Covered
- Plaintext & Ciphertext  
- Encryption & Decryption  
- Cryptographic keys  
- Caesar Cipher  
- Symmetric encryption  
- Asymmetric encryption  
- XOR operation  
- Modulo arithmetic  

---

## Key Concepts

### Importance of Cryptography
The room demonstrated how cryptography protects:
- confidentiality  
- integrity  
- secure communication  

Without encryption, sensitive information such as credentials, financial data, and private communication could be intercepted or modified by attackers.

---

### Plaintext vs Ciphertext
I learned the distinction between:
- **Plaintext** → readable original data  
- **Ciphertext** → encrypted unreadable output  

Encryption transforms plaintext into ciphertext using a cipher and a key, while decryption reverses the process.

---

### Historical Ciphers
The Caesar Cipher was introduced as an example of classical encryption, where characters are shifted through the alphabet using a fixed offset. 
For a detailed understanding, I made myself an interactive and visual based Caesar Cipher, as part of my [vibe coding](https://github.com/Frontman369/vibe-coding) journey!

Although historically significant, such ciphers are extremely weak by modern standards.

---

### Symmetric vs Asymmetric Encryption

#### Symmetric Encryption
Uses the same secret key for both encryption and decryption.

Advantages:
- fast  
- efficient for large data transfers  

Challenge:
- secure key sharing  

---

#### Asymmetric Encryption
Uses two mathematically related keys:
- public key  
- private key  

This allows secure communication without directly sharing private secrets.

---

### XOR & Modulo Operations
The room also introduced mathematical concepts commonly used in cryptography.

- **XOR** is frequently used in encryption algorithms because of its reversible properties  
- **Modulo operations** are heavily used in modern cryptographic mathematics and key generation  

---

## Challenges Faced
- Understanding the mathematical side of cryptography  
- Differentiating encryption methods and their practical uses  
- Connecting historical ciphers to modern encryption concepts  

---

## Key Takeaways
- Cryptography is fundamental to modern digital security  
- Encryption protects sensitive data from unauthorized access  
- Symmetric and asymmetric encryption solve different security problems  
- Mathematical operations form the backbone of cryptographic systems  
- Even simple historical ciphers help explain modern encryption principles  

---

## Reflection
Many of the concepts introduced in this room were already somewhat familiar to me from reading The Code Book by [Simon Singh](https://en.wikipedia.org/wiki/The_Code_Book). 
However, this room helped reinforce those ideas through practical cybersecurity-focused explanations.

It also strengthened my understanding of why cryptography remains one of the most important pillars of modern cybersecurity.
