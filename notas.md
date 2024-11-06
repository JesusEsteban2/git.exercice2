Creamos ubn nuevo repo Crea una rama main con 3 commits Crea una rama feature con 2 commits Vuelva a main y añade un commit Mergea la rama feature en main

¿Que estrategia usará git? ort (Recursive)

# Ejercicio 2 Git

## Creación del proyecto
- Crear carpteta gti.exercice1
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

## Volver a rama main y crear 1 commit


## Merge rama feature en main
- Comprobar el log: git log --oneline
- Cambiar a rama main: git checkout main
- Hacer merge de las ramas feature: git merge feature
- Comprobar cambios: git log --oneline



