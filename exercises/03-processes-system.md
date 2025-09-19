# Exercise 03: Processes & System

----

## Goal
Learn how to monitor and manage processes.

## Tasks
1. Start a background process:
   ```bash
   sleep 200 &
   ```

2. Find its PID using:
```
ps aux | grep sleep
```

3. Kill the process using:
```
kill -9 <PID>
```

4. Check system uptime:
```
uptime
```

5. Display free memory:
```
free -h
```

6. Show disk usage:
```
df -h
```

7. Run `top` and identify the process using the most CPU.



Verification

Confirm the process is killed ```(ps aux | grep sleep should return nothing).
```
Take note of system uptime, memory, and CPU usage.
