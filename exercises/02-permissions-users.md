# Exercise 02: Permissions & Users

## Goal
Understand Linux permissions and user management.

## Tasks
1. Create a file called `secret.txt` and write `Top Secret: Cyberflex` inside.
2. Change its permissions so **only the owner can read/write** (`chmod 600`).
3. Create a new user called `guest`.
4. Switch to the `guest` user and try reading `secret.txt` (it should fail).
5. Switch back to your main user.
6. Change permissions to allow **read-only access** for others (`chmod 644`).
7. Switch to `guest` again and verify they can read but not edit the file.

## Verification
- Run `ls -l secret.txt` after each permission change.
- Test file access with both users.

