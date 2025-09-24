Flag : pwn.college{0H2aPQwsdMrntnzPBQ2ycY8BBB7.QXwMDO0wSMyAzNzEzW}
# Touching Files
### Learning to Create new files.

**Flag:** `Flag : pwn.college{0H2aPQwsdMrntnzPBQ2ycY8BBB7.QXwMDO0wSMyAzNzEzW}`

First, i created the 'pwn' file. Then i created the 'college' file. Both inside the 'tmp' directory. And then i gotthe flag by tping `/challenge/run`.

```
hacker@commands~touching-files:~$ touch /tmp/pwn
hacker@commands~touching-files:~$ touch /tmp/college
hacker@commands~touching-files:~$ ls /tmp
bin  college  hsperfdata_root  pwn  tmp.TpSOPGOVKK
hacker@commands~touching-files:~$ /challenge/run
Success! Here is your flag:
pwn.college{0H2aPQwsdMrntnzPBQ2ycY8BBB7.QXwMDO0wSMyAzNzEzW}
hacker@commands~touching-files:~$
```

## What I learned

1. I learnt to create new files in a particular directory.

## References

None.

---

