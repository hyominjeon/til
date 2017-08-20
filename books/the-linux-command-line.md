# The Linux Command Line

## Part 1 Learning the Shell

### Chapter 1 What is the Shell

```
$ date
Sat Aug 19 21:01:13 PDT 2017
```
```
$ cal
    August 2017
Su Mo Tu We Th Fr Sa
       1  2  3  4  5
 6  7  8  9 10 11 12
13 14 15 16 17 18 19
20 21 22 23 24 25 26
27 28 29 30 31
```
```
$ df
Filesystem    512-blocks      Used Available Capacity iused      ifree %iused  Mounted on
/dev/disk1     974716928 435311240 538893688    45% 2049815 4292917464    0%   /
devfs                373       373         0   100%     647          0  100%   /dev
map -hosts             0         0         0   100%       0          0  100%   /net
```
```
$ exit
logout
Saving session...
...copying shared history...
...saving history...truncating history files...
...completed.

[Process completed]
```

### Chapter 2 Navigation

```
$ pwd
/Users/hyomin
```
```
$ ls
Applications		Library			Sites			Desktop			Movies
Documents		Music   Downloads		Pictures		Public
```
```
$ pwd
/Users/hyomin
$ cd /Users
$ cd ..
$ pwd
/Users
```
```
$ pwd
/Users
$ cd ./hyomin
$ cd hyomin
$ pwd
/Users/hyomin
```
```
$ pwd
/Users/hyomin
$ cd ../..
$ pwd
/
$ cd -
$ pwd
/Users/hyomin
```
