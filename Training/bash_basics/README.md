<p align="center">
  <img src="https://github.com/CJA-Cyberhack24/Linux-Essential-Introduction/blob/main/Penguin-Tales.png?raw=true" alt="Penguin-Tales Logo" width="200"/>
</p>


# 🧰 Bash Basics

## 📖 Theory Summary
This section covers essential shell commands used to navigate and manage the Linux filesystem.

## 🧪 Tasks
- Navigate directories with `cd`, `pwd`
- List files using variations of `ls`
- Create and delete files using `touch`, `rm`, `mkdir`

## 💻 Starter Script
```bash
#!/bin/bash
mkdir -p ~/LinuxLab/{Notes,Scripts,Backups}
touch ~/LinuxLab/Notes/welcome.txt
echo "Lab setup complete!" > ~/LinuxLab/Notes/welcome.txt

🗂️ Extras
- Try combining multiple commands with && or ;
- Record command history: history > command_log.txt


