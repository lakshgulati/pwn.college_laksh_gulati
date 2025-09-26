# Challenge Name
Exporting Variables

## My solve
**Flag:** `pwn.college{QTSBI5WWhflt64MUOFwvy9oJeFt.QXyYTN0wSOyMzNzEzW}`

```bash
Connected!
hacker@variables~exporting-variables:~$ COLLEGE=PWN
You've set the COLLEGE variable to the proper value!
hacker@variables~exporting-variables:~$ export PWN=COLLEGE
You've set the PWN variable to the proper value!
You've set the COLLEGE variable to the proper value!
hacker@variables~exporting-variables:~$ /challenge/run
CORRECT!
You have exported PWN=COLLEGE and set, but not exported, COLLEGE=PWN. Great
job! Here is your flag:
pwn.college{QTSBI5WWhflt64MUOFwvy9oJeFt.QXyYTN0wSOyMzNzEzW}
You've set the PWN variable to the proper value!
You've set the COLLEGE variable to the proper value!
hacker@variables~exporting-variables:~$
```
## Incorrect tangents I went on
None

## What I learned
Learned how to export a variable from the parent shell using the export command.

## References 
No outside reference used