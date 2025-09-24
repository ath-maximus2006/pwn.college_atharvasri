Flag : pwn.college{QGt9bOLWRwMS-q1zIrIpdURyE4y.QXxUTN0wSMyAzNzEzW}
# Run from current directory with `.`

The challenge asks you to run the `run` program while your current working directory is `/challenge`. Linux does not search the current directory for naked command names by default, so you must explicitly tell the shell to execute the program in the current directory using `.` (dot) — for example `./run`.

## My Solve

**Flag:** `pwn.college{QGt9bOLWRwMS-q1zIrIpdURyE4y.QXxUTN0wSMyAzNzEzW}`

Steps I used:

1. Change into the challenge directory.
2. Execute the local `run` program by prefixing it with `./` so the shell runs the file from the current directory.

```
hacker@dojo:~$ cd /challenge
hacker@dojo:/challenge$ ./run
```

## What I Learned
* `.` means “current directory”;
* `./program` runs `program` from the directory you’re currently in.
* This behavior is a safety feature to avoid unintentionally executing local files that the system utilities.

## References

* None

---
