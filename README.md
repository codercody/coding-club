# How to use git/Terminal command line

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

|Command|What it does|
|-------|------------|
|`ls`   |list the files in the current directory|
|`cd _` |change directory to `_`|
|`cd ..`|go to parent directory of current folder|
|`mv _ _`|move `_` to `_`|
|`mkdir _`|make new directory `_`|
|`rm _` |remove `_`|
|`[tab]`|autocomplete the directory/filename|
|`[up arrow]`|used to navigate through previous commands so you don't have to retype them|

# Schedule

|Date|Task|Assignment|
|----|----|----------|
|idk|learn Python|A Practical Introduction to Python Programming: Chapters 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 19, 20, 21, 22, 23, 24, 25, all exercises|
|idk|learn basic data structures and algorithms|All handouts in 15122 folder, all exercises|
|idk|learn the math behind computer science|All of 15251 notes, all exercises|
|idk|learn advanced algorithms|Algorithms: Chatpers 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 15 (very important), 16, 17, 21, 22, 23, 24, 25, 26, 29, 33 (optional), 34, 35, Appendices C, D, all exercises|

Here's a brief description of the content of each of the resources I have:

|Resource|Contents|
|--------|-----------|
|A Practical Introduction to Python Programming|getting started with Python, `for` loops, `if` statements, strings, lists, `while` loops, dictionaries, functions|
|15122|programming concepts, ints, arrays, searching/sorting algorithms, stacks/queues, linked lists, hash tables, binary search trees, BFS/DFS|
|15251|DFA's, Turing Machines, countable/uncountable sets, big O/Omega/Theta, graph algorithms, polynomial time reductions, P vs. NP, approximation algos, probability theory, randomized algorithms|
|Algorithms||
