<p align="center">
  <img src="https://github.com/CJA-Cyberhack24/Linux-Essential-Introduction/blob/main/Penguin-Tales.png?raw=true" alt="Penguin-Tales Logo" width="200"/>
</p>
---

# 🛡️ Week 7: Security-Oriented Scripts

## 📖 Overview

This section bridges Linux fundamentals with real-world security awareness. You'll dive into basic auditing, log observation, and scripting techniques that support system integrity—great skills for aspiring cybersecurity analysts.

## 🧠 Key Focus Areas

- File monitoring and tamper detection
- Login audits from system logs
- Network connection analysis
- Simple alert mechanisms via scripting

---

## 🧪 Tasks & Concepts

### ✅ File Auditing with `stat` and `diff`
- Create a script that tracks changes in critical files (e.g., `/etc/passwd`).
- Log timestamp, size, and hash comparison.

### ✅ Login Audit from Logs
- Use `journalctl`, `last`, and `grep` to detect unusual login attempts.
- Script a basic filter that flags login outside office hours.

### ✅ Network Awareness
- Monitor connections with `netstat`, `ss`, or `lsof`.
- Extract suspicious outbound IPs or unusual port activity.

### ✅ Alert Script Demo
- Automate a script that triggers a notification when a specific log keyword is found.
- Use cron to schedule hourly scans.

---

## 💻 Sample Audit Script

```bash
#!/bin/bash
FILE="/etc/passwd"
SNAPSHOT="snapshot.txt"
HASH_BEFORE=$(md5sum $FILE)

sleep 10  # Simulate time delay or changes

HASH_AFTER=$(md5sum $FILE)

if [ "$HASH_BEFORE" != "$HASH_AFTER" ]; then
    echo "ALERT: $FILE has been modified!" >> audit_log.txt
else
    echo "No changes detected." >> audit_log.txt
fi
