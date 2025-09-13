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