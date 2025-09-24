Flag : pwn.college{AL2K0sa5lmGQ9ysdn3sWdtx3fwx.0VOxEzNxwSMyAzNzEzW}
# Moving Files

### Learning to change locations of files

**Flag:** `pwn.college{AL2K0sa5lmGQ9ysdn3sWdtx3fwx.0VOxEzNxwSMyAzNzEzW}`

I used the `mv` command to change the location of the given file to the desired location. 

```
hacker@commands~moving-files:~$ mv /flag /tmp/hack-the-planet
Correct! Performing 'mv /flag /tmp/hack-the-planet'.
hacker@commands~moving-files:~$ /challenge/check
Congrats! You successfully moved the flag to /tmp/hack-the-planet! Here it is:
pwn.college{AL2K0sa5lmGQ9ysdn3sWdtx3fwx.0VOxEzNxwSMyAzNzEzW}

```

## What I learned

1. I learned about using the `mv` command to move a file to a particular location.

## References

https://www.guru99.com/must-know-linux-commands.html#moving-and-renaming-files
