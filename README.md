# My Repo
uus rivi

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25
$ mkdir my-repo

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25
$ cd my-repo

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo
$ get init
bash: get: command not found

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo
$ git init
Initialized empty Git repository in C:/Users/nikoa/Desktop/OhkeSyksy25/my-repo/.
git/

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo (master)
$ echo "# My Repo" > README.md

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo (master)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the nex
t time Git touches it

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo (master)
$ git commit -m "uus commit"
[master (root-commit) d9ebb8f] uus commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo (master)
$ echo "uus rivi"
uus rivi

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo (master)
$ echo "uus rivi" >> README.md

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo (master)
$ git commit -m "uus"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo (master)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the nex
t time Git touches it

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo (master)
$ git commit -m "Updated README with new line"
[master 805c702] Updated README with new line
 1 file changed, 1 insertion(+)

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo (master)
$ git remote add origin https://github.com/keputsu1/my-repo.

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo (master)
$ git branch -M main

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo (main)
$ git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (6/6), 466 bytes | 466.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/keputsu1/my-repo.
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

nikoa@DESKTOP-5FC0UQK MINGW64 ~/Desktop/OhkeSyksy25/my-repo (main)
$
