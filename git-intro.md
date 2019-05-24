# Introducción a Git

## Qué es un CVS y por qué usarlo?



## Breve historia

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
  - Branches
  - Clonar
  ```
  $ git clone /path/to/repository
  $ git clone username@host:/path/to/repository
  ```
 -  Repositorios remotos
    `git remote -v`
    `git remote add origin https://github.com/betoscopio/tallergit.git`
 - Push/Pull
    `git push -u origin master`
 -  Proveedores Git
   - [Github](https://github.com/)
   - [Bitbucket](https://bitbucket.org/)
   - [Gitlab](https://about.gitlab.com/)
 -  Auditando cambios

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
