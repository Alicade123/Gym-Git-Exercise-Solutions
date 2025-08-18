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
