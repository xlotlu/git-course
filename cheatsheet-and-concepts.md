# Shell

two very important shell commands you need to know:

cd target
 - changes directory
dir
 - lists directory contents

## using cd:

```
cd Desktop\new_project_one
:: ^^ this was a "relative" path
::    relative to the starting point
::    which was C:\Users\My-User
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

remember, inside the shell ↑ (arrow up) and ↓ (arrow down) recall the previous commands.

when you are in a pager (you can tell because on the bottom line you have a ":", to exit press "q")


when in trouble,
Ctrl+C stops most applications (except for the pager)



more working with the shell:
selection and Enter = copy
right click = paste




# git concepts

"staging" --> means things are not committed yet, but are prepared for commit

3 states:
- 1) untracked file
- 2) staged for commit (added with git add)
- 3) tracked (commited)


# git cheatsheet / things to know

dacă scrieți
git commit file1 file2
se face automat git add, fără să fie nevoie de el explicit în prealabil

git commit fără -m
va deschide editorul default
pentru a scrie commit message-ul



# when lost in Vim:

Vim: a "multi-modal" text editor, that is driven with "commands".

command mode is entered with ":"

the quit command is "quit", or short "q".
commands can be forced with "!"

comenzile importante de vim:
- w (write)
- q (quit)
- x (write and quit)

we said multi-modal. to enter Insert mode press "i"
to exit any mode, press Esc



