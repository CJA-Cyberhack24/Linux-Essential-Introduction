<p align="center">
  <img src="https://github.com/CJA-Cyberhack24/Linux-Essential-Introduction/blob/main/Penguin-Tales.png?raw=true" alt="Penguin-Tales Logo" width="200"/>
</p>


---

## 📁 `automation/README.md`

```md
# 🤖 Shell Scripting & Automation

## 📖 Theory Summary
Shell scripting brings Linux automation to life. This section explores scripting logic and scheduled tasks.

## 🧪 Tasks
- Create interactive scripts with input/output
- Log outputs to timestamped files
- Schedule cron jobs for recurring tasks

## 💻 Starter Script
```bash
#!/bin/bash
echo "Welcome, $1! Today is $(date)" >> welcome_log.txt

🗂️ Crontab Example
0 8 * * * /home/cj/linux-lab-portfolio/automation/greeting_logger.sh



