# What is git?

Git is a version controlling system.

## How to create a git project

There are two ways to use git in an project

    1. Creat project on local machine and use 'git init'.
    2. Create repository online and clone that in to ur local system.

## How git works internally?

![Alt text](../git_in_detail.png)

## Important git commands

    1. what is rebase?
    2. what is stash?
    3. How to unstage changes? 
        git rm --cached <file>

## Important scenerios in git

    1. What happen if we stage a file and make change in working directory to same file after staging?
        ANS : Due to above scenerio a difference between staging area and working directory file will arise due to
        which we will not be able to unstage the file by using 'git rm --cached <file>'.
        Now we have three options:
       1. Whatever new changes we have in working directory file will be copied to staging area file.
        This can be done by again staging that file by using 'git add <file>'
       2. Discard the changes in working directory file so that it can be similar to that of staging area file.
        by using 'git restore <file>'
    3.
    2. How to see differences between staging area and working directory files?
        ANS : 'git diff'

Note: ls command is used to see list of file in linux.

> run git init to initialize git

example:

```java
public static void main(String[] args) {

}
```

## Features of java

1. easy
2. platform independent
3. distributed
4. multi-threaded
5. secure
![Alt text](../proxy_layer.png)
