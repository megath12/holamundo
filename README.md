# holamundo
Aprender a usar GitHub

especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ -R
-R: no se encontró la orden
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ ls
primer_repo
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ rm
rm: falta un operando
Pruebe 'rm --help' para más información.
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ rm 
rm: falta un operando
Pruebe 'rm --help' para más información.
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ -R
-R: no se encontró la orden
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ -R primer_repo
-R: no se encontró la orden
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ rm  primer_repo
rm: no se puede borrar 'primer_repo': Es un directorio
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ -R  primer_repo
-R: no se encontró la orden
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ ls
primer_repo
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ rm -R  primer_repo
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ ls
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ clear

especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ git clone https://github.com/megath12/holamundo.git
Clonar en «holamundo»...
fatal: unable to access 'https://github.com/megath12/holamundo.git/': Could not resolve host: github.com
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ ls
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ git clone https://github.com/megath12/holamundo.git
Clonar en «holamundo»...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Comprobando la conectividad… hecho.
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ ls
holamundo
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit$ cd holamundo
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ ls
README.md
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ nano hola_muno.py
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ python hola_muno.py
Hol mundo
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ git add .
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ git commit -m "Se ha creado el hola mundo"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'especialidad@especialidad-OptiPlex-9020.(none)')
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ git push origin master
Username for 'https://github.com': git config --global user.email "megath@live.com"
Password for 'https://git config --global user.email "megath@live.com"@github.com': 
fatal: unable to access 'https://github.com/megath12/holamundo.git/': Could not resolve host: github.com
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ git config --global user.email "megath@live.com"
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ git config --global user.name "megath12"
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ git config --global user.email "megath@live.com"
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ git config --global user.name "megath12"
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ git commit -m "Se ha creado el hola mundo"
[master cbd717f] Se ha creado el hola mundo
 1 file changed, 1 insertion(+)
 create mode 100644 hola_muno.py
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ git push origin master
fatal: unable to access 'https://github.com/megath12/holamundo.git/': Could not resolve host: github.com
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ git status
En la rama master
Su rama está delante de «origin/master» para 1 commit.
  (use "git push" to publish your local commits)
nothing to commit, working directory clean
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ git push
warning: push.default is unset; its implicit value has changed in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the traditional behavior, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

When push.default is set to 'matching', git will push local branches
to the remote branches that already exist with the same name.

Since Git 2.0, Git defaults to the more conservative 'simple'
behavior, which only pushes the current branch to the corresponding
remote branch that 'git pull' uses to update the current branch.

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

Username for 'https://github.com': megath12
Password for 'https://megath12@github.com': 
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 302 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/megath12/holamundo.git
   d5e2334..cbd717f  master -> master
especialidad@especialidad-OptiPlex-9020:~/Dev/tallerGit/holamundo$ 

