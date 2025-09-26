Flag : pwn.college{MKgou7lpIDP_iWG3GWJa44v-SjC.0lM3kjNxwSMyAzNzEzW}
# Multiple Globs

### Using multiple `*`s while globbing a file

**Flag:** `pwn.college{MKgou7lpIDP_iWG3GWJa44v-SjC.0lM3kjNxwSMyAzNzEzW}`

Here, i used `*` multiple times in a single argument, so search for all possible files containing a certain 'string' or 'symbol'.

```
hacker@globbing~multiple-globs:~$ cd /challenge/files
hacker@globbing~multiple-globs:/challenge/files$ cat *p*
hacker@globbing~multiple-globs:/challenge/files$ /challenge/run *p*
You got it! Here is your flag!
pwn.college{MKgou7lpIDP_iWG3GWJa44v-SjC.0lM3kjNxwSMyAzNzEzW}
```

## What I learned

1. I learned that, we can use * multiple times in an argument to expand the scope of what we're searching for.

## References

None.

---
