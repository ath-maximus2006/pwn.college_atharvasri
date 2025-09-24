Flag : pwn.college{IjOhsm1gXK5fknINe1Oz7n33yEd.QXxMDO0wSMyAzNzEzW}
# Making Directories

### Learning to Cretae new directories

**Flag:** `pwn.college{IjOhsm1gXK5fknINe1Oz7n33yEd.QXxMDO0wSMyAzNzEzW}`

Using `mkdir` command, i created a  new directory called 'pwn' and then, i created a file inside 'pwn' using `touch` command, called 'college', and got the required flag.

```
hacker@commands~making-directories:~$ mkdir /tmp/pwn
hacker@commands~making-directories:~$ cd /tmp
hacker@commands~making-directories:/tmp$ ls
bin  hsperfdata_root  pwn  tmp.TpSOPGOVKK
hacker@commands~making-directories:/tmp$ touch college
hacker@commands~making-directories:/tmp$
college
hacker@commands~making-directories:/tmp$ /challenge/run
Success! Here is your flag:
pwn.college{IjOhsm1gXK5fknINe1Oz7n33yEd.QXxMDO0wSMyAzNzEzW}
```

## What I learned

1. I leanrt, how to create my own directories.

## References

None. 

---
