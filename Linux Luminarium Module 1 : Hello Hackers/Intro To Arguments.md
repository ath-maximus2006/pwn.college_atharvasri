Flag : pwn.college{oSyF3CX8lm27N9XOjhlLA8fy8yH.QX4YjM1wSMyAzNzEzW}
# Arguments: `hello hackers`

The challenge asks you to run a command with arguments. You must invoke the `hello` command with a single argument `hackers` (commands and arguments are case sensitive) to obtain the flag.

## My Solve

**Flag:** `pwn.college{oSyF3CX8lm27N9XOjhlLA8fy8yH.QX4YjM1wSMyAzNzEzW}`

I solved the level by running `hello` with the `hackers` argument. The shell uses the first word as the command and the rest as arguments, so `hello hackers` invokes `hello` and passes `hackers` as the argument. The command then prints the flag(pasted above).

```
hacker@dojo:~$ hello hackers
Success! Here is your flag:
pwn.college{oSyF3CX8lm27N9XOjhlLA8fy8yH.QX4YjM1wSMyAzNzEzW}
hacker@dojo:~$
```

## What I Learned

* How the shell splits input into a command and arguments: the first word is the command, subsequent words are arguments.
* That many simple utilities (like `echo`) print their arguments back, while challenge binaries (like `hello`) may use arguments to change behavior.
* The importance of exact casing and spacing when invoking commands.

## References

* None

---
