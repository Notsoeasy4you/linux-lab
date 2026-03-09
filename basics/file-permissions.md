# Linux File Permissions

## Viewing permissions

Command:
ls -l

Example output:
-rwxr-xr-- 1 user user 0 Mar 1 test.sh

Explanation:
r = read
w = write
x = execute

---

## Changing permissions

Command:
chmod

Examples:

chmod +x script.sh
chmod 755 script.sh
chmod 644 file.txt

---

## Changing ownership

Command:
chown

Example:

sudo chown user:file file.txt
