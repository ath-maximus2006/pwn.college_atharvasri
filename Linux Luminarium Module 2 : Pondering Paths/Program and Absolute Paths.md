Flag : pwn.college{closRIVODJTZ4iq0pOqHN7Jzvor.QX1QTN0wSMyAzNzEzW}
# Run from a Subdirectory: `/challenge/run`

The challenge asks you to execute a program that lives in the `/challenge` directory by writing its absolute path `/challenge/run` to get the flag.

## My Solve

**Flag:** `pwn.college{closRIVODJTZ4iq0pOqHN7Jzvor.QX1QTN0wSMyAzNzEzW}`

I opened the terminal and invoked the program using its absolute path. Because the program is located in `/challenge`, the full path to run is `/challenge/run`. Running that exact path executes the program and gives us the flag.

```
hacker@dojo:~$ /challenge/run
```

## What I Learned

* How to open a file by its absolute path, e.g., `/challenge/run`.
* The difference between `run`, `./run`, and `/challenge/run`:

## References

None

---
