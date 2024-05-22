# my-awesome-project
This awesome project is created to experiment git notions like clone, push and pull


---------------------- dans le GitBash : -------------------------------------

$ cd challenge

Daniel@RYOKOH_974 MINGW64 ~/challenge
$ git remote -v
fatal: not a git repository (or any of the parent directories): .git

Daniel@RYOKOH_974 MINGW64 ~/challenge
$ git init
Initialized empty Git repository in C:/Users/Daniel/challenge/.git/

Daniel@RYOKOH_974 MINGW64 ~/challenge (main)
$ git remote -v

Daniel@RYOKOH_974 MINGW64 ~/challenge (main)
$ git remote add origin git@github.com:Ryokoh-974/my-awesome-project.git

Daniel@RYOKOH_974 MINGW64 ~/challenge (main)
$ git pull origin main
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), 1.81 KiB | 44.00 KiB/s, done.
From github.com:Ryokoh-974/my-awesome-project
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main

Daniel@RYOKOH_974 MINGW64 ~/challenge (main)
$ git push origin main
Everything up-to-date
