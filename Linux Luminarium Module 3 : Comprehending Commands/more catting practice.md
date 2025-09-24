Flag : pwn.college{02HJ3aSkJgIG9MKIxgmbaZ7Rxfh.QXwITO0wSMyAzNzEzW}

# More Catting Practice

### Retrieving Files using 'cat' and their alsolute paths

**Flag:** `pwn.college{02HJ3aSkJgIG9MKIxgmbaZ7Rxfh.QXwITO0wSMyAzNzEzW}`

Here, the flag was hidden inside certain directories and I wasn't allowed to use cd to change directories. But i have learnt that, we can directly use absolute paths
with `cat` commands to access a file. So that's what I did.

```
hacker@commands~more-catting-practice:~$ cat /lib/python3.8/dbm/flag
pwn.college{02HJ3aSkJgIG9MKIxgmbaZ7Rxfh.QXwITO0wSMyAzNzEzW}
```

## What I learned

1. 'cat' can be used with complicated absolute paths without the need for `cd` command.

## References

None.

---
