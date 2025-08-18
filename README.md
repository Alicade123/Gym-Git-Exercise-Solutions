# Git Exercise

## Bundle 1

## Exercise 1

```bash
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1> mkdir Exercise_1_2


    Directory: C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         8/18/2025   6:25 PM                Exercise_1_2


PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1> cd .\Exercise_1_2\
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git init
Initialized empty Git repository in C:/xampp/htdocs/The Gym Phase2/GIT_BASICS/Bundle-1/Exercise_1_2/.git/
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> ls


    Directory: C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         8/18/2025   6:26 PM            520 index.html


PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git add .
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git commit -m "Initial commit"
>>
[Main (root-commit) ec2b9da] Initial commit
 1 file changed, 21 insertions(+)
 create mode 100644 index.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git remote add origin https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git branch -M main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 520 bytes | 520.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git branch
* main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git branch -m master
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git branch
* master
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git branch -m main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git branch
* main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        app.js
        styles.css

nothing added to commit but untracked files present (use "git add" to track)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git add .
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   app.js
        new file:   styles.css

PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git commit -m "add JS and Style files"
[main 58dcebe] add JS and Style files
 2 files changed, 15 insertions(+)
 create mode 100644 app.js
 create mode 100644 styles.css
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 533 bytes | 533.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
   ec2b9da..58dcebe  main -> main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git checkout -b "dev"
Switched to a new branch 'dev'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git branch
* dev
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Alicade123/Gym-Git-Exercise-Solutions/pull/new/dev
remote:
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      dev -> dev
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git checkout -b "test"
Switched to a new branch 'test'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/Alicade123/Gym-Git-Exercise-Solutions/pull/new/test
remote:
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      test -> test
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git checkout dev
Switched to branch 'dev'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git branch -D test
Deleted branch test (was 58dcebe).
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git push origin dev
Everything up-to-date
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2> git branch
* dev
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\Bundle-1\Exercise_1_2>
```

### Exercise 2

```bash
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> ls


    Directory: C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         8/18/2025   7:08 PM             66 app.js
-a----         8/18/2025   7:08 PM            520 index.html
-a----         8/18/2025   6:40 PM           5767 README.md
-a----         8/18/2025   8:17 PM            212 styles.css


PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git init
Initialized empty Git repository in C:/xampp/htdocs/The Gym Phase2/GIT_BASICS/BUNDLE-One/.git/
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add .
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -m "initial commit"
[Main (root-commit) b58c05b] initial commit
 4 files changed, 167 insertions(+)
 create mode 100644 README.md
 create mode 100644 app.js
 create mode 100644 index.html
 create mode 100644 styles.css
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote add origin https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch -M main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.93 KiB | 660.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main


PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git init
Initialized empty Git repository in C:/xampp/htdocs/The Gym Phase2/GIT_BASICS/BUNDLE-One/.git/
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add .
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -m "initial commit"
[Main (root-commit) b58c05b] initial commit
 4 files changed, 167 insertions(+)
 create mode 100644 README.md
 create mode 100644 app.js
 create mode 100644 index.html
 create mode 100644 styles.css
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote add origin https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch -M main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.93 KiB | 660.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main
Initialized empty Git repository in C:/xampp/htdocs/The Gym Phase2/GIT_BASICS/BUNDLE-One/.git/
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add .
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -m "initial commit"
[Main (root-commit) b58c05b] initial commit
 4 files changed, 167 insertions(+)
 create mode 100644 README.md
 create mode 100644 app.js
 create mode 100644 index.html
 create mode 100644 styles.css
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote add origin https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch -M main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.93 KiB | 660.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.93 KiB | 660.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add .\home.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git stash
Saved working directory and index state WIP on main: b58c05b initial commit
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add .\about.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git stash
Saved working directory and index state WIP on main: b58c05b initial commit
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add .\team.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git stash
Saved working directory and index state WIP on main: b58c05b initial commit
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git stash list
stash@{0}: WIP on main: b58c05b initial commit
stash@{1}: WIP on main: b58c05b initial commit
stash@{2}: WIP on main: b58c05b initial commit
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git stash pop "stash@{1}"
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (a16af6a9d010aa54a4124425476dc623e1b67a1b)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git stash list
stash@{0}: WIP on main: b58c05b initial commit
stash@{1}: WIP on main: b58c05b initial commit
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git stash pop "stash@{1}"
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (46315bbbf8e6841b1a639b4e21457d4067de5e08)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -m "add the about page and home page"
[main 3bac049] add the about page and home page
 2 files changed, 28 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git stash list
stash@{0}: WIP on main: b58c05b initial commit
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git stash pop "stash@{0}"
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped stash@{0} (5ed0e9ecf85b51205a9c79145556eab7364394af)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git stash reset --hard
error: unknown option `hard'
usage: git stash list [<log-options>]
   or: git stash show [-u | --include-untracked | --only-untracked] [<diff-options>] [<stash>]
   or: git stash drop [-q | --quiet] [<stash>]
   or: git stash pop [--index] [-q | --quiet] [<stash>]
   or: git stash apply [--index] [-q | --quiet] [<stash>]
   or: git stash branch <branchname> [<stash>]
   or: git stash [push [-p | --patch] [-S | --staged] [-k | --[no-]keep-index] [-q | --quiet]
                 [-u | --include-untracked] [-a | --all] [(-m | --message) <message>]
                 [--pathspec-from-file=<file> [--pathspec-file-nul]]
                 [--] [<pathspec>...]]
   or: git stash save [-p | --patch] [-S | --staged] [-k | --[no-]keep-index] [-q | --quiet]
                 [-u | --include-untracked] [-a | --all] [<message>]
   or: git stash clear
   or: git stash create [<message>]
   or: git stash store [(-m | --message) <message>] [-q | --quiet] <commit>

    -k, --[no-]keep-index keep index
    -S, --[no-]staged     stash staged changes only
    -p, --[no-]patch      stash in patch mode
    -q, --[no-]quiet      quiet mode
    -u, --[no-]include-untracked
                          include untracked files in stash
    -a, --[no-]all        include ignore files
    -m, --[no-]message <message>
                          stash message
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements are separated with NUL character

PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git reset -hard
error: did you mean `--hard` (with two dashes)?
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git reset --hard
HEAD is now at 3bac049 add the about page and home page
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>
```
