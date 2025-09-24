Flag : pwn.college{oX9Q3S3NX3Gn-dyUPaJCNOqzpWv.01MwMDOxwSMyAzNzEzW}
# Comparing Files

### To learn how to detect differences between two files using the linux shell

**Flag:** `pwn.college{oX9Q3S3NX3Gn-dyUPaJCNOqzpWv.01MwMDOxwSMyAzNzEzW}}`

Here, I used the `diff` command to figure the difference between the two given files, one of which contained the real flag.
```
hacker@commands~comparing-files:~$ diff /challenge/decoys_only.txt /challenge/decoys_and_real.txt
59a60
> pwn.college{oX9Q3S3NX3Gn-dyUPaJCNOqzpWv.01MwMDOxwSMyAzNzEzW}
```

## What I learned

1. I learned to use the `diff` command to find the differences between two files.

## References

None.

---
