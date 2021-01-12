---
title: Software Engineering Questions
author: by Ultan
---

 

Introduction
------------

 

Some questions from, or relevant to, the course.

 

Questions
---------

 

**Shell**

 

-   What is the shell?

-   What is `$PATH`?

-   What is `.`, `..` and `~` in a file path?

-   Where is `/`?

-   What does pwd, cd, mv, cp, mkdir, chmod, rm, rmdir, ls, man, which, echo,
    cat, sudo, sha256sum, curl do? Give an example of each

-   What does each of cd -, rm -r, ls -l, ls -a do?

-   What are the modes for a directory?

-   What is the user ID of root?

-   How do you override the default input/output streams?

-   How would you append to a file?

-   What is a pipe?

-   Why is the xargs program useful?

 

**Shell Tools and Scripting**

 

-   What is \$0, \$1 to \$9, \$\@, \$\@, \$\#, \$?, \$\$, !!, \$_?

-   Syntax for variables? How do you echo variables?

-   What return code indicates no issues?

-   How do you separate commands on the same line?

-   What is command substitution? Give an example

-   What is process substitution? Give an example

-   Write a function to make a directory and cd into it

-   Write a for loop and in if statement

-   What is a shebang? Give a shebang for python

-   What is shell globbing? Give an example to move all \*.py and \*.sh files to
    a new folder

-   Give an example of using diff

-   What is touch useful for?

-   Find all directories named source. Find all directories named source (case
    insensitive)

-   Use grep to recursively look through a directories

-   How do you see your command history?

-   What does starting a command with a leading space do?

-   What is the shortcut CTRL+R used for?

 

**Vim**

 

-   What are the modes in Vim?

-   What are buffers, tabs and windows in Vim?

-   What are nouns in Vim?

-   What are verbs in Vim?

-   Where do you put Vim plugins?

-   What do these regular expressions do: ., \*, +, [abc], (RX1\|RX2), \^, \$ ?

 

**Command-Line Environment**

 

-   What does CTRL+c do?

-   What does CTRL+\\ do?

-   What does kill -TERM \<PID\> do?

-   What does Ctrl+z do?

-   What are fg and bg used for?

-   What does jobs do?

-   How do you refer to a process?

-   What does the & suffix in a command do?

-   What does disown allow you to do?

-   What is a daemon?

-   How do aliases persist across shell sessions?

-   Make a simple alias

-   How do you ignore an alias?

-   Where are dot files located?

-   How do you connect over SSH? How do you do key-based authentication?

-   How to grep locally remote output? How to grep remotely local output?

-   Give two methods for copying files to a remote server over SSH?

-   Explain how to port forward using an example

 

**Version Control (Git)**

 

-   Explain the Git data model (snapshots, modelling history, data model as
    pseudocode, objects and content-addressing, references and repositories)

-   What is the staging area?

-   What do the following do?

    -   git help \<command\>

    -   git init

    -   git status

    -   git add \<filename\>

    -   git add \<filename\> -u

    -   git commit -m “message"

    -   git log

    -   git log -all -graph decorate

    -   git diff \<filename\>

    -   git diff \<revision\> \<filename\>

    -   git checkout \<revision\>

-   How do you show the branches?

-   How do you create a branch?

-   How do you create a branch and switch to it?

-   How do you create a branch based off existing branch and switch to it?

-   How do you merge into the current branch?

-   How do you rebase a set of patches onto a new base? Illustrate with a
    diagram

-   How do you resolve a merge conflict?

-   How do you list remotes?

-   How do you add to the remote?

-   How do you send object to a remote and update the remote reference?

-   How do you set up correspondence between the local and remote branch?

-   How do you retrieve objects/references from a remote?

-   What does git pull do?

-   What is git clone used for?

-   How do you edit a commits content message?

-   How do you unstage a file?

-   How do you discard changes of a file?

-   How do you clone without the entire version history?

-   How to check who edited which line last?

-   What is git stash and git stash pop useful for?

 

**Debugging**

 

-   Discuss debugging referring to print statements, logging and debuggers

 

**Metaprogramming**

 

-   Give an example of a simple makefile to compile a c file and a c header file

-   Explain the semantic versioning format

-   What is a lock file?

-   What is vendoring?

-   Explain at a high level what how a CI system operates

-   What is a test suite, unit test, integration test, regression test and
    mocking?

-   In Markdown how do you: write a bullet, a list, italic text, bold text,
    headings, code, code font and links?

 

**Virtual Machines and Containers**

 

-   What is a virtual machine?

-   What is a container?

 

**Android Studio**

 

-   What is the device file explorer?

-   What is the layout editor?

-   What is a constraint layout?

-   Why is the Gradle build system useful?
