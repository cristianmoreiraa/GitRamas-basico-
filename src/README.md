# Ramas Básico
## Pasos:

- 1: Primero hacemos 2 commits en la rama master


        git init
        git commit -m "A"
        git commit -m "B"

- 2: Creamos la nueva rama **'exp'**, nos cambiamos a esa nueva rama y comprobamos que nos hayamos cambiado correctamente


        git branch exp
        git checkout exp
        git branch
- 3: Hacemos un commit en esta rama **'C'**
  
        git commit -m "C"
- 4: Nos volvemos a cambiar a la rama **'master'** y hacemos el commit 'E'
        
        git checkout master
        git commit -m "E"
- 5: Cambiamos a la rama **'exp'** y hacemos el commit 'D'

        git checkout exp
        git commit -m "D"
- 6: Volvemos a la rama **'master'** y hacemos el git merge
  
        git checkout master
        git merge