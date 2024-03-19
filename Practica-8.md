1. **¿Cómo se inicializa un repositorio en Git?**
- Una vez registrada la cuenta dentro de Visual Studio Code con git se inicia con el código:
``` 
git Init
```
- Para poder vincular el repositorio con git, y así poder subir cualquier cambio que se haga.
2. **¿Cómo creas un repositorio en GitHub?**
- En la página de inicio de github hay 2 opciones para crear un repositorio, una es seleccionando una opción con el signo **+** para agregar o importar un repositorio, y donde está la sección top repositories hay una opción que dice **New** en el cual ya redirige a una pestaña para crear el repositorio.
3. **¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?**
- Para vincularlo se necesita guardar los cambios que se hagan dentro del repositorio de Visual Studio. Para subir un archivo nuevo a Git es:
``` 
git add aquí el nombre del archivo
```
- o para actualizar los cambios realizados es: 
``` 
git add .
```
Luego se tiene que agregar un commit que como función es agregar una nota de los cambios que se hicieron en ese momento:
``` 
git commit -m "Nombre del cambio"
```
- Para finalizar y subir el repositorio local al remoto es:
``` 
git push origin nombre de la rama
```
4. **¿Cuál es el flujo básico de trabajo en Git y GitHub?**
- Es la carpeta local donde se trabaja manualmente, luego donde se registran los cambios a git, luego donde se registran los cambios del repositorio con los commits y por último cuando se almacenan en las plataformas como github
5. **¿Para qué sirve el archivo .gitignore?**
- Es un archivo que tiene como proposito hacer que git ignore los archivos o carpetas que se introduzcan dentro del archivo .gitignore.
6. **¿Cuál es el propósito de una rama?**
- Tener diferentes versiones de un repositorio, una rama podría tener un archivo dentro de ella o algún cambio de un archivo que las demás ramas también compartan no se verán reflejados fuera de la utilizada.
7. **¿Qué es una fusión?**
- Es cuando 2 ramas juntan los cambios que tienen, pero antes hay que seleccionar la rama en la que se aplicará el contenido de la fusión. 
8. **Explica los diferentes tipos de fusión que existen.**
- una es en la cual nos dirigimos a la rama principal donde se efectua la fusión de forma automática, y la segunda es de forma manual para resolver problemas de duplicación.
9. **¿Cómo puedes ver el historial de tu repositorio?**
- Se pueder visualizar el historial del repositorio dentro de la consola mediante el código
``` 
git log
```
o tambian mediante un archivo como commits.txt utilizando el código
``` 
git log > commits.txt
```
10. **¿Cuál es el propósito de una etiqueta?**
- Principalmente se utiliza para poner versiones al proyecto.