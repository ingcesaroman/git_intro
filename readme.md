#Intro
* Que es Git?
* Que es Gituhub?
* Porque me debe inportar?
* Analogia Novel escribiendo 
* Instalar Git

# Directorio (Working Derectory)
- Area donde todos nuestros archivos, directorios y cambios se almacenan todo el tiempo

# Staging Area
- Archivos y directorios que se almacenan temporalmente en linbo entre un repositorio y directorio 

# Repositorio (Git Repository)
Donde todos nuestros checkpoints son guardados
#Git Basico
* Git --version (version instalada)
* touch <file> (crea un nuevo archivo)
* Git init     (Inicia un repositorio Git nuevo)
* Git status   (Desglosa informacion del repo)
* Git add <file>/ *.js / . (Seleccionas que chieres agregar a ese checkpoint al repo)
* Git commit    (agregas el checkpoint al repo)
* .. -m "msg"   (agregar un mensaje al commit)

status -> add -> commit -> status -> add -> commit

#Git Checkout
* Git Log
* Git Checkout
* Git revert --no-commit 0766c2..HEAD
 
    HEAD
    0 -> 0 -> 0 -> 0
                   Master
# Comandos adicionales
* Git reset HEAD <file> (para eliminarlo de staging)

# Git Branches
* Git branch (visualizar el repositorio en el que estamos)
* Git checkout -b <branch_name> (crear un nuevo banch)
* Git checkout master / <branch_name> (cambiar de branch)
* Git merge <master> / <branch_name> (combinar dos branches)
Master
 0 ---> 0 ---> 0 ---> 0 --> 0
         \                 / Git merge <master>
          \->0 ---> 0 --> 0 
          branch_name

# Github para subir a la nube tu instancia
* SSH and keys
* Git remote add origin <github_path>
* Git remote -v (confirmar que el repo se haya creado)
* Git push -u origin master / <banch_name> (actualizar repo en github)
