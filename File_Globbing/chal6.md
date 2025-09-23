# Challenge Name
Mixing globs

## My solve
**Flag:** `pwn.college{EHC3PATiE6eZh0grcY_l7XkS7DZ.QX1IDO0wSOyMzNzEzW}`

```bash
Connected!
hacker@globbing~mixing-globs:~$ cd /challenge/files
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run [c*e*p*]
Error: your argument is too long! It must be 6 characters or less.
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run *n*
Error: you did not use a square bracket glob...
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run *[in]*
Your expansion did not expand to the requested files (challenging, educational,
pwning). Instead, it expanded to:
amazing beautiful challenging delightful educational fantastic incredible jovial kind laughing magical nice optimistic pwning queenly radiant splendid thrilling uplifting victorious wonderful xenial
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run [cep]*
You got it! Here is your flag!
pwn.college{EHC3PATiE6eZh0grcY_l7XkS7DZ.QX1IDO0wSOyMzNzEzW}
hacker@globbing~mixing-globs:/challenge/files$
```
## Incorrect tangents I went on
None

## What I learned
Learned how to use different globes in a single argument

## References 
No outside reference used