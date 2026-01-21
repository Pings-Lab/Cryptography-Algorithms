# Cryptography-Algorithms
Every cryptography algorithm ever made

## 🛡️ The Cryptography Atlas: 
Every Algorithm Ever MadeA comprehensive, chronological repository of cryptographic algorithms—from ancient pen-and-paper ciphers to modern post-quantum standards. This project serves as a technical encyclopedia, providing a deep dive into the history, mechanics, and security status of each method.

## 📖 Table of Contents
- IntroductionThe
- Timeline
- Security Status Legend
- Project Structure
- Contributing

# 🛡️ The Cryptography Atlas

A comprehensive, chronological repository of cryptographic algorithms—from ancient pen-and-paper ciphers to modern post-quantum standards. This project serves as a technical encyclopedia, providing a deep dive into the history, mechanics, and security status of each method.

## 🏛️ Project Index

| Era | Year | Algorithm | Type | Status |
| :--- | :--- | :--- | :--- | :--- |
| **Ancient** | ~50 BC | [Caesar Cipher](./algos/caesar-cipher.md) | Substitution | 🔴 Broken |
| **Renaissance** | 1467 | [Vigenère Cipher](./algos/vigenere-cipher.md) | Polyalphabetic | 🔴 Broken |
| **Modern** | 1974 | [DES](./algos/des.md) | Block Cipher | 🔴 Broken |
| **Modern** | 1977 | [RSA](./algos/rsa.md) | Asymmetric | 🟡 Legacy |
| **Modern** | 2001 | [AES (Rijndael)](./algos/aes.md) | Block Cipher | 🟢 Gold Std |
| **Modern** | 2008 | [ChaCha20](./algos/chacha20.md) | Stream Cipher | 🟢 Gold Std |
| **Future** | 2022+ | [CRYSTALS-Kyber](./algos/kyber.md) | Post-Quantum | 🔵 Emerging |

---

## 🚦 Security Status Legend

* 🟢 **Gold Standard:** Current industry best practice. Safe for modern production.
* 🟡 **Legacy/Safe:** Mathematically secure but requires large keys or specific implementations.
* 🔴 **Broken:** Vulnerable to modern cryptanalysis. Use for educational purposes only.
* 🔵 **Emerging:** Post-Quantum Cryptography (PQC) candidates.

## 📁 Project Structure

```bash
├── README.md           # Project Overview & Index
├── algos/              # Individual algorithm deep-dives
│   ├── aes.md
│   ├── rsa.md
│   └── ...
└── assets/             # Diagrams and educational images
```

## 🛠️ Contributing
- If you find a missing variant or want to add a code implementation:

- Fork the repo.

- Create a new file in /algos.

- Submit a Pull Request.

