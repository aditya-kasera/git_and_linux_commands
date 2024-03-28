> This repository has Linux and git commands I practised and would refer in future.

[Click](https://github.com/aditya-kasera/git_and_linux_commands/blob/main/Notes%20-%20LInux%20%26%20Git.one) and download Linux and Git Commmands' Onenote notes.

---

```

aditya@Laptop MINGW64 /d/DEVELOPMENT/Git/Linux Commands (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

aditya@Laptop MINGW64 /d/DEVELOPMENT/Git/Linux Commands (main)
$ git remote
origin

aditya@Laptop MINGW64 /d/DEVELOPMENT/Git/Linux Commands (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Git Commands.txt

nothing added to commit but untracked files present (use "git add" to track)

aditya@Laptop MINGW64 /d/DEVELOPMENT/Git/Linux Commands (main)
$ git add .

aditya@Laptop MINGW64 /d/DEVELOPMENT/Git/Linux Commands (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Git Commands.txt

aditya@Laptop MINGW64 /d/DEVELOPMENT/Git/Linux Commands (main)
$ git commit -m "second commit"
[main 88a7886] second commit
 1 file changed, 81 insertions(+)
 create mode 100644 Git Commands.txt

aditya@Laptop MINGW64 /d/DEVELOPMENT/Git/Linux Commands (main)
$ git branch -m main

aditya@Laptop MINGW64 /d/DEVELOPMENT/Git/Linux Commands (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 931 bytes | 931.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/aditya-kasera/git_and_linux_commands.git
   cc15384..88a7886  main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

aditya@Laptop MINGW64 /d/DEVELOPMENT/Git/Linux Commands (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

```
