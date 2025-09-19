## Stage 1: Orientation

Goal: Get comfortable moving around and knowing “where you are.”
Exercises:

1. Open a terminal. Run:
```bash
whoami
uname -a
pwd
```

→ Note your username, kernel version, and current directory.


2. Create a practice directory in your home folder:
```bash
mkdir ~/linux_practice
cd ~/linux_practice
```

3. Use:
```
ls
ls -l
ls -a
```
→ Observe differences between normal listing, long listing, and hidden files.

---

## Stage 2: File & Directory Kung Fu

Goal: Create, move, copy, rename, delete, explore.
Exercises:

1. Create files:
```bash
touch file1.txt file2.txt
echo "Hello Kali" > file1.txt
echo "Cyberflex rocks Linux" >> file1.txt
```

2. Show contents:
```bash
cat file1.txt
head file1.txt
tail file1.txt
```

3. Copy, move, and rename:
```bash
cp file1.txt copy.txt
mv copy.txt renamed.txt
```

4. Remove files & directories:
```bash
rm file2.txt
mkdir test_dir
rmdir test_dir
```
(Try rm -r test_dir if the folder has stuff inside.)

---

## Stage 3: User & Permission Wizardry

Goal: Understand ownership and permissions.
Exercises:

1. Run:
```
ls -l
```
→ Look at permission flags (rwx).


2. Change file permissions:
```
chmod 600 file1.txt
chmod +x file1.txt
```
→ Check before/after with ls -l.


3. Create a new user (needs sudo/root):
```
sudo adduser testuser
su - testuser
whoami
exit
```

---

## Stage 4: Process & System Control

Goal: Monitor and control your system.
Exercises:

1. Check running processes:
```
ps aux | less
top
```

2. Kill a process:
```
sleep 300 &
ps aux | grep sleep
kill -9 <PID>
```

3. Check system info:
```
free -h
df -h
uptime
```
---

## Stage 5: Networking Basics

Goal: Use networking commands built into Linux.
Exercises:

1. Show your IP:
```
ip addr show
```

2. Test connectivity:
```
ping -c 4 google.com
```

3. Check open ports:
```
ss -tuln
```
---

## Stage 6: Power Tools (Searching & Scripting)

Goal: Search and automate.
Exercises:

1. Find text inside a file:
```
grep "Kali" file1.txt
```

2. Search the filesystem:
```
find ~ -name "*.txt"
```

3. Write a small script:
```
nano hello.sh
```
Inside:
```
#!/bin/bash
echo "Hello, Linux world!"
```
Save, then run:
```
chmod +x hello.sh
./hello.sh
```

---

## Stage 7: Daily Practice Drill

Every day, try this “warm-up”:
```
pwd
ls -l
date
whoami
uptime
df -h
```

This helps reinforce memory.

