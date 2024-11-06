Creamos ubn nuevo repo Crea una rama main con 3 commits Crea una rama feature con 2 commits Vuelva a main y añade un commit Mergea la rama feature en main

¿Que estrategia usará git? ort (Recursive)

# Ejercicio 2 Git

## Creación del proyecto
- Crear carpteta gti.exercice2
- Abrir consola en la carpeta
- git init
- hacer commit "Initial commit"

## Bucle de 3 commit
- crear archivo archivox.html
- git add archivox.html
- git status
- comprobar que archivo está listo para commit
- git commit -m "Add archivox.html"

## Comprobar los commit
- git log --oneline

## Crear rama feature
- Crear rama feature: git branch feature
- Cambiar a rama feature: git checkout feature
- Ambos pasos se pueden fusionar un uno solo con: git checkout -b feature
- Comprobar los cambios: git log --oneline

## Bucle de 2 commit
- crear archivofx
- git add archivofx.html
- git status
- comprobar que archivo está listo para commit
- git commit -m "Add archivofx.html"

## Comprobar log
- Comprobar los cambios: git log --oneline

    3d3e76e (HEAD -> feature) Add archivof2.html
    2d043b4 Add archivof1.html
    e782ded (main) Add archivo3.html
    35be1a6 Add archivo2.html
    1ff64d8 Add archivo1.html
    bf4a928 Initial Commit

## Volver a rama main y crear 1 commit
- Volver a main: git checkout main
- crear archivo archivom1.html
- git add archivom1.html
- git commit -m "Add archivom1.html
- comprobar log: git log --oneline


a
## Merge rama feature en main
- Comprobar el log: git log --oneline
- Cambiar a rama main: git checkout main
- Hacer merge de las ramas feature: git merge feature
- Comprobar cambios: git log --oneline



