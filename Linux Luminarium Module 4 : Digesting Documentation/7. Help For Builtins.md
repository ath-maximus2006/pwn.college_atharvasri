Flag : pwn.college{ww7d0kce5Y6INAKPRwVp06fF241.QX0ETO0wSMyAzNzEzW}
# Help for Builtins

### To understand and use shell builtins

**Flag:** `pwn.college{ww7d0kce5Y6INAKPRwVp06fF241.QX0ETO0wSMyAzNzEzW}`

First I invoked the `help` command with 'challenge' and then followed the steps within to get the flag.

```
hacker@man~help-for-builtins:~$ help challenge
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!

    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value
    is "ww7d0kce".
hacker@man~help-for-builtins:~$ challenge --secret ww7d0kce
Correct! Here is your flag!
pwn.college{ww7d0kce5Y6INAKPRwVp06fF241.QX0ETO0wSMyAzNzEzW}
```

## What I learned

1. I learned the concept of shell builtins like 'cd'.
2. I also learned hwo to access them using the `help` command.

## References

None. 

---
