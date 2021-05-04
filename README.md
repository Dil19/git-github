# git-github
What is Git | What is GitHub | Git Tutorial | GitHub Tutorial | Devops Tutorial | Edureka
just try

git init

git remote add origin "https://github.com/Dil19/git-github.git"

git pull origin main

git status

git add Edu1.txt

git status

git commit -m "adding first commit in local repo"

git status

git add -A

git status

git commit -a -m "adding all once"

git log

git branch firstbranch

git checkout 'firstbranch'

git status

git add Edu4.txt

git commit -m "making changes in firstbranch"

ls

git checkout main

ls

git checkout master

ls

git merge firstbranch

ls

git checkout firstbranch

-------------------------------------------------------


-------------------------------------------------------



user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka
$ git init
Initialized empty Git repository in C:/Users/user/Projects20210414/GIT_Edureka/.git/

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git remote add origin "https://github.com/Dil19/git-github.git"

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git pull origin master
fatal: couldn't find remote ref master

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git pull origin master
fatal: couldn't find remote ref master

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git pull origin main
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), 1.23 KiB | 105.00 KiB/s, done.
From https://github.com/Dil19/git-github
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git s
send-email        show-branch       stash             switch
shortlog          sparse-checkout   status
show              stage             submodule

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git s
send-email        show-branch       stash             switch
shortlog          sparse-checkout   status
show              stage             submodule

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Edu1.txt

nothing added to commit but untracked files present (use "git add" to track)

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git add Edu1.txt

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Edu1.txt


user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git
Display all 64 possibilities? (y or n)

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git c
checkout                     clone
cherry                       commit
cherry-pick                  config
citool                       credential-helper-selector
clean

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git c
checkout                     clone
cherry                       commit
cherry-pick                  config
citool                       credential-helper-selector
clean

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git co
commit   config

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git commit -m "adding first commit in local repo"
[master 495d88a] adding first commit in local repo
 1 file changed, 1 insertion(+)
 create mode 100644 Edu1.txt

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ ^C

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ ^C

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Edu2.txt
        Edu3.txt

nothing added to commit but untracked files present (use "git add" to track)

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git add -a
error: unknown switch `a'
usage: git add [<options>] [--] <pathspec>...

    -n, --dry-run         dry run
    -v, --verbose         be verbose

    -i, --interactive     interactive picking
    -p, --patch           select hunks interactively
    -e, --edit            edit current diff and apply
    -f, --force           allow adding otherwise ignored files
    -u, --update          update tracked files
    --renormalize         renormalize EOL of tracked files (implies -u)
    -N, --intent-to-add   record only the fact that the path will be added later
    -A, --all             add changes from all tracked and untracked files
    --ignore-removal      ignore paths removed in the working tree (same as --no-all)
    --refresh             don't add, only refresh the index
    --ignore-errors       just skip files which cannot be added because of errors
    --ignore-missing      check if - even missing - files are ignored in dry run
    --chmod (+|-)x        override the executable bit of the listed files
    --pathspec-from-file <file>
                          read pathspec from file
    --pathspec-file-nul   with --pathspec-from-file, pathspec elements are separated with NUL character


user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git add -A

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Edu2.txt
        new file:   Edu3.txt


user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git commit -a -m "adding all once"
[master ccdd03f] adding all once
 2 files changed, 2 insertions(+)
 create mode 100644 Edu2.txt
 create mode 100644 Edu3.txt

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git log
commit ccdd03f4cbd079962b43905bb17f81cf4f2f2ada (HEAD -> master)
Author: Dil19 <59259863+Dil19@users.noreply.github.com>
Date:   Wed Apr 28 15:01:23 2021 +0530

    adding all once

commit 495d88ab3e0327969cbd596e3528f37bdd1caa6e
Author: Dil19 <59259863+Dil19@users.noreply.github.com>
Date:   Wed Apr 28 14:54:37 2021 +0530

    adding first commit in local repo

commit 09a6e76a672c02c46667aedd25321e6f17f1bd67 (origin/main)
Author: Dil19 <59259863+Dil19@users.noreply.github.com>
Date:   Wed Apr 28 14:18:08 2021 +0530

    Update README.md

commit 89a9b5eae1005179bba142ca7fe563cc2a643d36
Author: Dil19 <59259863+Dil19@users.noreply.github.com>
Date:   Wed Apr 28 14:16:47 2021 +0530

    Initial commit


user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git branch firstbranch

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git checkout 'firstbranch'
Switched to branch 'firstbranch'

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ git status
On branch firstbranch
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Edu4.txt

nothing added to commit but untracked files present (use "git add" to track)

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ git add Edu4.txt

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ git commit -m "making changes in firstbranch"
[firstbranch 8cf0e20] making changes in firstbranch
 1 file changed, 1 insertion(+)
 create mode 100644 Edu4.txt

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ ls
Edu1.txt  Edu2.txt  Edu3.txt  Edu4.txt  README.md

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ git checkout main
Switched to a new branch 'main'
Branch 'main' set up to track remote branch 'main' from 'origin'.

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (main)
$ ls
README.md

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (main)
$ git checkout master
Switched to branch 'master'

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ ls
Edu1.txt  Edu2.txt  Edu3.txt  README.md

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git merge firstbranch
Updating ccdd03f..8cf0e20
Fast-forward
 Edu4.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Edu4.txt

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ ls
Edu1.txt  Edu2.txt  Edu3.txt  Edu4.txt  README.md

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ ^C

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git checkout firstbranch
Switched to branch 'firstbranch'

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ git commit -a -m "modify edu4"
On branch firstbranch
nothing to commit, working tree clean

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ git commit -a -m "modify edu4"
[firstbranch 355cf02] modify edu4
 1 file changed, 1 insertion(+), 1 deletion(-)

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ cat Edu4.txt
firstbranch modified in firstbranch
user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ git checkout master
Switched to branch 'master'

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ cat Edu4.txt
firstbranch
user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git checkout firstbranch
Switched to branch 'firstbranch'

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ git add -A

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ git commit -a -m "adding for rebasing"
[firstbranch 80b2f4b] adding for rebasing
 2 files changed, 2 insertions(+)
 create mode 100644 Edu5.txt
 create mode 100644 Edu6.txt

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ ls
Edu1.txt  Edu2.txt  Edu3.txt  Edu4.txt  Edu5.txt  Edu6.txt  README.md

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ git checkout master
Switched to branch 'master'

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ ls
Edu1.txt  Edu2.txt  Edu3.txt  Edu4.txt  README.md

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git checkout firstbranch
Switched to branch 'firstbranch'

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ git rebase master
Current branch firstbranch is up to date.

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ git checkout master
Switched to branch 'master'

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git rebase firstbranch
Successfully rebased and updated refs/heads/master.

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ ls
Edu1.txt  Edu2.txt  Edu3.txt  Edu4.txt  Edu5.txt  Edu6.txt  README.md

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git checkout firstbranch
Switched to branch 'firstbranch'

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ git push origin firstbranch
Enumerating objects: 18, done.
Counting objects: 100% (18/18), done.
Delta compression using up to 12 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (17/17), 1.32 KiB | 677.00 KiB/s, done.
Total 17 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), done.
remote:
remote: Create a pull request for 'firstbranch' on GitHub by visiting:
remote:      https://github.com/Dil19/git-github/pull/new/firstbranch
remote:
To https://github.com/Dil19/git-github.git
 * [new branch]      firstbranch -> firstbranch

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (firstbranch)
$ git checkout master
Switched to branch 'master'

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git push origin master
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/Dil19/git-github/pull/new/master
remote:
To https://github.com/Dil19/git-github.git
 * [new branch]      master -> master

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git add revert.txt

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git commit -m "revert1"
[master 5b7a76c] revert1
 1 file changed, 1 insertion(+)
 create mode 100644 revert.txt

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git commit -a -m "revert2"
[master 4fcae6a] revert2
 1 file changed, 1 insertion(+), 1 deletion(-)

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ cat revert.txt
h then
user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git log
commit 4fcae6a14a40be761c2a420b403d842564016a47 (HEAD -> master)
Author: Dil19 <59259863+Dil19@users.noreply.github.com>
Date:   Tue May 4 23:41:30 2021 +0530

    revert2

commit 5b7a76c966dfaff296300f7110bc91d2b44e199f
Author: Dil19 <59259863+Dil19@users.noreply.github.com>
Date:   Tue May 4 23:39:45 2021 +0530

    revert1

commit 80b2f4b5f712c54694ccf7c2c66fcb5990e8b9de (origin/master, origin/firstbranch, firstbranch)
Author: Dil19 <59259863+Dil19@users.noreply.github.com>
Date:   Tue May 4 22:36:57 2021 +0530

    adding for rebasing

commit 355cf02df7a6912c96e043703f6a59746089e056
Author: Dil19 <59259863+Dil19@users.noreply.github.com>
Date:   Tue May 4 21:48:05 2021 +0530



user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ git checkout 5b7a76c9 revert.txt
Updated 1 path from 3f23df4

user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$ cat revert.txt
h
user@DESKTOP-QSD8FR6new MINGW64 ~/Projects20210414/GIT_Edureka (master)
$
