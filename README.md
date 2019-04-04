# How to use git

Github is a website used to store all your files. It's basically like dropbox. To start, do the following command from the Terminal command line:

```
git clone https://github.com/codercody/coding-club.git
```

This copies all the Git code to whatever directory you are in on your Terminal command line. Now every time you make a new file, you will use

```
git add [path/to/file1] [path/to/file2] [...]
git commit -m "[brief description of what work you did]"
git push origin master
```

to put all of your stuff on Github. Make sure you are working in the right folder (`ben/` or `rithvik/`). Here is a brief cheat sheet of commands useful for navigating through file directories from the Terminal command line:

|command|what it does|
|-------|------------|
|`ls`   |list the files in the current directory|
|`cd _` |change directory to `_`|
|`cd ..`|go to parent directory of current folder|
|`mv _ _`|move `_` to `_`|
|`mkdir _`|make new directory `_`|
|`rm _` |remove `_`|
|`[tab]`|autocomplete the directory/filename|
