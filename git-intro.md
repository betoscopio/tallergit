# Introducción a Git

## Qué es un DSCVS y por qué usarlo?

[![Perfection](https://preview.redd.it/05b6u19pseoz.png?width=960&crop=smart&auto=webp&s=71ebd902c8adf4ed1f30a8c3d99a99cb0f9a7888)](https://www.reddit.com/r/ProgrammerHumor/comments/72rki5/the_real_version_control/)

## Breve historia
![Cheap talk](https://i.imgflip.com/1issnv.jpg)

También Linus.

![Linus](http://www.quickmeme.com/img/16/166e431445962d77fa8f67aa677ab49b2fc67894f1385e0d1bb370d59a2cb681.jpg)

## Definición de conceptos
 The git parable:

 - Es una máquina del tiempo
 - Registro de cambios. Git permite generar snapshots de distintos momentos de la historia a los cuales puedo moverme libremente. Cada registro tiene un enlace asociado para recordarlo mejor.
 - Diversas veriones de una base de código independientes.

## Instalación

## Uso básico
  - Git config
  ```
  $ git config --list --show-origin
  $ git config --global user.name "John Doe"
  $ git config --global user.email johndoe@example.com
  ```
  - Iniciar repositorio
  `$ git init`
  `$ git add`
  - Commits
  `$ git commit -m "Mensaje relevante y explicativo del cambio."`
  - Revisando la historia
  ```
  $ git log
  $ git log --oneline
  $ git log --oneline --decorate
  $ git log --graph --oneline --decorate
  $ git log --stat
  $ git log -p
  $ git shortlog
  $ git log -3
  $ git log --after="2018-5-1"
  $ git log --after="yesterday"
  $ git log --after="2014-7-1" --before="2014-7-4"
  $ git log --author="Beto"
  $ git log --grep="Mensaje"
  ```

  - Branches
    ```
    $ git brach rama
    $ git checkout rama
    $ git checkout -b otra-rama
    ```

  - Revisar diferencias
    ```
    $ git diff <source_branch> <target_branch>
    ```
  - Clonar
  ```
  $ git clone /path/to/repository
  $ git clone username@host:/path/to/repository
  ```
 -  Repositorios remotos
    `git remote -v`
    `git remote add origin https://github.com/betoscopio/tallergit.git`
    `git push -u origin master`
 - Push/Pull
    ```
    git fetch
    git merge
    git pull
    ```
 - Sobreescribiendo la historia
   `$ git revert`
 - Ojo ahí. **Precaución**
  ```
  $ git checkout -- <filename>
  $ git fetch origin
  $ git reset --hard origin/master
  ```
 -  Proveedores Git
    - [Github](https://github.com/)
    - [Bitbucket](https://bitbucket.org/)
    - [Gitlab](https://about.gitlab.com/)
 -  Auditando cambios
    ```
    $ git blame file
    $ git blame -L 1,5 README.md
    $ git blame -M README.md
    $ git blame -C README.md
    ```

# Ejercicio práctico:
  - Trabajo en un proyecto colaborativo.
  - Descargar [Intializr](http://www.initializr.com/)
  - Generar cambios a una web común.
  - Resolución de conflictos
## Modelos de desarrollo

## Publicación en Github Pages
  - https://pages.github.com/


## Referencias
- https://git-scm.com/book/en/v2
- https://www.atlassian.com/git
- https://www.atlassian.com/git/tutorials  
- https://hackr.io/tutorial/git-guru-guide-by-atlassian
- https://learngitbranching.js.org/  
- http://rogerdudler.github.io/git-guide/  
- https://hackr.io/tutorial/git-the-simple-guide  
- http://try.github.io/  
- https://hackr.io/tutorial/git-the-simple-guide
- https://hackr.io/tutorials/learn-git  
