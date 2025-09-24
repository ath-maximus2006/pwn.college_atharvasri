Flag : pwn.college{cXC0l3DP4SDL4FjC79gAQ8gjfXS.QX2QTN0wSMyAzNzEzW}

# Change Directory then Run

The challenge asks you to change your shell’s current working directory to a specific path (the path the level tells you) and then re-run the challenge program so it detects the correct working directory and prints the flag.

## My Solve

**Flag:** `pwn.college{cXC0l3DP4SDL4FjC79gAQ8gjfXS.QX2QTN0wSMyAzNzEzW}`

Steps I used:

1. `cd` into the directory specified by the challenge .
2. Run the /challenge/run program.

Errors:
1. I did a mistake by firectly running the program fron the default directory.

' ' '
hacker@paths~position-thy-self:~$ /challenge/run
Incorrect...
You are not currently in the /usr/bin directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-thy-self:~$ cd /usr/bin
hacker@paths~position-thy-self:/usr/bin$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{cXC0l3DP4SDL4FjC79gAQ8gjfXS.QX2QTN0wSMyAzNzEzW}
hacker@paths~position-thy-self:/usr/bin$
' ' '

## What I Learned

* How to use `cd` to change the current working directory.

## References

None

---
