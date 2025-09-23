# Challenge Name
Hidden Files

## My solve
**Flag:** `pwn.college{wCBjFEaXO316RFJhPPdUwpWLQ-w.QXwUDO0wSOyMzNzEzW}`

```bash
Connected!
hacker@commands~hidden-files:~$ ls / -a
.                    bin        etc    lib64   nix   run   tmp
..                   boot       home   libx32  opt   sbin  usr
.dockerenv           challenge  lib    media   proc  srv   var
.flag-2901590402567  dev        lib32  mnt     root  sys
hacker@commands~hidden-files:~$ cat /.flag-2901590402567
pwn.college{wCBjFEaXO316RFJhPPdUwpWLQ-w.QXwUDO0wSOyMzNzEzW}
hacker@commands~hidden-files:~$
```
## Incorrect tangents I went on
None

## What I learned
Learned how to show the hidden files that start with '.'

## References 
No outside reference used