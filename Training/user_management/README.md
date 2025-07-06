<p align="center">
  <img src="https://github.com/CJA-Cyberhack24/Linux-Essential-Introduction/blob/main/Penguin-Tales.png?raw=true" alt="Penguin-Tales Logo" width="200"/>
</p>

---

## 📁 `user_management/README.md`

```md
# 👥 User & Group Management

## 📖 Theory Summary
Understanding users and groups is key for system organization and access control. This folder handles user creation, group setup, and modifications.

## 🧪 Tasks
- Add and delete users with custom shells
- Create groups and assign users
- Script automation for onboarding new users

## 💻 Starter Script
```bash
#!/bin/bash
sudo useradd -m -s /bin/bash analyst01
sudo passwd analyst01
sudo groupadd cyberteam
sudo usermod -aG cyberteam analyst01
echo "User analyst01 onboarded and grouped!"

🗂️ Extras
- Document command options
- Record default /etc/passwd and /etc/group entries
