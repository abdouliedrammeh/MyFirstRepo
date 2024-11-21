# MyFirstRepo
MyFirstRepo % git remote add origin git@github.com:abdouliedrammeh/MyFirstRepo.git
MyFirstRepo %
MyFirstRepo % git commit -m “initial commit”
[master (root-commit) 9295da9] initial commit
 2 files changed, 2 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 git push -u origin master

MyFirstRepo % git push -u origin master
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 305 bytes | 305.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To github.com:hadidrachid/MyFirstRepo.git
 * [new branch]  master -> master
Branch ‘master’ set up to track remote branch ‘master’ from ‘origin’.
MyFirstRepo %
git log

MyFirstRepo % git log
commit 9295da9184eb4989f129e334e6f29c3be060b147 (HEAD -> master, origin/master)
Author: John <john.doe@web.com>
Date: Mon Apr 26 16:11:43 2021 +0200
  initial commit

