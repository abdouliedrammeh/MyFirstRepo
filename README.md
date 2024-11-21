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
Branch ‘master’ set up to track rjemote branch ‘master’ from ‘origin’.
MyFirstRepo %
git log

MyFirstRepo % git log
commit 9295da9184eb4989f129e334e6f29c3be060b147 (HEAD -> master, origin/master)
Author: John <john.doe@web.com>
Date: Mon Apr 26 16:11:43 2021 +0200
MyFirstRepo % git log -–format=fuller
commit 9295da9184eb4989f129e334e6f29c3be060b147 (HEAD -> master, origin/master)
Author:   John <john.doe@web.com>
AuthorDate: Mon Apr 26 16:11:43 2021 +0200
Commit:   John <john.doe@web.com>
CommitDate: Mon Apr 26 16:11:43 2021 +0200
  initial commit

  MyFirstRepo % git log –-format=raw
commit 9295da9184eb4989f129e334e6f29c3be060b147
tree e57f977bd6c515fc1d67d36ccb5958ac10e60674
author John <john.doe@web.com> 1619446303 +0200
commiter John <john.doe@web.com> 1619446303 +0200
  initial commit
  .git % git cat-file -p e57f977b
d6c515fc1d67d36ccb5958ac10e60674
100644 blob e43b0f988953ae3a84b00331d0ccf5f7d51cb3cf
  .gitignore
100644 blob 28db6070ba3f29124f7e2df09423c21f30f6ee17
  README.md
  .gitignore
  .git % git cat-file -p
28db6070ba3f29124f7e2df09423c21f30f6ee17
IU web Application Development project
MyFirstRepo % cat README.md
IU web Application Development project
MyFirstRepo % echo “IU Networking project” >> README.md
MyFirstRepo % git add README.md
MyFirstRepo % git commit -m “Second commit”
[master 41475de] Second commit
 1 file changed, 1 insertion(+)
 MyFirstRepo % git log --oneline
41475de (HEAD -> master) Second commit
9295da9 (origin/master) initial commit
MyFirstRepo % git cat-file -p 41475de
tree 5af1c427727d260a944abb20f8429501d848639f
parent 9295da9184eb4989f129e334e6f29c3be060b147
author John <john.doe@web.com> 1619523800 +0200
committer John <john.doe@web.com> 1619523800 +0200
Second commit

  

