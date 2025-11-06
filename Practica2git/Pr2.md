# Practica 2 - GIT

1. Cread un repositorio (directorio) llamado practica2git e inicializa el sistema de control de versiones
```
mkdir Practica2git
git init
```
2. Cread un fichero llamado contenido.txt con el siguiente texto:
```
//Lo creo con notepad
notepad contenido.txt
- Introducción a linea de comandos
    - Windows
    - Linux
```
![repositorio practica2](img2/f1.png)

3. Comprobad el estado del repositorio
```
git status
```
![Estado repositorio](img2/f2.png)

4. Añadid el fichero a la zona de preparado
```
git add contenido.txt
```
5. Comprobad de nuevo el estado del repositorio
```
git status
```
![Zona preparado](img2/f3.png)

6. Haced el primer commit con su comentario correspondiente
```
git commit -m "Primer commit del fichero contenido.txt"
```
![Primer commit](img2/f4.png)

7. Añadid la línea al fichero:
```
notepad contenido.txt
- Mac
``` 
8. Compruebad de nuevo el estado del repositorio
```
git status
```
![Añadir linea al fichero](img2/f5.png)

9. Añadid el fichero a preparado
```
git add contenido.txt
```
10. Haced otro commit del fichero
```
git commit -m "Modificado contenido.txt"
```
11. Cambiad el mensaje del último commit por “Añadido la línea de MAC.”
```
//Para cambiar el mensaje del commit se usa:

$git commit --amend -m "Añadido la linea de Mac"
```
![Ultimo commit](img2/f6.png)