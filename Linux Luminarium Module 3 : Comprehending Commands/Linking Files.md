Flag : pwn.college{wTBBlntw-A1VEXcqS4Gu83LZV09.QX5ETN1wSMyAzNzEzW}
# Linking Files

### Learning to create a create symbolic link between two files

**Flag:** `pwn.college{wTBBlntw-A1VEXcqS4Gu83LZV09.QX5ETN1wSMyAzNzEzW}`

Here, i used the `ln -s` command to create a symbolic link between `/flag` an the given file path. The i ran the final command to get the flag.

```
hacker@commands~linking-files:~$ ln -s /flag /home/hacker/not-the-flag
hacker@commands~linking-files:~$ /challenge/catflag
About to read out the /home/hacker/not-the-flag file!
pwn.college{wTBBlntw-A1VEXcqS4Gu83LZV09.QX5ETN1wSMyAzNzEzW}
```

## What I learned

1. I learnt how to create a symbolic link between files.
2. I learnt the use of `file` command : It tells us the file type.
3. I learnt the difference between hard link and soft/symbolic link.

## References

None.

---
