mi primerproyecto 
# QUE ES GIT? 
git es un sistema de control de versiones que registra los cambios en los archivos 
---
---
## VENTAJAS
---
se puede viajar entre versiones 
se tiene diferentes estados 
1. estado: working directory aqui se edita y se trabaja con el proyecto 
2. estado: staning area: se elige que archivos estan listos para pasar al tercer estado
3. estado: repository: en este estado se registra todo el proyecto 
---
## COMANDOS 
---
1. **git config --globlal user.name**  (nombre con el cual la consola te indentificara )
2. **git config --globlal user.email**
3. **git config --list** (lista de las configuraciones)
4. **git init** (marca el inicio de nuestro proyecto)
5. **git status** (muestra el estado del proyecto )
6. **git add** (añadir un archivo)
7. **git commit -m "mensaje"** (añade un commit)
8. **git log** (lista de los commits)
9. **git checkout** (viajar entre commits)
10. **git reset** 
# RAMAS Y FUSIONES 
## HEAD
es el commit principal donde te encuentras desde un comienzo
## RAMAS
es una linea de tiempo en nuestro proyecto que nos sirven para arreglar errores, experimentar y hacer grandes cambios 
1. rama master es la rama principal de nuestro pproyecto 
# COMANDOS 2 
- git branch : muesta las ramas que tenemos 
- git branch "nm" : crear nueva rama 
- git checkout: movernos entre ramas o commits
- git branch -b "nm r" crear y movernos a la rama 
# FUSIONES 
---
es la creacion de un commit juntando una rama con la otraa 
1. nos situamos en la rama que va a absorver 
2. fusionar con git merge "nombre de la rama"

**EXITEN 2 TIPOS DE FUSIONES**
1. **FASTFORWARD** :es simple y automatico 
2. **MANUAL MERGE** : es largo y fusion manual

# GIT HUB 
es una plataforma donde se puede guardar el proyecto usando git para su gestion 

- **git clone** sirve para clonar un proyecto normalmente se usa cuando no nos interesa colaborar en el proyecto 
---
## NUESTRO PROYECTO EN GIT HUB 
--- 
EXITEN 2 TIPOS
- remoto : son los que se encuentran en la nume (git hub)
- local : son los que se encuentran almacenados de forma local (nuestra PC)
---
## COMANDOS 3
- **git remote** : vincula el proyecto local con el remoto 
- **git remote add oriin "enlace de git hub"** : para concretar la vinculacion 
- **git remote remove** : borra el proyecto de linea 
- **git push** : manda nuestros cambios (commits) a github 
--- 
**ISSUES:** Son la forma de continuar, mejorar o solucionar un error en nuestro repositorio 

**MILESTONE:** Son grupos de issues que aplican para un proyecto, caracteristica o periodo de tiempo

**LABELS:** son unamanera de organizar diferentes tipos de problemas 

# TAGS 
son simples puntos especificos en la historia de nuestro proyecti y se usan para marcar alguna version del mismo 

**-TAG ANOTADOS:** Son alamcenados como objeto completos dentro de la base de git y contiene mas informacion 

**-TAG LIGERA:** Son otra forma de crear tags mas simples y con poca informacion 

**-git tag -a n "numero de version" -m "nombre"** sirve para crear tags
para asignar un tag a un commit se utiliza el mismo comando anterior con la difenrencia que al final se agrega el codigo **sha**

**-git push origin v"n"** sirve para subir el tag 

**-git push origin --tags** sirven para subir todos los tags 
