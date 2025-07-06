<p align="center">
  <img src="https://github.com/CJA-Cyberhack24/Linux-Essential-Introduction/blob/main/Penguin-Tales.png?raw=true" alt="Penguin-Tales Logo" width="200"/>
</p>


---

## 📁 `package_management/README.md`

```md
# 📦 Package Management

## 📖 Theory Summary
Linux systems use package managers for installing, updating, and removing software. This folder uses APT (Debian/Ubuntu) as a base.

## 🧪 Tasks
- Install essential tools: `curl`, `git`, `htop`, `tree`
- Automate installations with scripts
- Search and explore package metadata

## 💻 Starter Script
```bash
#!/bin/bash
sudo apt update && sudo apt install curl git htop tree -y
echo "Tools installed successfully!"

🗂️ Extras
- Log installation history with dpkg --list
- Compare alternative package managers (e.g. snap, flatpak)


