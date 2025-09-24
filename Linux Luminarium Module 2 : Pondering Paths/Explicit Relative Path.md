Flag : pwn.college{8RRZhUII22axJSLd8OCOJN5QNaP.QXwUTN0wSMyAzNzEzW}
# Using `.` in Relative Paths

The challenge asks you to run the challenge program using explicit relative paths that include the `.` entry (which refers to the current directory). Use `.` in the path to demonstrate that it refers to the same directory and still resolves to the same executable.

## My Solve

**Flag:** `pwn.college{8RRZhUII22axJSLd8OCOJN5QNaP.QXwUTN0wSMyAzNzEzW}`

I solved the level by running `./challenge/run` via a relative path that includes `.`. From the root directory `/` the `.` refers to `/` itself, so paths like `./challenge/run` are the same as `/challenge/run`.

```
hacker@dojo:~$ cd /
hacker@dojo:/$ ./challenge/run

```

## What I Learned

* `.` refers to the current directory and can be safely used inside paths without changing which file is accessed.
* How to make explicit relative paths like `./challenge/./run`.

## References

* None

---
