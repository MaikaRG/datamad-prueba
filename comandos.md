## Crear un repo git
git init
## COmitear los cambios en ficheros
git commit -am "Mensaje"
##Ver el estado actual del repo
git status
## Subir todos los commits a gitHub
git push origin master
## Revisar que el repo local esta vinculado correctamente con github
git remote -v

## PR - Pull Request

Cuando no puedas realizar un push porque no tienes permisos, haz una PR.
Ejemplo: labs de clase.

### Formato titulo PR
[lab-XXXX] <Nombre Completo>

## Crear una rama
git checkout -b <nombre_nueva_rama>

## Moverse a otra rama
git checkout <nombre rama>

## Comprobar en que rama estoy
git status

## Merge
1. Ir a la rama donde queremos incorporar los cambios
2. Realizar el merge (opcionalmente resolviendo conflictos)
