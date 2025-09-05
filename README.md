# **ACI_FooBar25_Q3**
### Q3 Challenge for ACI's 2025 FooBar Event
https://github.com/SimonAlex957/ACI_FooBar25_Q3
---

## **Overview**
This challenge focuses on **identifying and patching vulnerabilities** in a provided banking system. The more vulnerabilities you fix, the higher your score. This exercise will prepare you for the second phase, where you will defend your system against other teams.

---

## **Challenge Structure**
### **Part 1: Patch Vulnerabilities**
- Fork this repository and make your fork **private**.
- Add:
  - All your **team members**.
  - The account **`SimonAlex957`** as a collaborator.
- Clone your fork to your local machine.
- Whenever you fix a vulnerability:
  - Commit the changes to the **`main`** branch.
  - Each commit updates the **scoreboard** displayed in the room.

---

### **Part 2: Attack Another Team**
- You will be added as a collaborator to **another team’s repository** (and they will be removed).
- Your goal:
  - Find vulnerabilities they **missed**.
  - Exploit and patch them to **earn points**.
- Same process as Part 1: commit fixes to the `main` branch.

---

## **Setup Instructions**
1. **Fork the Repo**
   - Click **Fork** on GitHub.
   - Set visibility to **Private**.
2. **Add Collaborators**
   - Go to **Settings → Collaborators**.
   - Add your team members and `SimonAlex957`.
3. **Clone the Repo**
   ```bash
   git clone <your-fork-url>
   cd ACI_FooBar25_Q3
   ```
4. **Start Patching**
   - Identify vulnerabilities.
   - Fix them.
   - Commit and push:
     ```bash
     git add .
     git commit -m "Fixed vulnerability: <description>"
     git push origin main
     ```

---

## **Scoring**
- **Each patched vulnerability = points.**
- **More patches = better defense in Part 2.**
- Scoreboard updates automatically after each commit.

---

## **Tips for Success**
- **Document your fixes** in commit messages for clarity.
- **Think like an attacker**: What would you exploit?
- **Test thoroughly** after each patch.
- **Communicate with your team** to avoid duplicate work.
- **Prepare for Part 2**: The stronger your system, the harder it is to break.

---

## **Rules**
- Do **not** share your code outside your team.
- Do **not** attack other teams before Part 2.
- Follow ethical hacking guidelines.
