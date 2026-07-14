# Hackathon Starter Template

Welcome to the official workspace template! This structure is designed to keep your project organized and clear for both your team and the evaluation committee.

---

## 📁 Repository Folder Structure

* **`/src`**: Place all application source code here (frontend, backend, components, etc.).
* **`/database`**: Store all database scripts, schemas, SQL dumps, or migration files here.
* **`/docs`**: Include your system documentation, Installation Guide, system architecture diagrams, and final presentation files here.

---

## 💡 Developer Tips & Best Practices

### 🔄 The Golden Rule of Git
* **Commit Early & Often:** Run `git add .`, `git commit -m "descriptive message"`, and `git push origin main` every 30 to 60 minutes.
* **Pull Before You Push:** Always run `git pull origin main` before starting new code to keep your local machine synchronized with your teammates.
* **Work on `main` Only:** Avoid creating extra Git branches to prevent complex merge conflicts under tight competition time.

---

## 🤖 How to Effectively Use AI Tools During Development

As per official guidelines, AI tools (ChatGPT, Claude, GitHub Copilot, etc.) are allowed for research, coding assistance, debugging, UI design, and documentation. To get the best results without breaking your codebase, follow the **"Brick-by-Brick" Method**:

### 1. Start Big (General Concept)
Begin with broad, high-level questions to outline system logic or architecture.
> **Example:** *"What is the best database structure for an inventory tracking system with role-based access?"*

### 2. Build Brick-by-Brick (Modular Development)
Never ask AI to generate an entire application or a 1,000-line file all at once—it often generates errors, hallucinated variables, or broken logic. Break your problem down into tiny, functional pieces:
* **Step A:** Ask AI for just the database schema/tables.
* **Step B:** Ask AI for just the login authentication API endpoint.
* **Step C:** Ask AI for just the UI component layout for the user table.

### 3. Understand What You Paste
> ⚠️ **Critical Reminder:** The evaluation criteria includes **Technical Understanding (20%)**. You must be able to explain all code and architecture during the Q&A session with the judges. If AI writes code for you, make sure you understand every line before committing it!