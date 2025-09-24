Flag : pwn.college{M-Yek66V7dkKma6-B4P6YD7QXo6.QX2kDM1wSMyAzNzEzW}
# Removing Files

### Learning to delete files

**Flag:** `pwn.college{M-Yek66V7dkKma6-B4P6YD7QXo6.QX2kDM1wSMyAzNzEzW}`

First i checked the files in the home directory using the `ls` command. Then i used the `rm` command to remove the required file.

```
hacker@commands~removing-files:~$ ls
a  delete_me  s
hacker@commands~removing-files:~$ rm delete_me
hacker@commands~removing-files:~$ ls
a  s
hacker@commands~removing-files:~$ /challenge/check
Excellent removal. Here is your reward:
pwn.college{M-Yek66V7dkKma6-B4P6YD7QXo6.QX2kDM1wSMyAzNzEzW}
```

## What I learned

1. I learned a simple way to remove files using the 'rm' function.

## References

None.

---
