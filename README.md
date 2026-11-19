# Networkwalks Cybersecurity & Ethical Hacking Internship — Week 3

**Intern:** Sheheryar Ilyas  
**Program / Batch:** B084 - Networkwalks Cybersecurity Internship  
**Topic:** Password Cracking & Hash Analysis (`W3-PM1` & `W3-PM2`)  
**Date:** 20 November 2026  

---

## Project Overview
This repository documents the completion of Week 3 practical tasks focusing on cryptographic hash extraction and dictionary-based password recovery on encrypted PDF documents within an authorized educational lab environment.

### Modules Completed
1. **W3-PM1 — Password Cracking with John the Ripper (JTR):**
   - **Target:** `My Locked PDF1.pdf`
   - **Hash Format:** PDF R4 / 128-bit (`$pdf$4*4*128*...`)
   - **Tool Used:** John the Ripper (`john`) on Kali Linux
   - **Cracked Password:** `good-luck`
   - **Captured Flag:** `nw{cybersecurity_flag_captured_2608}`

2. **W3-PM2 — Password Cracking with Networkwalks Tools:**
   - **Target:** `My Locked PDF1 (for NW Tools Lab WK3-PM2).pdf`
   - **Tools Used:** Networkwalks Hash Calculator & Password Cracker (Dictionary Attack)
   - **Cracked Password:** `password1`
   - **Captured Flag:** `nw{networkwalks_flag1_jtr_270521_1}`

---

## Key Security Takeaways
- Weak or dictionary-based passwords on encrypted documents can be recovered rapidly once the password hash is extracted.
- Enforcing strong, high-entropy passphrases (12+ characters with mixed case, numbers, and symbols) significantly increases resistance against offline dictionary and brute-force attacks.

---

## Evidences Included
- `1_NW_Hash_Calculator.png` — PDF hash extraction using Networkwalks Hash Calculator
- `2_NW_Password_Cracker.png` — Dictionary attack recovery (`password1`)
- `3_NW_Unlocked_Flag1.png` — Unlocked PDF flag proof (`W3-PM2`)
- `4_Kali_JTR_Crack.png` — John the Ripper CLI execution on Kali Linux
- `5_Kali_JTR_Show.png` — Verification of cracked password (`good-luck`)
- `6_JTR_Unlocked_Flag2.png` — Unlocked PDF flag proof (`W3-PM1`)
