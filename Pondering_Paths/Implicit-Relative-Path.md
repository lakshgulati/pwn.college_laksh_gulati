# Challenge Name
Implicit Relative Path

## My solve
**Flag:** `pwn.college{Yo-g-yJMQT_vHaSN23UCXvcvbyg.QXxUTN0wSOyMzNzEzW}`

```bash
Connected!
hacker@paths~implicit-relative-path:~$ cd /challenge
hacker@paths~implicit-relative-path:/challenge$ ./run
Correct!!!
./run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{Yo-g-yJMQT_vHaSN23UCXvcvbyg.QXxUTN0wSOyMzNzEzW}
hacker@paths~implicit-relative-path:/challenge$
```
## Incorrect tangents I went on
None

## What I learned
Learned how to access a program using relative path using the '.' format. Linux avoids directly running the program file as a safety measure so you have to use implicit relative patht o specifically tell it to run the program.

## References 
No outside reference used
