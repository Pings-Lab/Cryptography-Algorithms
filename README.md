# 🛡️ The Cryptography Atlas

A comprehensive, chronological repository of cryptographic algorithms—from ancient pen-and-paper ciphers to modern post-quantum standards. This project serves as a technical encyclopedia, providing a deep dive into the history, mechanics, and security status of each method.

## 🏛️ Project Index

| Era | Year | Algorithm / Concept | Creator(s) | Type | Status |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Ancient** | ~1900 BC | [Symbol Replacement](./algos/symbol-replacement.md) | Egyptian Scribes | Substitution | 🏛️ Historical |
| **Ancient** | ~500 BC | [Atbash Cipher](./algos/atbash.md) | Hebrew Scholars | Substitution | 🔴 Broken |
| **Ancient** | ~400 BC | [Scytale](./algos/scytale.md) | Spartan Military | Transposition | 🏛️ Historical |
| **Ancient** | ~50 BC | [Caesar Cipher](./algos/caesar.md) | Julius Caesar | Substitution | 🔴 Broken |
| **Medieval** | 800s | [Frequency Analysis](./algos/frequency-analysis.md) | Al-Kindi | Attack Method | 🔍 N/A |
| **Renaissance** | 1467 | [Polyalphabetic Disk](./algos/alberti-disk.md) | Leon Battista Alberti | Mechanical | 🏛️ Historical |
| **Renaissance** | 1553 | [Vigenère Cipher](./algos/vigenere.md) | Giovan Bellaso | Substitution | 🔴 Broken |
| **Victorian** | 1854 | [Playfair Cipher](./algos/playfair.md) | Charles Wheatstone | Substitution | 🔴 Broken |
| **Pre-War** | 1917 | [Hebern Rotor](./algos/hebern-rotor.md) | Edward Hebern | Mechanical | 🔴 Broken |
| **Early Mod** | 1917 | [One-Time Pad (OTP)](./algos/otp.md) | Vernam & Mauborgne | Stream | 💎 Perfect |
| **WWII** | 1920s | [Enigma](./algos/enigma.md) | Arthur Scherbius | Rotor Machine | 🔴 Broken |
| **WWII** | 1943 | [Lorenz (SZ42)](./algos/lorenz.md) | German Military | Rotor Machine | 🔴 Broken |
| **Cold War** | 1974 | [DES](./algos/des.md) | IBM / NSA | Block Cipher | 🔴 Broken |
| **Modern** | 1976 | [Diffie-Hellman](./algos/diffie-hellman.md) | Diffie & Hellman | Key Exchange | 🟡 Safe* |
| **Modern** | 1977 | [RSA](./algos/rsa.md) | Rivest/Shamir/Adleman | Asymmetric | 🟡 Safe* |
| **Modern** | 1980 | [MD4 / MD5](./algos/md5.md) | Ron Rivest | Hashing | 🔴 Broken |
| **Modern** | 1985 | [ECC](./algos/ecc.md) | Miller & Koblitz | Asymmetric | 🟢 Safe |
| **Modern** | 1991 | [PGP](./algos/pgp.md) | Phil Zimmermann | Protocol | 🟢 Safe |
| **Modern** | 1993 | [Blowfish](./algos/blowfish.md) | Bruce Schneier | Block Cipher | 🟢 Safe |
| **Modern** | 1995 | [SHA-1](./algos/sha1.md) | NSA | Hashing | 🔴 Broken |
| **Modern** | 1996 | [RC4](./algos/rc4.md) | Ron Rivest | Stream Cipher | 🔴 Broken |
| **Modern** | 1998 | [Twofish / Serpent](./algos/twofish.md) | Schneier / Anderson | Block Cipher | 🟢 Safe |
| **Modern** | 1999 | [bcrypt](./algos/bcrypt.md) | Provos & Mazières | PWD Hashing | 🟢 Safe |
| **Modern** | 2001 | [AES (Rijndael)](./algos/aes.md) | Daemen & Rijmen | Block Cipher | 🏆 Gold Std |
| **Modern** | 2004 | [AES-GCM](./algos/aes-gcm.md) | McGrew & Viega | Mode (AEAD) | 🏆 Gold Std |
| **Web 3.0** | 2005 | [Curve25519](./algos/curve25519.md) | Daniel J. Bernstein | ECC | 🏆 Gold Std |
| **Web 3.0** | 2008 | [ChaCha20-Poly1305](./algos/chacha20-poly1305.md) | Daniel J. Bernstein | Stream/AEAD | 🏆 Gold Std |
| **Web 3.0** | 2009 | [scrypt](./algos/scrypt.md) | Colin Percival | PWD Hashing | 🟢 Safe |
| **Web 3.0** | 2012 | [SHA-3 (Keccak)](./algos/sha3.md) | Daemen et al. | Hashing | 🏆 Gold Std |
| **Web 3.0** | 2014 | [Double Ratchet](./algos/double-ratchet.md) | Signal Foundation | Protocol | 🏆 Gold Std |
| **Web 3.0** | 2015 | [Argon2](./algos/argon2.md) | Biryukov et al. | PWD Hashing | 🏆 Gold Std |
| **PQC Era** | 2022 | [CRYSTALS-Kyber](./algos/kyber.md) | Bos / Ducas et al. | Lattice-KEM | 🔵 Standard |
| **PQC Era** | 2022 | [CRYSTALS-Dilithium](./algos/dilithium.md) | Lyubashevsky et al. | Lattice-Sign | 🔵 Standard |

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

