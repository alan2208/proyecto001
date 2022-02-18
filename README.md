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