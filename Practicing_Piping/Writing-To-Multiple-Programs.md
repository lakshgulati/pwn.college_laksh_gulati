# Challenge Name
Writing to multiple programs

## My solve
**Flag:** `pwn.college{s21vhcxf2hLpnq4UPEciwE41_10.QXwgDN1wSOyMzNzEzW}`

```bash
Connected!
hacker@piping~writing-to-multiple-programs:~$ /challenge/hack | tee >(/challenge/the) | /challenge/planet
Congratulations, you have duplicated data into the input of two programs! Here
is your flag:
pwn.college{s21vhcxf2hLpnq4UPEciwE41_10.QXwgDN1wSOyMzNzEzW}
hacker@piping~writing-to-multiple-programs:~$
```
## Incorrect tangents I went on
None

## What I learned
Learned how to pass the output to multiple programs using tee and pipeline

## References 
No outside reference used