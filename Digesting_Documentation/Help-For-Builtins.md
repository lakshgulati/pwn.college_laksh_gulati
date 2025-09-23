# Challenge Name
Help For Builtins

## My solve
**Flag:** `pwn.college{sp-YQaAKHoKZdbSJr9Q_3phmlpo.QX0ETO0wSOyMzNzEzW}`

```bash
Connected!
hacker@man~help-for-builtins:~$ help challenge
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!

    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value
    is "sp-YQaAK".
hacker@man~help-for-builtins:~$ challenge --secret sp-YQaAK
Correct! Here is your flag!
pwn.college{sp-YQaAKHoKZdbSJr9Q_3phmlpo.QX0ETO0wSOyMzNzEzW}

hacker@man~help-for-builtins:~$
```
## Incorrect tangents I went on
None

## What I learned
Learned how to use help command to get help for the builtins functions

## References 
No outside reference used