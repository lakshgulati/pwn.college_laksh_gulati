# Challenge Name
Extracting specific sections of text

## My solve
**Flag:** `pwn.college{05YiVyX7kFM0QYP6llwSQxv_tE0.01NxEzNxwSOyMzNzEzW}`

```bash
Connected!
hacker@data~extracting-specific-sections-of-text:~$ /challenge/run | cut -d " " -f 2 | tr -d "\n"
pwn.college{05YiVyX7kFM0QYP6llwSQxv_tE0.01NxEzNxwSOyMzNzEzW}hacker@data~extracting-specific-sections-of-text:~$
```
## Incorrect tangents I went on
None

## What I learned
Learned hwo to extract the specific comlumn of text using cut command where d specifies the spearator and -f specifies the feild that needs to be extracted

## References 
No outside reference used