# 🔐 Password Security Demo

An interactive, browser-based tool for exploring password strength, security, and common password vulnerabilities.

The project demonstrates how password analysis works by examining password patterns, estimating guessability, and generating stronger passwords.

## ✨ Features

### 📘 Learn Mode
- Analyses password strength in real time.
- Identifies common password weaknesses and patterns.
- Estimates password entropy and cracking difficulty.
- Explains detected weaknesses and suggests improvements.
- Displays character composition.

### 🛡️ Attacker Mode
- Estimates how many guesses an attacker might need.
- Identifies common attack patterns and password structures.
- Demonstrates dictionary-based attacks and character substitutions.
- Explains how predictable password patterns affect security.

### 🔑 Password Generator
- Generates random passwords.
- Generates four-word passphrases.
- Uses the browser's `crypto.getRandomValues()` API for secure random generation.

### #️⃣ SHA-256 Demonstration
- Demonstrates SHA-256 hashing.
- Introduces the concept of cryptographic hashing and password security.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Web Crypto API

No external libraries or frameworks are required.

## 🔒 Privacy

- Password analysis is performed locally in the browser.
- Password inputs are not intentionally transmitted to a server.
- Generated passwords are created locally.
- No account or registration is required.

**Important:** Use sample passwords for experimentation. Never enter your actual passwords or credentials into an educational demo.

## ⚠️ Limitations

This project is an educational demonstration, not a professional password auditing or security-testing tool.

- Strength scores and entropy calculations are heuristic estimates, not official security standards.
- Estimated cracking times depend on assumptions about attacker hardware, techniques, and available information.
- Pattern detection cannot identify every possible weakness.
- Password reuse and data breaches cannot be detected through local analysis.
- Results may be less accurate for languages and writing systems other than English.

A high score does not guarantee that a password is secure.

## 🚀 Running the Project

### Run Locally

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Start experimenting with sample passwords.

### Run Online

The project can also be hosted using **GitHub Pages**.

Once GitHub Pages is enabled, the website will be accessible through its published GitHub Pages URL.

## 🎯 Purpose

This project was created to explore cybersecurity concepts, understand password security mechanisms, and demonstrate how seemingly strong passwords can still contain predictable patterns.

It is intended for educational and awareness purposes only.

---

*Built as an educational cybersecurity project.*