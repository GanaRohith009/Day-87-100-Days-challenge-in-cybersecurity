# Day-87-100-Days-challenge-in-cybersecurity
# 🛡️ Day 87: Injection Vulnerabilities

## 📝 Overview
Today’s focus was on **Injection**, a critical vulnerability where untrusted user input is sent to an interpreter (SQL, OS Shell, etc.) as part of a command. This allows an attacker to "inject" malicious code that the system then executes.

## 🧱 The Lego Analogy
* **Injection:** Like sticking a "malicious instruction" note over a manual. The builder (interpreter) just follows whatever is on top.
* **Parameterized Query:** Like having a pre-defined "brick slot." No matter what is written on the brick, the builder knows it's just a part, not a new instruction.

## ⚠️ Key Findings
| Concept | Security Risk |
| :--- | :--- |
| **Untrusted Input** | Headers, cookies, and form fields can all be hostile. |
| **The Interpreter** | SQL engines or OS shells that can't distinguish data from code. |
| **The Domino Effect** | Single service accounts allow a minor bug to compromise the whole DB. |

## 🛡️ Best Practices for 2026
- [ ] **Use Parameterized Queries:** Always separate code from data.
- [ ] **Input Validation:** Enforce strict types and lengths server-side.
- [ ] **Generic Errors:** Never reveal database versions or query structures in UI errors.
- [ ] **Principle of Least Privilege:** Ensure the DB user has only the permissions it needs.

## 📸 Visuals
![Injection Attack vs Defense](your_image_link_here.png)

---
*Part of my #100DaysOfCyberSecurity journey.*
