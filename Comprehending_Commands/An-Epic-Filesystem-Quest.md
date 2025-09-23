# Challenge Name
An Epic Filesystem Quest

## My solve
**Flag:** `pwn.college{cHOVOo68ITcRr-u5ez5r1WcwMVV.QX5IDO0wSOyMzNzEzW}`

```bash
Connected!
hacker@commands~an-epic-filesystem-quest:~$ ls /
INFO  challenge  flag  lib32   media  opt   run   sys  var
bin   dev        home  lib64   mnt    proc  sbin  tmp
boot  etc        lib   libx32  nix    root  srv   usr
hacker@commands~an-epic-filesystem-quest:~$ cat /INFO
Lucky listing!
The next clue is in: /usr/lib/python3/dist-packages/sympy/polys/benchmarks/__pycache__

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:~$ ls /usr/lib/python3/dist-packages/sympy/polys/benchmarks
__init__.py  bench_galoispolys.py    bench_solvers.py
__pycache__  bench_groebnertools.py
hacker@commands~an-epic-filesystem-quest:~$ ls /usr/lib/python3/dist-packages/sympy/polys/benchmarks/__pycache__
CLUE-TRAPPED                      bench_groebnertools.cpython-38.pyc
__init__.cpython-38.pyc           bench_solvers.cpython-38.pyc
bench_galoispolys.cpython-38.pyc
hacker@commands~an-epic-filesystem-quest:~$ cat /usr/lib/python3/dist-packag
es/sympy/polys/benchmarks/__pycache__/CLUE-TRAPPED
Tubular find!
The next clue is in: /usr/share/gcc/python/libstdcxx

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:~$ cd /usr/share/gcc/python/libstdcxx
hacker@commands~an-epic-filesystem-quest:/usr/share/gcc/python/libstdcxx$ ls
MESSAGE  __init__.py  v6
hacker@commands~an-epic-filesystem-quest:/usr/share/gcc/python/libstdcxx$ cat MESSAGE
Tubular find!
The next clue is in: /usr/lib/python3/dist-packages/cryptography/hazmat/backends/__pycache__

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/share/gcc/python/libstdcxx$ ls /usr/lib/python3/dist-packages/cryptography/hazmat/backends/__pycache__ -a
.  ..  .DOSSIER  __init__.cpython-38.pyc  interfaces.cpython-38.pyc
hacker@commands~an-epic-filesystem-quest:/usr/share/gcc/python/libstdcxx$ cat /usr/lib/python3/dist-packages/cryptography/hazmat/backends/__pycache__/.DOSSIER
Lucky listing!
The next clue is in: /opt/pwndbg/.venv/lib/python3.8/site-packages/pip/_vendor/pygments/filters/__pycache__
hacker@commands~an-epic-filesystem-quest:/usr/share/gcc/python/libstdcxx$ ls /opt/pwndbg/.venv/lib/python3.8/site-packages/pip/_vendor/pygments/filters/__pycache__
ALERT  __init__.cpython-38.pyc
hacker@commands~an-epic-filesystem-quest:/usr/share/gcc/python/libstdcxx$ cat /opt/pwndbg/.venv/lib/python3.8/site-packages/pip/_vendor/pygments/filters/__pycache__/ALERT
Tubular find!
The next clue is in: /opt/busybox/busybox-1.33.2/include/config/feature/telnetd

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/share/gcc/python/libstdcxx$ ls /opt/busybox/busybox-1.33.2/include/config/feature/telnetd -a
.  ..  .TRACE  inetd  standalone.h
hacker@commands~an-epic-filesystem-quest:/usr/share/gcc/python/libstdcxx$ cat /opt/busybox/busybox-1.33.2/include/config/feature/telnetd/.TRACE
Congratulations, you found the clue!
The next clue is in: /opt/linux/linux-5.4/tools/perf/arch/x86/tests
hacker@commands~an-epic-filesystem-quest:/usr/share/gcc/python/libstdcxx$ ls /opt/linux/linux-5.4/tools/perf/arch/x86/tests
Build                 gen-insn-x86-dat.sh  intel-pt-pkt-decoder-test.c
REVELATION            insn-x86-dat-32.c    perf-time-to-tsc.c
arch-tests.c          insn-x86-dat-64.c    rdpmc.c
bp-modify.c           insn-x86-dat-src.c   regs_load.S
dwarf-unwind.c        insn-x86.c
gen-insn-x86-dat.awk  intel-cqm.c
hacker@commands~an-epic-filesystem-quest:/usr/share/gcc/python/libstdcxx$ cat /opt/linux/linux-5.4/tools/perf/arch/x86/tests/REVELATION
Yahaha, you found me!
The next clue is in: /usr/share/locale/sk.cp1250
hacker@commands~an-epic-filesystem-quest:/usr/share/gcc/python/libstdcxx$ ls /usr/share/locale/sk.cp1250
BRIEF  LC_MESSAGES
hacker@commands~an-epic-filesystem-quest:/usr/share/gcc/python/libstdcxx$ cat /usr/share/locale/sk.cp1250/BRIEF
Tubular find!
The next clue is in: /usr/share/locale/nso

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/share/gcc/python/libstdcxx$ ls /usr/share/locale/nso
LC_MESSAGES  WHISPER-TRAPPED
hacker@commands~an-epic-filesystem-quest:/usr/share/gcc/python/libstdcxx$ cat /usr/share/locale/nso/WHISPER-TRAPPED
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{cHOVOo68ITcRr-u5ez5r1WcwMVV.QX5IDO0wSOyMzNzEzW}

hacker@commands~moving-files:~$
```
## Incorrect tangents I went on
None

## What I learned
Applied the knowledge of ls, cd, cat commands

## References 
No outside reference used