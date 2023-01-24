# Pasos para Crear Repo
Se describe el paso a paso y comandos git que uso frecuentemente para crear repositorios en sistemas de control de versiones.

# Erase una vez ...
1. Crear repositorio en el systema de control de versiones
2. Clonar en local `git clone https://github.com/shlondon/PasosCrearRepo.git`
3. Ir a carpeta con repo cd NOMBREREPO
4. Crear rama development `git branch development`
5. Apuntar hacia rama development `git checkout development`
6. Verificar que se está apuntando a la rama development `git branch` 

# Regla de oro
- Trabajar sólo sobre rama desarrollo
- No tocar la rama main o principal o producción desde local
- Sólo modificar la rama principal desde el sistema de control de versiones usando *Pull Request*

# El día a día
1. `git status`
2. `git add .`
3. `git commit -m "Escribe mensaje corto que describe los cambios"`
4. `git push origin development`