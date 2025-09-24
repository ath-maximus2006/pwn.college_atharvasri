Flag : pwn.college{Mqr0Alr-cSBXmbzDKK3ewKY2cXq.QXwUDO0wSMyAzNzEzW}
# Hidden Files
### Learning to See hidden files

**Flag:** `pwn.college{Mqr0Alr-cSBXmbzDKK3ewKY2cXq.QXwUDO0wSMyAzNzEzW}`

First, i went to the '/' directory using `cd`. Then, I used the `ls` command to list all the files. Then I used `ls -a` to list the files starting with a '.'. And i found my desired file. 
Then I used the `cat` command to look inside the file and found my flag.

```
hacker@commands~hidden-files:~$ cd /
hacker@commands~hidden-files:/$ ls
bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ ls -a
.   .dockerenv            bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-97902522025859  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ cat .flag-97902522025859
pwn.college{Mqr0Alr-cSBXmbzDKK3ewKY2cXq.QXwUDO0wSMyAzNzEzW}
```

## What I learned

1. I learned to list hidden file i.e. files starting with a '.'.
2. I also learnt the linux, by default display files having names that begin with a '.' if we use the simple 'ls' function.

## References

None.

---
