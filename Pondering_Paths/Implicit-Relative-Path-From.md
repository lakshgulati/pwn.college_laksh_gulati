# Challenge Name
Implicit Relative Path From

## My solve
**Flag:** `pwn.college{My2fN2w8DTgGY1rSyhHFtlk8Rc9.QX5QTN0wSOyMzNzEzW}`

```bash
Connected!
hacker@paths~implicit-relative-paths-from-:~$ /challenge/run
Incorrect...
You are not currently in the / directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~implicit-relative-paths-from-:~$ cd /
hacker@paths~implicit-relative-paths-from-:/$ /challenge/run
Incorrect...
You invoked this challenge with an absolute path. This challenge needs a relative path!
hacker@paths~implicit-relative-paths-from-:/$ challenge/run
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{My2fN2w8DTgGY1rSyhHFtlk8Rc9.QX5QTN0wSOyMzNzEzW}
hacker@paths~implicit-relative-paths-from-:/$
```
## Incorrect tangents I went on
Put aboslute path instead of the relative path

## What I learned
Learned how to access a program using relative path using the cwd

## References 
No outside reference used
