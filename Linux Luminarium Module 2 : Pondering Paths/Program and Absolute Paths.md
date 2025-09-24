Flag : pwn.college{closRIVODJTZ4iq0pOqHN7Jzvor.QX1QTN0wSMyAzNzEzW}
# Run from a Subdirectory: `/challenge/run`

The challenge asks you to execute a program that lives in the `/challenge` directory by invoking its absolute path `/challenge/run` to obtain the flag.

## My Solve

**Flag:** `pwn.college{closRIVODJTZ4iq0pOqHN7Jzvor.QX1QTN0wSMyAzNzEzW}`

I opened the DOJO terminal and invoked the program using its absolute path. Because the program is located in `/challenge`, the full path to run is `/challenge/run`. Running that exact path executes the program and prints the flag.

```
hacker@dojo:~$ /challenge/run
```

## What I Learned

* How to open a file by its absolute path, e.g., `/challenge/run`.
* The difference between `run`, `./run`, and `/challenge/run`:

## References

None

---
