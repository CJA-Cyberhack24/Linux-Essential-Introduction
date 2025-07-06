<p align="center">
  <img src="https://github.com/CJA-Cyberhack24/Linux-Essential-Introduction/blob/main/Penguin-Tales.png?raw=true" alt="Penguin-Tales Logo" width="200"/>
</p>
---

## 📁 `permissions/README.md`

```md
# 🔐 Permissions & Ownership

## 📖 Theory Summary
File access in Linux is governed by user, group, and others. This section explores `chmod`, `chown`, and permission notation.

## 🧪 Tasks
- Change file permissions using symbolic and numeric modes
- Practice `chown` to transfer file ownership
- Analyze file modes using `ls -l` and interpret results

## 💻 Starter Script
```bash
#!/bin/bash
touch secure.txt
chmod 600 secure.txt
chown $USER:$USER secure.txt
echo "Secure file created and locked down."

🗂️ Extras
- Explore umask to set default permissions
- Create permission cheat sheet (explain_permissions.txt)