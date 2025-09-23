# Challenge Name
Comparing Files

## My solve
**Flag:** `pwn.college{kYEj7cvge9LyriLYUXspTCDOQnd.01MwMDOxwSOyMzNzEzW}`

```bash
laksh_hacks@LAPTOP-P8BBEDMJ:~$ ssh -i key hacker@dojo.pwn.college
Connected!
hacker@commands~comparing-files:~$ diff /challenge/decoys_only.txt /challenge/decoys_and_real.txt
17a18
> pwn.college{kYEj7cvge9LyriLYUXspTCDOQnd.01MwMDOxwSOyMzNzEzW}
hacker@commands~comparing-files:~$
```
## Incorrect tangents I went on
None

## What I learned
Learned how to know what's the difference between the two files using diff command and what does the 17a18 means (a stands for addition, c stands for change)

## References 
No outside reference used