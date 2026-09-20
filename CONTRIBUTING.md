# Contributing Guidelines

Welcome! Please read these rules carefully before contributing.

---

## 📜 Copyright & Ownership

| Topic | Rule |
|-------|------|
| **Your Lumos** | You retain full copyright on your submitted Custom Lumos |
| **Other People's Lumos** | Not yours – respect creator attribution |
| **Repository Framework** | Licensed under MIT (see LICENSE) |
| **Proton Trademark** | We do NOT claim affiliation with Proton AG |

When you submit, you agree that:
- Others may use your Lumo configuration freely
- You keep moral attribution (your name stays credited)
- Proton-related trademarks remain their property

---

## 📥 How to Contribute

### Option A: Pull Request (Recommended)
1. Fork this repository.
2. Create a new branch (`git checkout -b feature/my-lumo-name`).
3. Create a `.md` file in the appropriate folder (`lumos/<category>/`).
4. Commit and push.
5. Create a Pull Request here.

### Option B: Open an Issue
If you need help or have questions, open an Issue first.

---

## 📋 Template for Custom Lumos

**Always** use this structure. Copy `templates/LUMA_TEMPLATE.md` and fill in the fields:

```markdown
# [Lumo Name]

**Category:** [productivity/tech-support/funny/etc.]
**Author:** [@GithubUsername]
**Created On:** YYYY-MM-DD

## ⚙️ Configuration

### Name
> [Name for your Custom Lumo in the app]

### Description (Optional)
> [Short internal note on what this Lumo does]

### Instructions (System Prompt)
```text
[PASTE YOUR EXACT SYSTEM PROMPT HERE]

[Ensure it starts with the role, defines behavior, and sets boundaries.]
