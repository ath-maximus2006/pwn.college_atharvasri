Flag : pwn.college{k9bPH5QuOAuQMtcqd0RZHCCEo9f.QX4QTN0wSMyAzNzEzW}
# Change Directory then Run

The challenge asks you to change your shell’s current working directory to a specific path (the path the level tells you) and then re-run the challenge program so it detects the correct working directory and prints the flag.

## My Solve

**Flag:** `pwn.college{k9bPH5QuOAuQMtcqd0RZHCCEo9f.QX4QTN0wSMyAzNzEzW}`

Steps I used:

1. `cd` into the directory specified by the challenge .
2. Run the /challenge/run program.


```
hacker@paths~position-yet-elsewhere:~$ cd /proc/131
hacker@paths~position-yet-elsewhere:/proc/131$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{k9bPH5QuOAuQMtcqd0RZHCCEo9f.QX4QTN0wSMyAzNzEzW}
```

## What I Learned

* How to use `cd` to change the current working directory.

## References

None

---
