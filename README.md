# git_notes
Apuntes de comandos git

// para ignorar archivos de manera local, pero no elinminarlos del repositorio remoto de git
// imaginemos que queremos tener distintas configuraciones en local dentro del mismo equipo
// pero no queremos modificar esa config de la rama real, ni tampoco tener que estar quitandolo
// de nuestros commits manualmente:

- para ignorar el archivo: git update-index --assume-unchanged <file>
- para revertir los cambios: git update-index --no-assume-unchanged <file>
- para listar los ignorados de esta manera: git ls-files -v | grep '^h '

