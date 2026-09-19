# Glosario de Git

Definiciones rápidas de los comandos y conceptos que uso todos los días.

## Comandos

### `git init`

Convierte una carpeta en un repositorio de Git. Crea la carpeta oculta .git, donde Git almacena la información y el historial del repositorio.

### `git add`

Prepara los cambios para el siguiente commit, agregándolos al área de preparación (*staging area*). **No guarda los cambios en el historial por sí solo.**

### `git commit`

Guarda en el historial local los cambios que se encuentran en el área de preparación. Cada commit representa un estado concreto del proyecto.

### `git push`

Envía los commits de una rama local a un repositorio remoto.

### `git pull`

Descarga los cambios del repositorio remoto y los integra en la rama local actual. Por defecto, combina las operaciones de git fetch y `git merge`.

### `git status`

Muestra el estado actual del repositorio: archivos modificados, archivos preparados para el commit, archivos sin seguimiento y otros cambios pendientes.

### `git log`

Muestra el historial de commits de una rama, normalmente del más reciente al más antiguo.

### `git restore`

Restaura archivos a un estado anterior. Por ejemplo, descarta los cambios no preparados de ese archivo y lo devuelve al estado registrado en el índice. Los cambios descartados de esta forma pueden perderse.

### `git commit --amend`

Modifica el commit más reciente. Permite, por ejemplo, cambiar su mensaje o agregar cambios que olvidaste incluir. En realidad, reemplaza el commit anterior por uno nuevo con un identificador diferente.

### `git branch`

Lista las ramas locales. Al proporcionar un nombre, crea una nueva rama con ese nombre.

## Conceptos

### Commit

Una instantánea del estado del proyecto en un momento determinado. Incluye los cambios preparados y un mensaje que describe el commit.

### Rama (*branch*)

Una referencia que permite mantener una línea de desarrollo independiente. Permite trabajar en cambios sin modificar directamente la rama en la que se encuentra el desarrollo principal, como main.

### `origin`

El nombre remoto predeterminado que Git suele asignar al repositorio desde el que clonaste el proyecto. Es un alias para la URL del repositorio remoto y puede cambiarse o complementarse con otros remotos.

### `HEAD`

Una referencia que indica la posición actual de Git. Normalmente apunta al commit más reciente de la rama actual.

### Pull Request

Una solicitud para revisar y proponer la integración de los cambios de una rama en otra. Es una función proporcionada por plataformas como GitHub, GitLab o Bitbucket, no un comando propio de Git.

