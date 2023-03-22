
EJ1
$ git clone ^[[200~https://github.com/adwinmbd/astro-blog-template~^[[200~https://github.com/adwinmbd/astro-blog-template~
Cloning into 'astro-blog-template~'...
fatal: protocol '?[200~https' is not supported


$ git clone https://github.com/adwinmbd/astro-blog-template
Cloning into 'astro-blog-template'...
remote: Enumerating objects: 263, done.
remote: Counting objects: 100% (117/117), done.
remote: Compressing objects: 100% (76/76), done.
remote: Total 263 (delta 42), reused 91 (delta 28), pack-reused 146
Receiving objects: 100% (263/263), 570.66 KiB | 709.00 KiB/s, done.
Resolving deltas: 100% (95/95), done.


$ cd astro-blog-template


$ git init
Reinitialized existing Git repository in C:/Users/34672/Desktop/Carpeta git/EJ3examen/astro-blog-template/.git/

EJE 2 
$ git branch
* main

34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (main)
$ git branch refactorizacion

34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (main)
$ git branch
* main
  refactorizacion

34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (main)
$ git checkout refactorizacion
Switched to branch 'refactorizacion'
EJE3
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (refactorizacion)
$ echo "Refactoring is a systematic process of improving code without creating new functionality that can transform a mess into clean code and simple design." > refactorizacion.txt
EJE 4
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (refactorizacion)
$ git add refactorizacion.txt
EJE 5
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (refactorizacion)
$ git commit -m "Añadido concepto de refactorizacion"
[refactorizacion 270c7ee] Añadido concepto de refactorizacion
 1 file changed, 1 insertion(+)
 create mode 100644 refactorizacion.txt
EJE6
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (refactorizacion)
$ git log --oneline --decorate --all
270c7ee (HEAD -> refactorizacion) Añadido concepto de refactorizacion
389bdf9 (origin/main, origin/HEAD, main) feat: upgrade to astro v1.06
d3c2f28 feat: add await to fetch calls.
4d50b5c feat: add post page.
7f339eb feat:add contact page.
62e0aa0 refractor: move tags page to the same level as home page.
c11bdcb feat: add favicon.
606c630 feat: add styling to tags.
12ef5ad feat: add markdown code styling.
7eac459 feat: add tagging functionality.
fa777df refractor: delete unecessary files.
fee9ac4 refractor: updated projected description in README.
6ae1908 feat: add pagination.
01e4b82 feat: add tag list.
06dd743 fix: patch posts not visible bug.
b2ba584 refractor: remove unecessary comments.
6adef41 feat: add initial source files.
351bd9b Initial commit
EJE7
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (refactorizacion)
$ git branch patrones


34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (refactorizacion)
$ git checkout patrones
Switched to branch 'patrones'
A       patrones.txt

EJE8

34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (patrones)
$  echo "Los patrones de diseño (design patterns) son soluciones habituales a problemas comunes en el diseño de software." > patrones.txt

EJE9

34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (patrones)
$ git add patrones.txt
EJE10
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (patrones)
$ git commit -m "Añadida primera modificacion de patrones"
On branch patrones
nothing to commit, working tree clean
EJE11
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (patrones)
$  git log --oneline --decorate --all
270c7ee (HEAD -> patrones, refactorizacion) Añadido concepto de refactorizacion
389bdf9 (origin/main, origin/HEAD, main) feat: upgrade to astro v1.06
d3c2f28 feat: add await to fetch calls.
4d50b5c feat: add post page.
7f339eb feat:add contact page.
62e0aa0 refractor: move tags page to the same level as home page.
c11bdcb feat: add favicon.
606c630 feat: add styling to tags.
12ef5ad feat: add markdown code styling.
7eac459 feat: add tagging functionality.
fa777df refractor: delete unecessary files.
fee9ac4 refractor: updated projected description in README.
6ae1908 feat: add pagination.
01e4b82 feat: add tag list.
06dd743 fix: patch posts not visible bug.
b2ba584 refractor: remove unecessary comments.
6adef41 feat: add initial source files.
351bd9b Initial commit
EJE12
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (patrones)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (main)
$ git merge patrones
Updating 389bdf9..270c7ee
Fast-forward
 refactorizacion.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 refactorizacion.txt
EJE13
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (main)
$  git log --oneline --decorate --all
270c7ee (HEAD -> main, refactorizacion, patrones) Añadido concepto de refactorizacion
389bdf9 (origin/main, origin/HEAD) feat: upgrade to astro v1.06
d3c2f28 feat: add await to fetch calls.
4d50b5c feat: add post page.
7f339eb feat:add contact page.
62e0aa0 refractor: move tags page to the same level as home page.
c11bdcb feat: add favicon.
606c630 feat: add styling to tags.
12ef5ad feat: add markdown code styling.
7eac459 feat: add tagging functionality.
fa777df refractor: delete unecessary files.
fee9ac4 refractor: updated projected description in README.
6ae1908 feat: add pagination.
01e4b82 feat: add tag list.
06dd743 fix: patch posts not visible bug.
b2ba584 refractor: remove unecessary comments.
6adef41 feat: add initial source files.
351bd9b Initial commit
EJE14
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (main)
$ git branch -D patrones
Deleted branch patrones (was 270c7ee).
EJE15
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (main)
$ git branch patrones
$ git checkout patrones
EJ16
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (patrones)
$ echo "Cada patrón es como un plano que se puede personalizar para resolver un problema de diseño particular de tu código." > patrones.txt
EJE17

34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (patrones)
$ git add patrones.txt
EJE18
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (patrones)
$ git commit -m "añadida definicion 2 de patrones de diseño"
[main 167940d] añadida definicion 2 de patrones de diseño
 1 file changed, 1 insertion(+)
 create mode 100644 patrones.txt


EJE19
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (main)
$ git checkout main
main 


34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ3examen/astro-blog-template (main)
