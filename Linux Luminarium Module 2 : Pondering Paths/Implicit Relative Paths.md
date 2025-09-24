Flag : pwn.college{8HkM0crcl3NZf-n2nhLUQ85kUKF.QX5QTN0wSMyAzNzEzW}
# Relative Path from `/` (starts with "c")

The challenge asks you to execute the challenge program using a relative path (not an absolute path) while your current working directory (cwd) is `/`. The hint says the relative path starts with the letter `c` — from `/` that path is `challenge/run`.

## My Solve

**Flag:** `pwn.college{8HkM0crcl3NZf-n2nhLUQ85kUKF.QX5QTN0wSMyAzNzEzW}`

Steps I used:

1. Change the shell's current working directory to the root directory `/`.
2. Run the program using the relative path `challenge/run`.

```
hacker@dojo:~$ cd /
hacker@dojo:/$ challenge/run
```


## What I Learned

* The difference between absolute and relative paths.
* From `/`, a relative path like `challenge/run` points to `/challenge/run`.

## References

None

---
