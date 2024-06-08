# cloud-bootcamp-fj89
git repos excercise
echo "# cloud-bootcamp-fj89" >> README.md --> (add file:README.md to repo:cloud-bootcamp-fj89 in git to a local and remote machine in git acct) 

$git init
Initialized empty Git repository in C:/Users/FJ89/Documents/cloud-bootcamp-fj89/.git/


```python
$** git status**

```On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)


**$ git add .**

FJ89@DESKTOP-VJO8REN MINGW64 ~/Documents/cloud-bootcamp-fj89 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


$ **git commit -m "first commit"**

[master (root-commit) b2ff5c6] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

FJ89@DESKTOP-VJO8REN MINGW64 ~/Documents/cloud-bootcamp-fj89 (master)
$ git status
On branch master
nothing to commit, working tree clean


$ git branch -M main

FJ89@DESKTOP-VJO8REN MINGW64 ~/Documents/cloud-bootcamp-fj89 (main)
$ git remote add origin git@github.com:fzjn89/cloud-bootcamp-fj89.git

FJ89@DESKTOP-VJO8REN MINGW64 ~/Documents/cloud-bootcamp-fj89 (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 226 bytes | 226.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:fzjn89/cloud-bootcamp-fj89.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
