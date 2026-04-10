## 🧠 Overview
This room introduced basic operating system security concepts using practical access through SSH.

---

## 🔍 What I Did

- Connected to a machine using SSH:
 ssh sammy@<target-ip>

- Entered a password to gain access as user **sammy**
- Then accessed another user:
 ssh johnny@<target-ip>

 - Guessed the password to log in as **johnny**
- Checked command history to find sensitive information:
  history

  - Found a root password that was mistakenly stored

- Switched to root user: su - root
 - Entered the password and gained root access

---

## ⚠️ Challenges

- I didn’t fully understand each step at first
- Some commands were confusing
- Remembering syntax was difficult

---

## 💡 Key Takeaways

- Weak passwords can lead to unauthorized access
- Command history can leak sensitive information
- Root access gives full control over the system
