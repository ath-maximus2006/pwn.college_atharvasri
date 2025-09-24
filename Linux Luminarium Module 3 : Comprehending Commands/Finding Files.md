Flag : pwn.college{kcDHLDxtdoEMfqoIEFZITMIXOaW.QXyMDO0wSMyAzNzEzW}
# Finding Files

### Finding a file based on cerain criteria

**Flag:** `pwn.college{kcDHLDxtdoEMfqoIEFZITMIXOaW.QXyMDO0wSMyAzNzEzW}`

I used the `find` command with a `-name` criteria to search for `flag`.

```
hacker@commands~finding-files:~$ cd /
hacker@commands~finding-files:/$ find -name flag
hacker@commands~finding-files:/$ cat ./usr/lib/debug/.build-id/84/flag
pwn.college{kcDHLDxtdoEMfqoIEFZITMIXOaW.QXyMDO0wSMyAzNzEzW}
```

## What I learned

1. I learnt how to find files in a certain directory using certain criteria like its name.

## References

None.

---
