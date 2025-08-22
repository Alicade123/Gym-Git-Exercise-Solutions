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

## Bundle 2

### Exercise 1

```bash
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout -b "ft/bundle-2"
Switched to a new branch 'ft/bundle-2'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add .\services.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -m "Added service page"
[ft/bundle-2 d775680] Added service page
 1 file changed, 14 insertions(+)
 create mode 100644 services.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 462 bytes | 231.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Alicade123/Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
remote:
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>
```

### Exercise 2

````bash
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
* ft/bundle-2
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout main
Switched to branch 'main'
Your branch is behind 'origin/main' by 2 commits, and can be fast-forwarded.
  (use "git pull" to update your local branch)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git pull
Updating 91a14c5..3402a27
Fast-forward
 services.html | 14 ++++++++++++++
 1 file changed, 14 insertions(+)
 create mode 100644 services.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
  ft/bundle-2
* main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout -b "ft/service-redesign"
Switched to a new branch 'ft/service-redesign'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
  ft/bundle-2
* ft/service-redesign
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -am "Added List of services"
[ft/service-redesign 856b232] Added List of services
 2 files changed, 64 insertions(+)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push origin ft/searvice-redesign
error: src refspec ft/searvice-redesign does not match any
error: failed to push some refs to 'https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push origin ft/service-redesign
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.12 KiB | 1.12 MiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/Alicade123/Gym-Git-Exercise-Solutions/pull/new/ft/service-redesign
remote:
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -am "Adde Our Team"
[main 1cdc900] Adde Our Team
 1 file changed, 8 insertions(+)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 548 bytes | 548.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
   3402a27..1cdc900  main -> main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git diff
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git diff ft/service-redesign main
diff --git a/README.md b/README.md
index 45fe4cd..93b5837 100644
--- a/README.md
+++ b/README.md
@@ -318,59 +318,3 @@ Your branch is ahead of 'origin/main' by 1 commit.
 nothing to commit, working tree clean
 PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>



-
-## Bundle 2
-
-### Exercise 1
-
-```bash
-PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout -b "ft/bundle-2"
-Switched to a new branch 'ft/bundle-2'
-PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add .\services.html
-PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -m "Added service page"
-[ft/bundle-2 d775680] Added service page
- 1 file changed, 14 insertions(+)
- create mode 100644 services.html
-PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push origin ft/bundle-2
-Enumerating objects: 4, done.
-Counting objects: 100% (4/4), done.
-Delta compression using up to 12 threads
-Compressing objects: 100% (3/3), done.
-Writing objects: 100% (3/3), 462 bytes | 231.00 KiB/s, done.
-Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
-remote: Resolving deltas: 100% (1/1), completed with 1 local object.
-remote:
-remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
-remote:      https://github.com/Alicade123/Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
-remote:
-To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
- * [new branch]      ft/bundle-2 -> ft/bundle-2
-PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>
-```
-
-### Exercise 2
-
-```bash
-PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
-* ft/bundle-2
-  main
-PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout main
-Switched to branch 'main'
-Your branch is behind 'origin/main' by 2 commits, and can be fast-forwarded.
-  (use "git pull" to update your local branch)
-PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git pull
-Updating 91a14c5..3402a27
-Fast-forward
- services.html | 14 ++++++++++++++
- 1 file changed, 14 insertions(+)
- create mode 100644 services.html
-PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
-  ft/bundle-2
-* main
-PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git status
-On branch main
-Your branch is up to date with 'origin/main'.
-
-nothing to commit, working tree clean
-PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>
-```
\ No newline at end of file
diff --git a/services.html b/services.html
index 2e81818..cfd3280 100644
--- a/services.html
+++ b/services.html
@@ -9,13 +9,13 @@

 <body>
     <h3>Service Page</h3>
-
-    <label>List of Service</label>
+    <label for="">Our Team</label>
     <ul>
-        <li>Web Development</li>
-        <li>Mobile App Development</li>
-        <li>Software Engineering Training</li>
-        <li>Web Hosting And Management service</li>
+        <li>Alicade ABITURIJE</li>
+        <li>Regis MUCYO</li>
+        <li>Pascal KUBANA</li>
+        <li>J. Paul IRADUKUNDA</li>
+        <li>Elie MUGISHA </li>
     </ul>
 </body>

PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git merge ft/service-redesign
Already up to date.
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
  ft/bundle-2
* ft/service-redesign
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -am "fix: resolve conflicts"
On branch ft/service-redesign
nothing to commit, working tree clean
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push origin ft/service-redesign
Everything up-to-date
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git diff main ft/service-redesign
diff --git a/README.md b/README.md
index 93b5837..45fe4cd 100644
--- a/README.md
+++ b/README.md
@@ -318,3 +318,59 @@ Your branch is ahead of 'origin/main' by 1 commit.
 nothing to commit, working tree clean
 PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>


- +## Bundle 2
- +### Exercise 1
- +```bash
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout -b "ft/bundle-2"
  +Switched to a new branch 'ft/bundle-2'
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add .\services.html
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -m "Added service page"
  +[ft/bundle-2 d775680] Added service page
- 1 file changed, 14 insertions(+)
- create mode 100644 services.html
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push origin ft/bundle-2
  +Enumerating objects: 4, done.
  +Counting objects: 100% (4/4), done.
  +Delta compression using up to 12 threads
  +Compressing objects: 100% (3/3), done.
  +Writing objects: 100% (3/3), 462 bytes | 231.00 KiB/s, done.
  +Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
  +remote: Resolving deltas: 100% (1/1), completed with 1 local object.
  +remote:
  +remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
  +remote: https://github.com/Alicade123/Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
  +remote:
  +To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
- - [new branch] ft/bundle-2 -> ft/bundle-2
    +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>
    +```
- +### Exercise 2
- +```bash
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
  +\* ft/bundle-2
- main
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout main
  +Switched to branch 'main'
  +Your branch is behind 'origin/main' by 2 commits, and can be fast-forwarded.
- (use "git pull" to update your local branch)
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git pull
  +Updating 91a14c5..3402a27
  +Fast-forward
- services.html | 14 ++++++++++++++
- 1 file changed, 14 insertions(+)
- create mode 100644 services.html
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
- ft/bundle-2
  +\* main
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git status
  +On branch main
  +Your branch is up to date with 'origin/main'.
- +nothing to commit, working tree clean
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>
  +```
  \ No newline at end of file
  diff --git a/services.html b/services.html
  index cfd3280..2e81818 100644
  --- a/services.html
  +++ b/services.html
  @@ -9,13 +9,13 @@
   <body>
       <h3>Service Page</h3>

* <label for="">Our Team</label>

-
- <label>List of Service</label>
  <ul>

*        <li>Alicade ABITURIJE</li>
*        <li>Regis MUCYO</li>
*        <li>Pascal KUBANA</li>
*        <li>J. Paul IRADUKUNDA</li>
*        <li>Elie MUGISHA </li>

-        <li>Web Development</li>
-        <li>Mobile App Development</li>
-        <li>Software Engineering Training</li>
-        <li>Web Hosting And Management service</li>
     </ul>
 </body>
diff --git a/README.md b/README.md
index 93b5837..45fe4cd 100644
--- a/README.md
+++ b/README.md
@@ -318,3 +318,59 @@ Your branch is ahead of 'origin/main' by 1 commit.
 nothing to commit, working tree clean
 PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>
  ```
- +## Bundle 2
- +### Exercise 1
- +```bash
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout -b "ft/bundle-2"
  PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git merge ft/service-redesign
  Auto-merging services.html
  CONFLICT (content): Merge conflict in services.html
- +## Bundle 2
- +### Exercise 1
- +```bash
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout -b "ft/bundle-2"
  PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git merge ft/service-redesign
  Auto-merging services.html
  CONFLICT (content): Merge conflict in services.html
  +### Exercise 1
- +```bash
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout -b "ft/bundle-2"
  PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git merge ft/service-redesign
  Auto-merging services.html
  CONFLICT (content): Merge conflict in services.html
  ```
 - +```bash
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout -b "ft/bundle-2"
  PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git merge ft/service-redesign
  Auto-merging services.html
  CONFLICT (content): Merge conflict in services.html
  +PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout -b "ft/bundle-2"
  PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git merge ft/service-redesign
  Auto-merging services.html
  CONFLICT (content): Merge conflict in services.html
  PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git merge ft/service-redesign
  Auto-merging services.html
  CONFLICT (content): Merge conflict in services.html
  Auto-merging services.html
  CONFLICT (content): Merge conflict in services.html
  CONFLICT (content): Merge conflict in services.html
  Automatic merge failed; fix conflicts and then commit the result.
  PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git merge ft/service-redesign
  fatal: You have not concluded your merge (MERGE_HEAD exists).
  Please, commit your changes before you merge.
  PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -am "fix: resolve conflicts"
  [main 5aaf014] fix: resolve conflicts
  PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push origin main
  Enumerating objects: 7, done.
  Counting objects: 100% (7/7), done.
  Delta compression using up to 12 threads
  Compressing objects: 100% (3/3), done.
  Writing objects: 100% (3/3), 455 bytes | 455.00 KiB/s, done.
  Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
  remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
  To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
  1cdc900..5aaf014 main -> main
  PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>
```
````

## Bundle 3

### Exercise 1

```bash
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
  ft/bundle-2
  ft/service-redesign
* main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout -b "ft/team-page"
Switched to a new branch 'ft/team-page'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
  ft/bundle-2
  ft/service-redesign
* ft/team-page
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git status
On branch ft/team-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -am "Added team page"
On branch ft/team-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add .
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git status
On branch ft/team-page
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -m "Added team page"
[ft/team-page 66d0285] Added team page
 1 file changed, 14 insertions(+)
 create mode 100644 team.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 449 bytes | 449.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/Alicade123/Gym-Git-Exercise-Solutions/pull/new/ft/team-page
remote:
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/team-page -> ft/team-page
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout -b "ft/contact-page"
Switched to a new branch 'ft/contact-page'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
  ft/bundle-2
* ft/contact-page
  ft/service-redesign
  ft/team-page
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout "ft/team-page"
Switched to branch 'ft/team-page'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git log
commit 66d02855ec75872038bd91b0b865028401e16575 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Date:   Wed Aug 20 10:07:56 2025 +0200

    Added team page

commit f1325f3401986e852f408310eceb1111276ee6bf (origin/main, main, ft/contact-page)
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Date:   Tue Aug 19 11:44:41 2025 +0200

    Update: README file

commit 5aaf0149cfaaf62fbce1d76b1c9dcd8a1ec30bc8
Merge: 1cdc900 856b232
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Date:   Tue Aug 19 11:08:34 2025 +0200

    fix: resolve conflicts

commit 1cdc900d0457841cf9ccbf3e26e358cd3b4d012a
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Date:   Tue Aug 19 10:54:28 2025 +0200

    Adde Our Team

commit 856b2327b3e6c2aad5adc0d30d7fff7630e17536 (origin/ft/service-redesign, ft/service-redesign)
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Date:   Tue Aug 19 10:47:41 2025 +0200

    Added List of services

commit 3402a2719d2b22d23b4e84d2f67ac9423c33dfe6
Merge: 91a14c5 d775680
Author: Regis Mucyo <mucyoregis250@gmail.com>
Date:   Tue Aug 19 10:36:58 2025 +0200

    Merge pull request #1 from Alicade123/ft/bundle-2

    Added service page

commit d77568003932441b43e7e0e1ad51a42b27c75a3d (origin/ft/bundle-2, ft/bundle-2)
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Date:   Tue Aug 19 10:19:23 2025 +0200

    Added service page

commit 91a14c5e1ad1193f8708252a08083d47e08c35a9
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Date:   Mon Aug 18 20:38:49 2025 +0200

    add final changes of Bundle1 Exercise 2

commit 3bac049fffbaaa817e58dd10d9f18730ac1d7ca9
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>

    add final changes of Bundle1 Exercise 2

commit 3bac049fffbaaa817e58dd10d9f18730ac1d7ca9
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
    add final changes of Bundle1 Exercise 2

commit 3bac049fffbaaa817e58dd10d9f18730ac1d7ca9
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
commit 3bac049fffbaaa817e58dd10d9f18730ac1d7ca9
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Date:   Mon Aug 18 20:33:40 2025 +0200
Date:   Mon Aug 18 20:33:40 2025 +0200

    add the about page and home page

    add the about page and home page
    add the about page and home page

commit b58c05b512669aa6e31664de03e69a462a809131
    add the about page and home page

commit b58c05b512669aa6e31664de03e69a462a809131
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
    add the about page and home page

commit b58c05b512669aa6e31664de03e69a462a809131
    add the about page and home page


commit b58c05b512669aa6e31664de03e69a462a809131
commit b58c05b512669aa6e31664de03e69a462a809131
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Date:   Mon Aug 18 20:27:55 2025 +0200

    initial commit
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout "ft/contact-page"
Switched to branch 'ft/contact-page'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git cherry-pick "66d02855ec75872038bd91b0b865028401e16575"
[ft/contact-page 2c18173] Added team page
 Date: Wed Aug 20 10:07:56 2025 +0200
 1 file changed, 14 insertions(+)
 create mode 100644 team.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -am "Change added in tean page"
[ft/contact-page f2323f9] Change added in tean page
 1 file changed, 8 insertions(+)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push origin ft/contact-page
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 803 bytes | 803.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/Alicade123/Gym-Git-Exercise-Solutions/pull/new/ft/contact-page
remote:
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/contact-page -> ft/contact-page
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch "ft/faq-page"
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
  ft/bundle-2
* ft/contact-page
  ft/faq-page
  ft/service-redesign
  ft/team-page
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout ft/faq-page
Switched to branch 'ft/faq-page'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
  ft/bundle-2
  ft/contact-page
* ft/faq-page
  ft/service-redesign
  ft/team-page
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -am "Added faq page"
On branch ft/faq-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        faq.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add .
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -m "Added faq page"
[ft/faq-page c77e778] Added faq page
 1 file changed, 20 insertions(+)
 create mode 100644 faq.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 526 bytes | 526.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/Alicade123/Gym-Git-Exercise-Solutions/pull/new/ft/faq-page
remote:
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/faq-page -> ft/faq-page
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git revert "66d02855ec75872038bd91b0b865028401e16575"
CONFLICT (modify/delete): team.html deleted in parent of 66d0285 (Added team page) and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not revert 66d0285... Added team page
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".
hint: Disable this message with "git config advice.mergeConflict false"
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git log
commit c77e778492f6e4ae9c4d80fb66760ae38ae8e9a0 (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Date:   Wed Aug 20 10:40:01 2025 +0200

    Added faq page

commit f2323f91c036b454c05b5a8e4708d9351728fbed (origin/ft/contact-page, ft/contact-page)
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Date:   Wed Aug 20 10:29:36 2025 +0200

    Change added in tean page

commit 2c18173b5751fbc493721cd14a32113bf582795c
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Date:   Wed Aug 20 10:07:56 2025 +0200

    Added team page

commit f1325f3401986e852f408310eceb1111276ee6bf (origin/main, main)
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Date:   Tue Aug 19 11:44:41 2025 +0200

    Update: README file

commit 5aaf0149cfaaf62fbce1d76b1c9dcd8a1ec30bc8
Merge: 1cdc900 856b232
Author: Alicade Abiturije Dusabe <abiturije1alicade@gmail.com>
Date:   Tue Aug 19 11:08:34 2025 +0200

    fix: resolve conflicts

PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git revert "2c18173b5751fbc493721cd14a32113bf582795c"
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git revert "66d02855ec75872038bd91b0b865028401e16575"
[ft/team-page 9b836e5] Revert "Added team page"
 1 file changed, 14 deletions(-)
 delete mode 100644 team.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 363 bytes | 363.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
   f9c62f2..c1430ce  ft/faq-page -> ft/faq-page
```

### Exercise 2

```bash
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
  ft/bundle-2
  ft/contact-page
* ft/faq-page
  ft/service-redesign
  ft/team-page
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch "ft/home-page-redesign"
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
  ft/bundle-2
  ft/contact-page
* ft/faq-page
  ft/home-page-redesign
  ft/service-redesign
  ft/team-page
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout main
M       README.md
Switched to branch 'main'
Your branch is behind 'origin/main' by 3 commits, and can be fast-forwarded.
  (use "git pull" to update your local branch)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -am "Added Change in home page"
[main 68edd98] Added Change in home page
 2 files changed, 283 insertions(+)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
  ft/bundle-2
  ft/contact-page
  ft/faq-page
* ft/home-page-redesign
  ft/service-redesign
  ft/team-page
  main
  PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add .
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -m "Update the home page"
[ft/home-page-redesign 9223a74] Update the home page
 1 file changed, 1 insertion(+)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push
fatal: The current branch ft/home-page-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/home-page-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>     git push --set-upstream origin ft/home-page-redesign
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 12 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (11/11), 1.57 KiB | 401.00 KiB/s, done.
Total 11 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Alicade123/Gym-Git-Exercise-Solutions/pull/new/ft/home-page-redesign
remote:
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
Delta compression using up to 12 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (11/11), 1.57 KiB | 401.00 KiB/s, done.
Total 11 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 2 local objects.
remote:
Delta compression using up to 12 threads
Delta compression using up to 12 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (11/11), 1.57 KiB | 401.00 KiB/s, done.
Total 11 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Alicade123/Gym-Git-Exercise-Solutions/pull/new/ft/home-page-redesign
remote:
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
branch 'ft/home-page-redesign' set up to track 'origin/ft/home-page-redesign'.
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>

```

## Bundle 4

### Exercise 1

```bash
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote -v
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote -v
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (push)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote add git-copy https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote -v
git-copy        https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git (fetch)
git-copy        https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git (push)
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (push)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote -v
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (push)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote add git-copy https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote -v
git-copy        https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git (fetch)
git-copy        https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git (push)
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (push)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote -v
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (push)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote add git-copy https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote -v
git-copy        https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git (fetch)
git-copy        https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git (push)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote -v
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (push)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote add git-copy https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote -v
git-copy        https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git (fetch)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote -v
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (push)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote add git-copy https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git remote -v
git-copy        https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git (fetch)
git-copy        https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git (push)
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git (push)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
  ft/bundle-2
  ft/contact-page
  ft/faq-page
  ft/home-page-redesign
  ft/service-redesign
  ft/team-page
* main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add --all
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -m "New Feature added"
[main 78bb6e7] New Feature added
 1 file changed, 27 insertions(+)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.04 KiB | 531.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
   8e224ae..78bb6e7  main -> main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push git-copy main
Enumerating objects: 66, done.
Counting objects: 100% (66/66), done.
Delta compression using up to 12 threads
Compressing objects: 100% (66/66), done.
Writing objects: 100% (66/66), 15.41 KiB | 876.00 KiB/s, done.
Total 66 (delta 38), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (38/38), done.
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions-2.git
 * [new branch]      main -> main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>
```

### Exercise 2

```bash
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout -b ft/footer
Switched to a new branch 'ft/footer'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add .
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commmit -m "Home page Changed"
git: 'commmit' is not a git command. See 'git --help'.

The most similar command is
        commit
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -m "Home page Changed"
[ft/footer db71117] Home page Changed
 2 files changed, 90 insertions(+), 2 deletions(-)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add --all
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -m "Home page Changed again"
[ft/footer 9ffc48a] Home page Changed again
 1 file changed, 11 insertions(+), 5 deletions(-)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push
fatal: The current branch ft/footer has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/footer

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>  git push --set-upstream origin ft/footer
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 12 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 1.27 KiB | 434.00 KiB/s, done.
Total 7 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 3 local objects.
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/Alicade123/Gym-Git-Exercise-Solutions/pull/new/ft/footer
remote:
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/footer -> ft/footer
branch 'ft/footer' set up to track 'origin/ft/footer'.
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> ft/squashing
ft/squashing : The term 'ft/squashing' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or
if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ ft/squashing
+ ~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (ft/squashing:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch ft/squashing
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkoutft/squashing
git: 'checkoutft/squashing' is not a git command. See 'git --help'.
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git checkout ft/squashing
Switched to branch 'ft/squashing'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git branch
  ft/bundle-2
  ft/contact-page
  ft/faq-page
  ft/footer
  ft/home-page-redesign
  ft/service-redesign
* ft/squashing
  ft/team-page
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git merge --squash ft/footer
Updating 78bb6e7..9ffc48a
Fast-forward
Squash commit -- not updating HEAD
 README.md | 83 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 home.html | 15 ++++++++++--
 2 files changed, 96 insertions(+), 2 deletions(-)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git add .
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git commit -am "footer changes squashing"
[ft/squashing e5e2fd8] footer changes squashing
 2 files changed, 96 insertions(+), 2 deletions(-)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One> git push
fatal: The current branch ft/squashing has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/squashing

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>
>>     git push --set-upstream origin ft/squashing
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1008 bytes | 336.00 KiB/s, done.
Total 4 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/Alicade123/Gym-Git-Exercise-Solutions/pull/new/ft/squashing
remote:
To https://github.com/Alicade123/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/squashing -> ft/squashing
branch 'ft/squashing' set up to track 'origin/ft/squashing'.
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\BUNDLE-One>
```

## Bundle 5

### Exercise 1

```bash
- On your Github repo enable Github pages
- Check if the link is publicly visible to anyone

here's my [🔗 link](https://alicade123.github.io/Gym-Git-Exercise-Solutions/) 
```

### Exercise 2

```bash
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git branch
* main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git add --all
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git commit -m "Change made in Index page"
[main ebd204e] Change made in Index page
 1 file changed, 283 insertions(+), 226 deletions(-)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.45 KiB | 744.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Alicade123/git-cafe-exercise.git
   d1d3f9c..ebd204e  main -> main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise>
```

## Bundle 6

### Exercise 1

```bash
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise>
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git branch "ft/menu-page"
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git branch
  ft/menu-page
* main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git checkout ft/menu-page
Switched to branch 'ft/menu-page'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git branch
* ft/menu-page
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git status
On branch ft/menu-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        images/image.png
        menu.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git branch
* ft/menu-page
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git status
On branch ft/menu-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        images/ie8-panel/image.png
        images/image.png
        menu.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git add --all
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git commit -m "Added menu page"
[ft/menu-page 1c8dd9c] Added menu page
 3 files changed, 25 insertions(+)
 create mode 100644 images/ie8-panel/image.png
 create mode 100644 images/image.png
 create mode 100644 menu.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git push origin ft/menu-page
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 12 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 1.58 MiB | 965.00 KiB/s, done.
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/menu-page' on GitHub by visiting:
remote:      https://github.com/Alicade123/git-cafe-exercise/pull/new/ft/menu-page
remote:
To https://github.com/Alicade123/git-cafe-exercise.git
 * [new branch]      ft/menu-page -> ft/menu-page
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git status
On branch ft/menu-page
nothing to commit, working tree clean
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git branch
* ft/menu-page
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise>
```

### Exercise 2

```bash
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git branch "fix/bug"
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git checkout fix/bug
Switched to branch 'fix/bug'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git branch
* fix/bug
  ft/menu-page
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git commit -am "The bug fixed title from menu to contact"
[fix/bug 36463cc] The bug fixed title from menu to contact
 1 file changed, 172 insertions(+), 157 deletions(-)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git status
On branch fix/bug
nothing to commit, working tree clean
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git push origin fix/bug
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.20 KiB | 1.20 MiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'fix/bug' on GitHub by visiting:
remote:      https://github.com/Alicade123/git-cafe-exercise/pull/new/fix/bug
remote:
To https://github.com/Alicade123/git-cafe-exercise.git
 * [new branch]      fix/bug -> fix/bug
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git status
On branch fix/bug
nothing to commit, working tree clean
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git branch
* fix/bug
  ft/menu-page
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise>
```

### Exercise 3

```bash
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git branch
* fix/bug
  ft/menu-page
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git status
On branch fix/bug
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index-4.html

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git add .\index-4.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git status
On branch fix/bug
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index-4.html

PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git commit -m "fix:hot-fix change index-4 telephone from PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git branch "fix/bug"
>> PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git checkout fix/bug
>> Switched to branch 'fix/bug'
>> PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git branch
>> * fix/bug
>>   ft/menu-page
>>   main
>> PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git commit -am "The bug fixed title from menu to contact"
>> [fix/bug 36463cc] The bug fixed title from menu to contact
>>  1 file changed, 172 insertions(+), 157 deletions(-)
>> PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git status
>> On branch fix/bug
>> nothing to commit, working tree clean
>> PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git push origin fix/bug
>> Enumerating objects: 5, done.
>> Counting objects: 100% (5/5), done.
>> Delta compression using up to 12 threads
>> Compressing objects: 100% (3/3), done.
>> Writing objects: 100% (3/3), 1.20 KiB | 1.20 MiB/s, done.
>> Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
>> remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
>> remote:
>> remote: Create a pull request for 'fix/bug' on GitHub by visiting:
>> remote:      https://github.com/Alicade123/git-cafe-exercise/pull/new/fix/bug
>> remote:
>> To https://github.com/Alicade123/git-cafe-exercise.git
>>  * [new branch]      fix/bug -> fix/bug
>> PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git status
>> On branch fix/bug
>> nothing to commit, working tree clean
>> PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git branch
>> * fix/bug
>>   ft/menu-page
>>   main
>> PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> "
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git commit -m "fix:hot-fix change index-4 telephone from +1 800 603 6035 to +1 800 659 6035"
[fix/bug 4e17113] fix:hot-fix change index-4 telephone from +1 800 603 6035 to +1 800 659 6035
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git status
On branch fix/bug
nothing to commit, working tree clean
```

### Exercise 4

```bash
- Review two PRs from your peers and request some changes on those PRs —> your peers need to give you access to their repository for you to review them.

- Once, they have adjusted the requested changes, approve and merge that PR.
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git branch
* fix/bug
  ft/menu-page
  main
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git checkout ft/menu-page
Switched to branch 'ft/menu-page'
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git status
On branch ft/menu-page
nothing to commit, working tree clean
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git add .\menu.html
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git status
On branch ft/menu-page
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   menu.html

PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git commit -m "The Implemention of feedback the new pragraph added"
[ft/menu-page 7ebacad] The Implemention of feedback the new pragraph added
 1 file changed, 37 insertions(+), 6 deletions(-)
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise> git push origin ft/menu-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.03 KiB | 1.03 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Alicade123/git-cafe-exercise.git
   1c8dd9c..7ebacad  ft/menu-page -> ft/menu-page
PS C:\xampp\htdocs\The Gym Phase2\GIT_BASICS\git-cafe-exercise>
```
