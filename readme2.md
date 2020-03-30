# ovo je potupak iz CMD-a:

Microsoft Windows [Version 10.0.18362.720]
(c) 2019 Microsoft Corporation. All rights reserved.

C:\Users\Ivana>f:

F:\> cd parcijalni-ispit-master

F:\parcijalni-ispit-master>git status
fatal: not a git repository (or any of the parent directories): .git

F:\parcijalni-ispit-master>git init
Initialized empty Git repository in F:/parcijalni-ispit-master/.git/

F:\parcijalni-ispit-master>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        app.js
        assets/
        index.css
        index.html
        package-lock.json
        package.json

nothing added to commit but untracked files present (use "git add" to track)

F:\parcijalni-ispit-master>git add .
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in app.js.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in index.css.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in index.html.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in package-lock.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in package.json.
The file will have its original line endings in your working directory

F:\parcijalni-ispit-master>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   app.js
        new file:   assets/HP1.jpg
        new file:   index.css
        new file:   index.html
        new file:   package-lock.json
        new file:   package.json


F:\parcijalni-ispit-master>git commit -m "upload mastera"
[master (root-commit) 7d68944] upload mastera
 7 files changed, 505 insertions(+)
 create mode 100644 README.md
 create mode 100644 app.js
 create mode 100644 assets/HP1.jpg
 create mode 100644 index.css
 create mode 100644 index.html
 create mode 100644 package-lock.json
 create mode 100644 package.json

F:\parcijalni-ispit-master>git status
On branch master
nothing to commit, working tree clean

F:\parcijalni-ispit-master>git remote add origin https://github.com/ivanashoo/parcijalni.git

F:\parcijalni-ispit-master>git push -u origin master
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 6 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (10/10), 53.94 KiB | 10.79 MiB/s, done.
Total 10 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ivanashoo/parcijalni.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

F:\parcijalni-ispit-master>git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

F:\parcijalni-ispit-master>git checkout -b ivana-supljika
Switched to a new branch 'ivana-supljika'

F:\parcijalni-ispit-master>git add .
warning: LF will be replaced by CRLF in index.html.
The file will have its original line endings in your working directory

F:\parcijalni-ispit-master>git status
On branch ivana-supljika
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html


F:\parcijalni-ispit-master>git commit -m "Parcijalni: Ivana Supljika"
[ivana-supljika 0f93240] Parcijalni: Ivana Supljika
 1 file changed, 2 insertions(+)

F:\parcijalni-ispit-master>git status
On branch ivana-supljika
nothing to commit, working tree clean

F:\parcijalni-ispit-master>git branch -a
* ivana-supljika
  master
  remotes/origin/master

F:\parcijalni-ispit-master>git push -u origin ivana-supljika
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 6 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 371 bytes | 371.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ivana-supljika' on GitHub by visiting:
remote:      https://github.com/ivanashoo/parcijalni/pull/new/ivana-supljika
remote:
To https://github.com/ivanashoo/parcijalni.git
 * [new branch]      ivana-supljika -> ivana-supljika
Branch 'ivana-supljika' set up to track remote branch 'ivana-supljika' from 'origin'.

F:\parcijalni-ispit-master>