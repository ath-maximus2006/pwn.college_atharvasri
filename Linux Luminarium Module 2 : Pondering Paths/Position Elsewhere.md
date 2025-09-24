Flag : pwn.college{Mbc8te2pbxueAuJN13Q4KvThMkY.QX3QTN0wSMyAzNzEzW}
# Change Directory then Run

The challenge asks you to change your shell’s current working directory to a path the level specifies, then execute the `/challenge/run` program from there to obtain the flag.

## My Solve

**Flag:** `pwn.college{Mbc8te2pbxueAuJN13Q4KvThMkY.QX3QTN0wSMyAzNzEzW}`

Steps I used (replace `<required-path>` with the directory the level tells you):

1. Change into the required directory with `cd`.
2. Run the challenge program while my current working directory is set.

```
hacker@paths~position-elsewhere:~$ cd /usr/share/doc/fontconfig
hacker@paths~position-elsewhere:/usr/share/doc/fontconfig$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{Mbc8te2pbxueAuJN13Q4KvThMkY.QX3QTN0wSMyAzNzEzW}
```

## What I Learned

* How to use `cd` to change the current working directory.
## References

* None

---
