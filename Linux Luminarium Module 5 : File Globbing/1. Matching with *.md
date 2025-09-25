Flag : pwn.college{cjAeiO4UNTOKlkeAy9cixH3G7fx.QXxIDO0wSMyAzNzEzW}
# Matching with *

### Accessing Files without using full names or paths

**Flag:** `pwn.college{cjAeiO4UNTOKlkeAy9cixH3G7fx.QXxIDO0wSMyAzNzEzW}`

I used the `*` symbol after `/cha` to let the cd command in the shell take me to the challenge directory automatically.

```
hacker@globbing~matching-with-:~$ cd /ch*
hacker@globbing~matching-with-:/challenge$ /challenge/run
You ran me with the working directory of /challenge! Here is your flag:
pwn.college{cjAeiO4UNTOKlkeAy9cixH3G7fx.QXxIDO0wSMyAzNzEzW}
```

## What I learned

1. I learned to save time by using the `*` symbol after only a few characters of a file name or path.

## References

None. 

---
