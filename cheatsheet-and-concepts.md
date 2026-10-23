# Shell

Two very important shell commands you need to know:

cd target
 - changes directory
dir
 - lists directory contents

## using cd:

```
cd Desktop\new_project_one
:: ^^ this was a "relative" path
::    (relative to the starting point
::     which was C:\Users\My-User)
```

```
cd C:\new_project_two
::  ^^ this is an "absolute" path
```

```
cd ..
::  ^ navigates to the parent folder
```

## other useful shell commands:

```
mkdir directory_name
```

```
:: write contents directly into a file:
echo some content > myfile.txt
```


## shell usage:

Remember, inside the shell `↑` (arrow up) and `↓` (arrow down) recall the previous commands.

When you are in a pager (you can tell because on the bottom line you have a "`:`") to exit press "`q`".

When in trouble,
Ctrl+C stops most applications (except for the pager).

Using the clipboard with the shell:
- select text and then `Enter`: copy
- right click: paste


# Git concepts

"staging": means things are not committed yet, but are prepared for commit.

3 states:
 1) untracked file
 2) staged for commit (added with git add)
 3) tracked (commited)

# git cheatsheet / things to know

dacă scrieți

```
git commit file1 file2
```
se face automat `git add`, fără să fie nevoie de el explicit în prealabil.

Atenție: `git commit` fără `-m`
va deschide editorul default
pentru a scrie commit message-ul.


# when lost in Vim:

Vim: a "multi-modal" text editor, that is driven with "commands".

Command mode is entered with "`:`"

- the quit command is "`quit`", or short "`q`".
- commands can be forced with "!"

Comenzile importante de vim:

- w (write)
- q (quit)
- x (write and quit)

We said multi-modal. To enter `Insert mode` press "`i`".

To exit any mode, press `Esc`.
