# Final Boss Challenge

## Goal
Combine everything into one useful script.

## Task
Write a script called `dailycheck.sh` that:
- Prints today’s date and time.
- Prints your username.
- Shows disk usage (`df -h`).
- Displays top 5 processes by memory usage.

## Example Script
```bash
#!/bin/bash
# Daily system check script

echo "===== Daily System Report ====="
date
echo "User: $(whoami)"
echo "Disk Usage:"
df -h | head -n 5
echo "Top 5 Memory-Hungry Processes:"
ps aux --sort=-%mem | head -n 6
```

Verification

1. Save it in ```scripts/dailycheck.sh```


2. Make it executable:
```bash
chmod +x scripts/dailycheck.sh
```

3. Run it:
```bash
./scripts/dailycheck.sh
```

4. Confirm it prints date, user, disk space, and process list.

