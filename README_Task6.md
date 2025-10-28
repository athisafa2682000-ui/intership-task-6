# 🔐 Task 6 — Password Strength Evaluation

## 🎯 Objective
To analyze and evaluate the strength of different passwords using an online password checker, calculate entropy, and understand how password complexity affects security.

---

## 🧩 Passwords Tested

### 1. **password123**
- **Length:** 11  
- **Contains:** Lowercase, Numbers  
- **Rating:** ❌ Very Weak  
- **Estimated Crack Time:** 0 seconds  
- **Summary:** Common and predictable; easily cracked instantly.

---

### 2. **P@ssw0rd!**
- **Length:** 9  
- **Contains:** Lowercase, Uppercase, Numbers, Symbol  
- **Rating:** ❌ Very Weak  
- **Estimated Crack Time:** 0 seconds  
- **Summary:** Common dictionary pattern with substitutions.

---

### 3. **7clouds9Song**
- **Length:** 12  
- **Contains:** Lowercase, Uppercase, Numbers  
- **Rating:** ⚠️ Strong  
- **Estimated Crack Time:** 1 month  
- **Summary:** Strong but could be improved by adding symbols.

---

### 4. **Taco$Blue8Tree#**
- **Length:** 15  
- **Contains:** Lowercase, Uppercase, Numbers, Symbols  
- **Rating:** ✅ Very Strong  
- **Estimated Crack Time:** 338 years  
- **Summary:** Excellent strength; meets modern security standards.

---

### 5. **correct horse battery staple**
- **Length:** 28  
- **Contains:** Lowercase only  
- **Rating:** ✅ Very Strong  
- **Estimated Crack Time:** 13 million years  
- **Summary:** Extremely strong due to long length and randomness.

---

## 🧪 Observations
1. Short or common passwords are instantly cracked by brute-force or dictionary attacks.  
2. Length and randomness are key — long passphrases outperform short complex passwords.  
3. Mixed character types drastically increase entropy.  
4. Passwords ≥15 characters are generally resistant to brute-force attacks.

---

## 💡 Recommendations
- Use **at least 12–16 characters** per password.  
- Combine **upper, lower, digits, and symbols** for complexity.  
- Prefer **random passphrases** (4–6 unrelated words).  
- Store credentials securely with a **password manager** (Bitwarden, KeePass, etc.).  
- Enable **Multi-Factor Authentication (MFA)** wherever possible.  
- Avoid personal info, birthdays, or predictable substitutions.

---

## 🖥️ Windows-Specific Tips
- Use **Windows Credential Manager** for local logins.  
- Use **Windows Hello (PIN/Biometrics)** for device sign-in.  
- Use **Bitwarden** or **KeePass** for secure password storage and generation.

---

## 🧾 Conclusion
Long, random passwords or multi-word passphrases are nearly impossible to brute-force.  
The best balance between security and memorability is a **random passphrase (≥6 words)** or a **15+ character mixed password** stored in a password manager with MFA enabled.

> ✅ **Best Password:** `Taco$Blue8Tree#` — Very Strong (338 years to crack)  
> ✅ **Best Passphrase:** `correct horse battery staple` — Very Strong (13 million years to crack)

---

## 📷 Screenshot Evidence
| Screenshot File | Description |
|:----------------|:-------------|
| `passwrd1.png` | password123 (very weak) |
| `passwrd2.png` | P@ssw0rd! (very weak) |
| `passwrd 3.png` | 7clouds9Song (strong) |
| `PASSWRD 4.png` | Taco$Blue8Tree# (very strong) |
| `passwrd5.png` | correct horse battery staple (very strong) |

---

**Author:** Atheeka Bi Safa  
**Operating System:** Windows 10  
**Tool Used:** PasswordMonster  
**Category:** Cybersecurity Fundamentals / Password Security
