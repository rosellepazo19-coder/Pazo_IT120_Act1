Roselle@DESKTOP-53FPVR6 MINGW64 ~
$ cd Desktop

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop
$ mkdir Pazo_IT120_Act1

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop
$ cd Pazo_IT120_Act1

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1
$ git init
Initialized empty Git repository in C:/Users/Roselle/Desktop/Pazo_IT120_Act1/.gi
t/

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (master)
$ git remote add origin https://github.com/rosellepazo19-coder/Pazo_IT120_Act1.git

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (master)
$ touch Profile.txt Education.txt Background.txt Readme.txt Test.py


Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (master)
$ git add .
warning: in the working copy of 'Test.py', LF will be replaced by CRLF the next
time Git touches it

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (master)
$ git commit -m "Initial commit with all files"
[master (root-commit) 6f28b33] Initial commit with all files
 5 files changed, 35 insertions(+)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 Test.py

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=schannel
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=rosellepazo19-coder
user.email=rosellepazo19@gmail.com
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/rosellepazo19-coder/Pazo_IT120_Act1.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (master)
$ git push origin master
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (7/7), 930 bytes | 155.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/rosellepazo19-coder/Pazo_IT120_Act1.git
 * [new branch]      master -> master

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (master)
$ git branch -M master

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (master)
$ git push -u origin master
branch 'master' set up to track 'origin/master'.
Everything up-to-date

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (master)
$ git checkout -b Pazo_B1
Switched to a new branch 'Pazo_B1'

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (Pazo_B1)
$ git branch
* Pazo_B1
  master

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (Pazo_B1)
$ git add Profile.txt

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (Pazo_B1)
$ $ git commit -m "Amend: added Birth of Place, Religion, Father's Name, Father's Occupation, Mother's Name, Occupation"
bash: $: command not found

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (Pazo_B1)
$  git commit -m "Amend: added Birth of Place, Religion, Father's Name, Father's Occupation, Mother's Name, Occupation"
[Pazo_B1 28829fe] Amend: added Birth of Place, Religion, Father's Name, Father's
 Occupation, Mother's Name, Occupation
 1 file changed, 8 insertions(+), 1 deletion(-)

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (Pazo_B1)
$ git push origin Pazo_B1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 515 bytes | 515.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Pazo_B1' on GitHub by visiting:
remote:      https://github.com/rosellepazo19-coder/Pazo_IT120_Act1/pull/new/Paz
o_B1
remote:
To https://github.com/rosellepazo19-coder/Pazo_IT120_Act1.git
 * [new branch]      Pazo_B1 -> Pazo_B1

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (Pazo_B1)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (master)
$ git checkout -b Pazo_B2
Switched to a new branch 'Pazo_B2'

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (Pazo_B2)
$ git add Education.txt

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (Pazo_B2)
$ git commit -m "Amend: updated Education.txt with details"
[Pazo_B2 e37d8b2] Amend: updated Education.txt with details
 1 file changed, 5 insertions(+), 1 deletion(-)

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (Pazo_B2)
$ git push origin Pazo_B2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 460 bytes | 460.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Pazo_B2' on GitHub by visiting:
remote:      https://github.com/rosellepazo19-coder/Pazo_IT120_Act1/pull/new/Paz
o_B2
remote:
To https://github.com/rosellepazo19-coder/Pazo_IT120_Act1.git
 * [new branch]      Pazo_B2 -> Pazo_B2

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (Pazo_B2)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (master)
$ git checkout -b Pazo_B3
Switched to a new branch 'Pazo_B3'

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (Pazo_B3)
$ git add Background.txt

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (Pazo_B3)
$ git rm Test.py
rm 'Test.py'

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (Pazo_B3)
$ git commit -m "Amend: updated Background.txt and removed Test.py"
[Pazo_B3 02aba89] Amend: updated Background.txt and removed Test.py
 2 files changed, 4 insertions(+), 3 deletions(-)
 delete mode 100644 Test.py

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1 (Pazo_B3)
$ git push origin Pazo_B3
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 397 bytes | 397.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Pazo_B3' on GitHub by visiting:
remote:      https://github.com/rosellepazo19-coder/Pazo_IT120_Act1/pull/new/Paz
o_B3
remote:
To https://github.com/rosellepazo19-coder/Pazo_IT120_Act1.git
 * [new branch]      Pazo_B3 -> Pazo_B3

$ git checkout master
Switched to branch 'master'

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1  (master)
$ git checkout -b Pazo_B4
Switched to a new branch 'Pazo_B4'

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1  (Pazo_B4)
$ git add Readme.txt

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1  (Pazo_B4)
$ git rm Test.py
rm 'Test.py'

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1  (Pazo_B4)
$ git commit -m "Amend: updated Readme.txt and removed Test.py"
[Pazo_B4 7ce28a1] Amend: updated Readme.txt and removed Test.py
 2 files changed, 148 insertions(+), 3 deletions(-)
 delete mode 100644 Test.py

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1  (Pazo_B4)
$ git push origin Pazo_B4
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.40 KiB | 1.40 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Mabras_B4' on GitHub by visiting:
remote:      https://github.com/mabrasjelyn-stack/Mabras_IT120_Act1/pull/new/Pazo_
B4
remote:
To https://github.com/mabrasjelyn-stack/Pazo_IT120_Act1.git
 * [new branch]      Pazo_B4 -> Pazo_B4

Roselle@DESKTOP-53FPVR6 MINGW64 ~/Desktop/Pazo_IT120_Act1  (Pazo_B4)
$ git branch -a
  Pazo_B1
  Pazo_B2
  Pazo_B3
* Pazo_B4
  master
  remotes/origin/Pazo_B1
  remotes/origin/Mabras_B2
  remotes/origin/Pazo_B3
  remotes/origin/Pazo_B4
  remotes/origin/master