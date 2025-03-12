
admin@DESKTOP-F22EK55 MINGW64 ~ (master)
$ mkdir labb7

admin@DESKTOP-F22EK55 MINGW64 ~ (master)
$ cd labb7

admin@DESKTOP-F22EK55 MINGW64 ~/labb7 (master)
$ git init
Initialized empty Git repository in C:/Users/admin/labb7/.git/

admin@DESKTOP-F22EK55 MINGW64 ~/labb7 (master)
$ git add .

admin@DESKTOP-F22EK55 MINGW64 ~/labb7 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   das1.py
        new file:   das2.py
        new file:   das3.py
        new file:   das4.py
        new file:   das5.py


admin@DESKTOP-F22EK55 MINGW64 ~/labb7 (master)
$ git commit -m "okee"
[master (root-commit) cd0651c] okee
 5 files changed, 47 insertions(+)
 create mode 100644 das1.py
 create mode 100644 das2.py
 create mode 100644 das3.py
 create mode 100644 das4.py
 create mode 100644 das5.py

admin@DESKTOP-F22EK55 MINGW64 ~/labb7 (master)
$ git brach -M main
git: 'brach' is not a git command. See 'git --help'.

The most similar command is
        branch

admin@DESKTOP-F22EK55 MINGW64 ~/labb7 (master)
$ git branch -M main

admin@DESKTOP-F22EK55 MINGW64 ~/labb7 (main)
$ git remote add origin https://github.com/byambaa50/lab_7.git

admin@DESKTOP-F22EK55 MINGW64 ~/labb7 (main)
$ git branch -M main

admin@DESKTOP-F22EK55 MINGW64 ~/labb7 (main)
$ git push -u origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 853 bytes | 853.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/byambaa50/lab_7.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

