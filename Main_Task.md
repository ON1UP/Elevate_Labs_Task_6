## 🔐 Password Strength Evaluation 

This document outlines the password testing steps, results, and improvements made during each stage.

---

### ✅ Step 1: Basic Numeric Password
- **Password:** `1234567889`
- **Tool Used:** [PasswordMonster](https://www.passwordmonster.com)
- **Result:** Very Weak
- **Time to Crack:** 0.28 seconds
- **Review:** Contains only numbers in a predictable sequence.

**🔧 Improvement Made:**  
→ Added an uppercase letter and a special character to increase complexity.
![Screenshot 2025-06-07 184627](https://github.com/user-attachments/assets/64d71c0a-b2e3-4146-9f9f-15631425a8cd)

---

### ✅ Step 2: Added Uppercase and Symbol
- **Password:** `1D@234567889`
- **Tool Used:** PasswordMonster
- **Result:** Weak
- **Time to Crack:** 1 hour
- **Review:** Better than before, but still weak due to inclusion of common patterns and dictionary-based guessability.

**🔧 Improvement Made:**  
→ Removed predictable numeric sequence and included personal keyword with a mix of characters.
![Screenshot 2025-06-07 184812](https://github.com/user-attachments/assets/f8646715-30d7-4ed4-8f25-4fea22ebfbac)

---

### ✅ Step 3: Mixed Case, Symbols, and Less Predictability
- **Password:** `S@blo@k2025#`
- **Tool Used:** [PasswordMeter](https://www.passwordmeter.com)
- **Result:** Strong
- **Time to Crack:** 3 thousand years 
- **Review:** Good mix of upper/lowercase letters, numbers, and symbols. More personalized, but still partly predictable.
![Screenshot 2025-06-07 192431](https://github.com/user-attachments/assets/5a6d1fd8-1e58-4986-bd7e-6a4e901f271f)

**🔧 Improvement Made:**  
→ Increased randomness and length, removed personal ties, and created a purely random password.

---

### ✅ Step 4: Random Complex Password
- **Password:** `7uV*e&1qZ$#rBtNp`
- **Tool Used:** PasswordMeter, Kaspersky Password Checker
- **Result:** Very Strong
- **Time to Crack:** Centuries (estimated)
- **Review:** High entropy. Strong resistance against brute force and dictionary attacks. Ideal for secure environments.
![Screenshot 2025-06-07 192521](https://github.com/user-attachments/assets/f4c212d1-d94b-4b07-91a4-8ca878f8f510)

**🔧 Final Tip:**  
→ Use password managers to securely store and generate such strong, random passwords.

---

### 📌 Summary

| Step | Password             | Strength     | Time to Crack | Improvement Made                                |
|------|----------------------|--------------|----------------|--------------------------------------------------|
| 1    | `1234567889`         | Very Weak    | 0.28 seconds   | Added uppercase + symbol                        |
| 2    | `1D@234567889`       | Weak         | 1 hour         | Removed patterns + personalized structure       |
| 3    | `S@blo@k2025#`       | Strong       | —              | More symbol mix, less predictable               |
| 4    | `7uV*e&1qZ$#rBtNp`   | Very Strong  | Centuries      | Fully random, long, mixed character types       |

---

📁 **Screenshots for each step are available in the `/screenshots` folder.**
