# Exercise 04: Networking

## Goal
Practice basic networking commands.

## Tasks
1. Display your IP address:
   ```bash
   ip addr show
   ```

2. Ping bing.com 5 times:

```bash 
ping -c 5 bing.com
```

3. Show all listening ports:

```bash
ss -tuln
```


4. Use curl to fetch the homepage of example.com:

```bash
curl example.com -o site.html
```

5. Show the first 10 lines of site.html:

```bash
head site.html
```

---

# Verification

Check `site.html` was created.

Confirm network commands work.
