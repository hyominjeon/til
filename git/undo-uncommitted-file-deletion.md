# Undoing deleting a file

Today I accidentally deleted a file that I should not have and was in this state:
```
2017-04-03 11:23:07 ~/my-repo my-branch*
$ git status
On branch my-branch
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	deleted:    path/to/my/file/MyFile.java
```
I followed what git told me to do to unstage the file...
```
2017-04-03 11:23:42 ~/my-repo my-branch*
$ git reset
Unstaged changes after reset:
D	path/to/my/file/MyFile.java
```
and was able to restore the deleted file!
```
2017-04-03 11:23:59 ~/my-repo my-branch*
$ git checkout path/to/my/file/MyFile.java
```

_The journey of a git idiot continues..._
