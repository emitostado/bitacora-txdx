# Glosario de Git

Definiciones rápidas de los comandos y conceptos que uso todos los días.

## Comandos

### git init

Convierte una carpeta normal en un repositorio de Git. Crea la carpeta oculta `.git`.

### git add

Registra los cambios y agrega el archivo especifico.

### git commit

Guarda los cambios del proyecto en local.

### git push

Envía los commits de tu rama local al repositorio remoto.

### git pull

Trae los cambios del repositorio remoto y los integra en tu rama local.

### git status

Muestra qué archivos modificaste y cuáles están listos para commitear.

### git log

Muestra el historial de commits, del más reciente al más antiguo.

### git restore

Deshace cambios y los regresa a una version anterior.

### git commit --amend

Crea un commit nuevo remplazando al anterior, el commit viejo no desaparece pero no se visualiza en la rama pricipal.

### git branch

Lista las ramas locales del repositorio. Con un nombre después, crea una rama nueva.

## Conceptos

### Commit

Una foto del proyecto en un momento dado, con un mensaje que explica qué cambió.

### Rama (branch)

Una línea de trabajo paralela. Te deja hacer cambios sin tocar `main` hasta que estén listos.

### origin

El nombre predeterminado y abreviado que se le asigna al repositorio remoto de donde clonaste o copiaste un proyecto originalmente

### HEAD

Apunta al commit en el que estás parado ahora mismo.

### Pull Request

Una petición para integrar los cambios de tu rama en otra rama del proyecto.
