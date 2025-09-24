 Flag : pwn.college{Ahkf8Wt1gTryK1IjcgSeGT30Y3d.QXzMDO0wSMyAzNzEzW}
# Using `~` (Home Directory) with Absolute Paths

The challenge asks you to run `/challenge/run` and save a copy of the flag to a file inside your home directory. You must provide an **absolute path** that uses the `~` shorthand and is three characters or less before expansion.

## My Solve

**Flag:** `pwn.college{Ahkf8Wt1gTryK1IjcgSeGT30Y3d.QXzMDO0wSMyAzNzEzW}`

Steps I used:

1. Understand that `~` expands to `/home/hacker`, so a path like `~/f` is interpreted as `/home/hacker/f`.
2. Pick a filename of one character (i picked `a`) to satisfy the “three characters or less” requirement.
3. Run the program with the required path argument.

```
hacker@dojo:~$ /challenge/run ~/a
```


## What I Learned

* `~` is shorthand for the current user’s home directory.
* shell expands `~` only when it is the leading component of a path.
* How to write files to a location in your home directory using absolute paths with `~`.

## References

* None

---
