# Iniciar un repositorio de git 

    $ git init 

# Verificar el estado de un repositorio 

    $ git status

# Ver listado de ramas (branches) de un repositorio 

    $ git branch

# Preparar archivos (staged) para guardarlos en el repositorio

    $ git add <File>
    
    $ git add -A

    $ git add .

    $ git add *

# Guardar archivos (commit) en el repositorio

    $ git commit -m "Mensaje del Commit"

# Extraer archivo (checkout) del repositorio o rama (branch)

    $ git checkout <File>/<Branch>

# Ver listado de cambios

    $ git log

# Crear una nueva rama(branch)

    $ git brach <branch-name>

    $ git checkout -b <branch-name>

# Unir ramas (branch) usando merge

    $ git merge <branch>


# Eliminar una rama(branch)

    $ git branch -D <branch-name>


# Agregar repositorio remoto

    $ git remote add <remote-name> <url-repositorio>

# Ver informacion del repitorio remoto

    $ git remote show <remote-name>

# Eliminar repositorio remoto

    $ git remote rm <remote-name>

# Actualizar repositorio remoto 

    $ git remote set-url <remote-name> <url-repositorio>

# Subir cambios al repositorio remoto

    $ git push <remote-name> <branch-name>

# Update repositio local con los cambios del repositorio remoto

    $ git pull <remote-name> <branch-name>

# Clonar repositorio remoto

    $ git clone <url-repositorio>

    $ git clone -b <branch> <url-repositorio> 