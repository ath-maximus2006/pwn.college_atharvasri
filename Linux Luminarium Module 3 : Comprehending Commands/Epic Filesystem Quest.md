Flag : pwn.college{oSC__aV7Q_PSQgrovi8nDucPQME.QX5IDO0wSMyAzNzEzW}
# Epic FileSystem Quest

### Testing the previously learnt skills

**Flag:** `pwn.college{oSC__aV7Q_PSQgrovi8nDucPQME.QX5IDO0wSMyAzNzEzW}`

In this challenge, i had to use `cat`, `ls` and `cd` and `ls -a` plenty of times, to go from one directory to another based on the clues i was uncovering.

```
hacker@commands~an-epic-filesystem-quest:~$ cd /
hacker@commands~an-epic-filesystem-quest:/$ ls
TEASER  boot       dev  flag  lib    lib64   media  nix  proc  run   srv  tmp  var
bin     challenge  etc  home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~an-epic-filesystem-quest:/$ cat TEASER
Lucky listing!
The next clue is in: /opt/linux/linux-5.4/include/linux/netfilter_bridge

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/$ cd /opt/linux/linux-5.4/include/linux/netfilter_bridge
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/linux/netfilter_bridge$ ls -a
.  ..  .DISPATCH  ebtables.h
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/linux/netfilter_bridge$ cat .DISPATCH
Lucky listing!
The next clue is in: /usr/share/fish/vendor_conf.d

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/linux/netfilter_bridge$ ls -a /usr/share/fish/vendor_conf.d
.  ..  BLUEPRINT-TRAPPED
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/linux/netfilter_bridge$ cat /usr/share/fish/vendor_conf.d/BLUEPRINT-TRAPPED
Great sleuthing!
The next clue is in: /usr/lib/python3/dist-packages/hamcrest/library/number

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/linux/netfilter_bridge$ ls -a /usr/lib/python3/dist-packages/hamcrest/library/number
.  ..  .CUE  __init__.py  __pycache__  iscloseto.py  ordering_comparison.py
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/include/linux/netfilter_bridge$ cd /usr/lib/python3/dist-packages/hamcrest/library/number
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/hamcrest/library/number$ ls -a
.  ..  .CUE  __init__.py  __pycache__  iscloseto.py  ordering_comparison.py
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/hamcrest/library/number$ cat .CUE
Great sleuthing!
The next clue is in: /usr/share/vim/vim81/lang/no/LC_MESSAGES

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/hamcrest/library/number$ cd /usr/share/vim/vim81/lang/no/LC_MESSAGES
hacker@commands~an-epic-filesystem-quest:/usr/share/vim/vim81/lang/no/LC_MESSAGES$ ls -a
.  ..  EVIDENCE  vim.mo
hacker@commands~an-epic-filesystem-quest:/usr/share/vim/vim81/lang/no/LC_MESSAGES$ cat EVIDENCE
Tubular find!
The next clue is in: /opt/linux/linux-5.4/Documentation/driver-api/thermal
hacker@commands~an-epic-filesystem-quest:/usr/share/vim/vim81/lang/no/LC_MESSAGES$ cd /opt/linux/linux-5.4/Documentation/driver-api/thermal
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/Documentation/driver-api/thermal$ ls -a
.     cpu-cooling-api.rst           index.rst             power_allocator.rst
..    exynos_thermal.rst            intel_powerclamp.rst  sysfs-api.rst
CLUE  exynos_thermal_emulation.rst  nouveau_thermal.rst   x86_pkg_temperature_thermal.rst
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/Documentation/driver-api/thermal$ cat CLUE
Yahaha, you found me!
The next clue is in: /usr/share/doc/libgc1c2
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/Documentation/driver-api/thermal$ cd /usr/share/doc/libgc1c2
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libgc1c2$ ls -a
.               README.amiga.gz        README.ews4800    README.solaris2      debugging.html     porting.html
..              README.arm.cross       README.hp         README.symbian       finalization.html  scale.html
AUTHORS.gz      README.autoconf        README.linux.gz   README.uts           gc.man.gz          simple_example.html
DOSSIER         README.cmake           README.macros.gz  README.win32.gz      gcdescr.html       tree.html
README.DGUX386  README.cords           README.md.gz      README.win64         gcinterface.html
README.Mac.gz   README.darwin.gz       README.rs6000     changelog.Debian.gz  leak.html
README.OS2      README.environment.gz  README.sgi        copyright            overview.html
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libgc1c2$ cat DOSSIER
Yahaha, you found me!
The next clue is in: /opt/linux/linux-5.4/drivers/media/dvb-frontends/drx39xyj
hacker@commands~an-epic-filesystem-quest:/usr/share/doc/libgc1c2$ cd /opt/linux/linux-5.4/drivers/media/dvb-frontends/drx39xyj
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/media/dvb-frontends/drx39xyj$ ls -a
.   GIST     Makefile    drx_dap_fasi.h  drx_driver_version.h  drxj.h
..  Kconfig  drx39xxj.h  drx_driver.h    drxj.c                drxj_map.h
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/media/dvb-frontends/drx39xyj$ cat GIST
Yahaha, you found me!
The next clue is in: /usr/share/doc/libasound2/examples

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/media/dvb-frontends/drx39xyj$ ls -a /usr/share/doc/libasound2/examples
.  ..  NOTE-TRAPPED  asoundrc.txt
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/media/dvb-frontends/drx39xyj$ cat /usr/share/doc/libasound2/examples/NOTE-TRAPPED
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{oSC__aV7Q_PSQgrovi8nDucPQME.QX5IDO0wSMyAzNzEzW}
```

## What I learned

1. I practiced the stuff i learnt in almost all the previous challenges.

## References

pwn.college SENSAI
