# Esta es la Práctica de Git

Práctica de git realizada en clase.

# Probando comandos

```
git commit -a -m "mensaje"
```

Sirve para obviar el add

# Proceso realizado en cmd
git add .
git commit -m "Documento Sebastian"
git config --global user.email chsebas98@gmail.com
gint config --global user.username Sebastian
On branch master
Your branch is up to date with 'origin/master'.

  (use "git add <file>..." to include in what will be committed)
        doc2Sebastian.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git add .
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git commit -a -m "Doc 2"
[master 24dce4a] Doc 2
 1 file changed, 0 insertions(+), 0 deletions(-)
Enumerating objects: 4, done.
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git add .
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git commit -m "Rama1"
[rama1 72a862c] Rama1
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git push
fatal: The current branch rama1 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin rama1

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git push --set-upstream origin rama1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Writing objects: 100% (3/3), 327 bytes | 327.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
To https://github.com/Chsebas98/practica_git.git
 * [new branch]      rama1 -> rama1
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git branch
  master
* rama1
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> giit add .
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git add .
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git commit -m "docRama1"
[rama1 bbcefaf] docRama1
 1 file changed, 1 insertion(+)
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git push
Enumerating objects: 4, done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 357 bytes | 357.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Chsebas98/practica_git.git
   72a862c..bbcefaf  rama1 -> rama1
Your branch is up to date with 'origin/master'.
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git merge rama1
Updating 24dce4a..bbcefaf
Fast-forward
 doc2Sebastian.txt | 1 +
 2 files changed, 2 insertions(+)
 create mode 100644 docRama1.txt
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git add .
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
nothing to commit, working tree clean
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
   24dce4a..bbcefaf  master -> master
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git branch
* master
  rama1
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git add .
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git commit -m "Doc para pasar a la rama"
[master bebd606] Doc para pasar a la rama
 1 file changed, 1 insertion(+)
 create mode 100644 docParaPasarRama.txt
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 307 bytes | 307.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Chsebas98/practica_git.git
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git checkout rama1
Switched to branch 'rama1'
Your branch is up to date with 'origin/rama1'.
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git merge master
Updating bbcefaf..bebd606
Fast-forward
 docParaPasarRama.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 docParaPasarRama.txt
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Chsebas98/practica_git.git
   bbcefaf..bebd606  rama1 -> rama1
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git>n branch master
Your branch is up to date with 'origin/master'.

  (use "git add <file>..." to include in what will be committed)
        doc2Sebastian.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git add .
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git commit -a -m "Doc 2"
[master 24dce4a] Doc 2
 1 file changed, 0 insertions(+), 0 deletions(-)
Enumerating objects: 4, done.
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git add .
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git commit -m "Rama1"
[rama1 72a862c] Rama1
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git push
fatal: The current branch rama1 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin rama1

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git push --set-upstream origin rama1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Writing objects: 100% (3/3), 327 bytes | 327.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
To https://github.com/Chsebas98/practica_git.git
 * [new branch]      rama1 -> rama1
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git branch
  master
* rama1
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> giit add .
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git add .
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git commit -m "docRama1"
[rama1 bbcefaf] docRama1
 1 file changed, 1 insertion(+)
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git push
Enumerating objects: 4, done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 357 bytes | 357.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Chsebas98/practica_git.git
   72a862c..bbcefaf  rama1 -> rama1
Your branch is up to date with 'origin/master'.
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git merge rama1
Updating 24dce4a..bbcefaf
Fast-forward
 doc2Sebastian.txt | 1 +
 2 files changed, 2 insertions(+)
 create mode 100644 docRama1.txt
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git add .
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
nothing to commit, working tree clean
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
   24dce4a..bbcefaf  master -> master
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git branch
* master
  rama1
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git add .
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git commit -m "Doc para pasar a la rama"
[master bebd606] Doc para pasar a la rama
 1 file changed, 1 insertion(+)
 create mode 100644 docParaPasarRama.txt
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 307 bytes | 307.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Chsebas98/practica_git.git
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git checkout rama1
Switched to branch 'rama1'
Your branch is up to date with 'origin/rama1'.
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git merge master
Updating bbcefaf..bebd606
Fast-forward
 docParaPasarRama.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 docParaPasarRama.txt
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Chsebas98/practica_git.git
   bbcefaf..bebd606  rama1 -> rama1
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git branch
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git add .
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git commit -m "Last commit"
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git push
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git checkout master
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git merge rama1
PS C:\Users\labctr.BQV-LAB-SALA8\Documents\ESPE\practica-git> git push