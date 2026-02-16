# CiberLudus CTF Challenges

**Official Challenge Repository for CiberLudus Platform**  
Website: https://ciberludus.com

---

## 📋 Mission 1: El Bibliotecario Ninja (The Ninja Librarian)

**Difficulty:** Beginner  
**Learning Objective:** Google Dorks / OSINT Awareness  
**Scenario:** Patito Corp (Banking Subsidiary - Banco PatoFin)

### Challenge Description
Patito Corp, a banking technology subsidiary of Banco PatoFin, has accidentally exposed sensitive internal documents online. Your mission is to use Google Dorks (advanced search operators) to find leaked credentials in their system logs.

### Challenge Files
- **[log_022026.log](./log_022026.log)** - Internal system logs containing database credentials
- **[Banking-Top-Trends-FY26-Report-Final.pdf](./Banking-Top-Trends-FY26-Report-Final.pdf)** - Financial report (decoy)

### Hints
1. Use Google advanced search operators to find specific text patterns
2. Look for environment variables or configuration dumps
3. Database passwords often follow predictable formats
4. The flag format is: `patito{...}`

### Learning Outcomes
After completing this challenge, you will understand:
- How Google indexes public repositories
- The dangers of committing sensitive data to version control
- How attackers use OSINT to find credentials
- The importance of `.gitignore` and secret management tools

---

## 🎯 How to Play

1. Visit https://ciberludus.com
2. Click "Try Mission 1 Free"
3. Read the mission briefing
4. Use Google to find the password in these files
5. Submit the flag to validate your solution

---

## 🔒 Security Notice

**This is a controlled CTF environment.** All credentials and data in this repository are fictional and created specifically for educational cybersecurity training. Do not use these techniques on systems you don't own or have explicit permission to test.

---

## 📚 About CiberLudus

LUDUS is the first gamified cybersecurity awareness platform in LATAM that teaches non-technical users to think like attackers. 

- **Pricing:** $0.50 / user / month
- **Target:** Banks, FinTech, SMBs in Latin America
- **Philosophy:** "Si vis pacem, para bellum" (If you want peace, prepare for war)

Learn more: https://ciberludus.com

---

## 📄 License

These challenge materials are provided for educational purposes only under the MIT License.

Copyright (c) 2026 Teetech Security - https://www.teetech.com.ar
