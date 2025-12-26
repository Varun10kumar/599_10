Microsoft Windows [Version 10.0.22621.4317]
(c) Microsoft Corporation. All rights reserved.

D:\599>git config --global user.email"lingampallyvarun34@gmail.com"

D:\599>config --global user.name"Varun10kumar"
'config' is not recognized as an internal or external command,
operable program or batch file.

D:\599>config --global user.name"Varun10kumar"
'config' is not recognized as an internal or external command,
operable program or batch file.

D:\599>git init
Initialized empty Git repository in D:/599/.git/

D:\599>git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

D:\599>notepad 1.txt

D:\599>notepad sample.html

D:\599>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        1.txt
        sample.html

nothing added to commit but untracked files present (use "git add" to track)

D:\599>git add 1.txt

D:\599>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   1.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        sample.html


D:\599>git add sample.html

D:\599>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   1.txt
        new file:   sample.html


D:\599>git commit -m "2 files are added"
[master (root-commit) d8f42f5] 2 files are added
 2 files changed, 7 insertions(+)
 create mode 100644 1.txt
 create mode 100644 sample.html

D:\599>git remote add origin https://github.com/Varun10kumar/599_10.git

D:\599>git push -u origin master
remote: Permission to Varun10kumar/599_10.git denied to Devi9063.
fatal: unable to access 'https://github.com/Varun10kumar/599_10.git/': The requested URL returned error: 403

D:\599>git push -u origin master
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 334 bytes | 334.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Varun10kumar/599_10.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

D:\599>git push -u origin master
branch 'master' set up to track 'origin/master'.
Everything up-to-date

D:\599>git branch
* master

D:\599>git branch csea

D:\599>git branch
  csea
* master

D:\599>git checkout csea
Switched to branch 'csea'

D:\599>git branch
* csea
  master

D:\599>notepad demo.html

D:\599>git status
On branch csea
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        demo.html

nothing added to commit but untracked files present (use "git add" to track)

D:\599>git add demo.html

D:\599>git status
On branch csea
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   demo.html


D:\599>git commit -m "demo file added"
[csea fb2adb7] demo file added
 1 file changed, 5 insertions(+)
 create mode 100644 demo.html

D:\599>git push -u origin csea
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 364 bytes | 364.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'csea' on GitHub by visiting:
remote:      https://github.com/Varun10kumar/599_10/pull/new/csea
remote:
To https://github.com/Varun10kumar/599_10.git
 * [new branch]      csea -> csea
branch 'csea' set up to track 'origin/csea'.

D:\599>git branch
* csea
  master

D:\599>git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

D:\599>git checkout csea
Switched to branch 'csea'
Your branch is up to date with 'origin/csea'.

D:\599>git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

D:\599>git merge csea
Updating d8f42f5..fb2adb7
Fast-forward
 demo.html | 5 +++++
 1 file changed, 5 insertions(+)
 create mode 100644 demo.html

D:\599>git push -u origin master
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Varun10kumar/599_10.git
   d8f42f5..fb2adb7  master -> master
branch 'master' set up to track 'origin/master'.

D:\599>git branch -d csea
Deleted branch csea (was fb2adb7).

D:\599>git push origin --delete csea
To https://github.com/Varun10kumar/599_10.git
 - [deleted]         csea

D:\599>
