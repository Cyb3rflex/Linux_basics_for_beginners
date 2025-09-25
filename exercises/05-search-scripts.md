# Exercise 05: Search & Scripts

## Goal
Learn to search files and create simple scripts.

## Tasks
1. Create a file called `notes.txt` with three lines:

I love Kali Linux is life Cyberflex forever

2. Search for the word `Linux` inside the file:
```bash
grep "Linux" notes.txt
```
3. Find notes.txt anywhere in your home directory:
```bash
find ~ -name "notes.txt"
```

4. Create a script called motivation.sh:
```bash
nano motivation.sh
```
Add:
```bash
#!/bin/bash
echo "Stay sharp, Cyberflex."
echo "Hack the planet."
```

5. Make it executable and run:
```bash
chmod +x motivation.sh
./motivation.sh
```


Verification

`grep` should return the correct line.

find should locate `notes.txt`

Running `motivation.sh` should display the two lines.
