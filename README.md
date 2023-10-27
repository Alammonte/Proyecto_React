Hola Mundo

git init <- crear el repo en local

# Pasos eventuales
git add <archivo> <- Puede ser un punto

git commit -m <mensaje> <- Preparar un commit

git branch -M main <- especifica que la rama principal es main

git remote add origin <url> <- añade un remoto

git push -u origin main <- empuja los cambios

# Cambiar de rama
## Tener los cambios ya subidos
## Ir a rama
git checkout <rama>

### Crear rama
git checkout -b <rama> 

## Cambios con Merge

* unifica los cambios entre rama1 y rama2 en rama2 
# git merge <remote/rama1> <remote/rama2>

* unifica los cambios entre main y Vistas en Vistas
git merge origin/main origin/Vistas