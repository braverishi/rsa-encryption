# 🔐 RSA Encryption Utility

A simple web-based tool to **generate RSA key pairs, encrypt messages, and decrypt ciphertext** — all inside your browser using the Web Crypto API.
This project demonstrates how RSA encryption works and is hosted on **GitHub Pages** for easy access.

👉 [Live Demo](https://braverishi.github.io/rsa-encryption/)

---

## ✨ Features

* Generate RSA key pair (2048-bit, RSA-OAEP with SHA-256).
* Export keys in Base64 format.
* Encrypt text using the generated public key.
* Decrypt text using the generated private key.
* Runs **100% locally in your browser** (no server needed).

---

## 🚀 How to Use

1. Open the [live demo](https://braverishi.github.io/rsa-encryption/).
2. Click **Generate RSA Keys** → copy your keys.
3. Type a message in the box and click **Encrypt** → ciphertext will appear.
4. Paste ciphertext into the box and click **Decrypt** → original message is restored.

---

## 📝 Usage Example

**Step 1: Generate Keys**
You get a Public Key and Private Key (in Base64).

**Step 2: Enter Message**

```
Hello RSA!
```

**Step 3: Encrypt → Output**

```
lI4aJk9t...FzP8y9H==
```

**Step 4: Decrypt → Output**

```
Hello RSA!
```

---



## 📚 Tech Stack

* **HTML5**
* **CSS3**
* **JavaScript (Web Crypto API)**

---



