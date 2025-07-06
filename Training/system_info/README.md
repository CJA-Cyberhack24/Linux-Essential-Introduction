<p align="center">
  <img src="https://github.com/CJA-Cyberhack24/Linux-Essential-Introduction/blob/main/Penguin-Tales.png?raw=true" alt="Penguin-Tales Logo" width="200"/>
</p>


---

## 📁 `system_info/README.md`

```md
# 🖥️ System Info & Diagnostics

## 📖 Theory Summary
Monitoring system health is vital for security and performance. This section covers tools that provide insights into CPU, RAM, disk, and system events.

## 🧪 Tasks
- Extract system metrics using `top`, `free`, `df`, `uptime`
- Analyze logs with `journalctl` and `dmesg`
- Build a system dashboard with output logs

## 💻 Starter Script
```bash
#!/bin/bash
echo "=== System Report ===" > sysreport.txt
echo "Uptime: $(uptime)" >> sysreport.txt
echo "Memory: $(free -h)" >> sysreport.txt
echo "Disk Usage: $(df -h)" >> sysreport.txt

🗂️ Extras
- Record top 10 largest directories using du
- Explore parsing log files with grep

---

Would you like me to create a summary section for recruiters or collaborators at the top of each one, or help add visuals like ASCII dividers or icons to make them pop? We can level this up however you like 🌟


