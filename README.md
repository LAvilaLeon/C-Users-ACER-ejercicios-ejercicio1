# 1) Abrir la consola e imprimir la ubicación actual.
comando:
```
PS C:\Users\ACER> pwd
```
salida:
``` 
Path
----
C:\Users\ACER
```
# 2)  Crear una carpeta llamada  `ejercicios`  desde la consola.

comando:
```
mkdir ejercicios
``` 

# 3) Cambiar la ubicación a la nueva carpeta que crearon.

comando: 

```
cd ejercicios
```

# 4) Abrir la carpeta con VSCode.

comando:
```
code .
```

# 5) En VSCode crear una carpeta `ejercicio1`


# 6) Crear un archivo llamado  `README.md`  (vacío) dentro de la carpeta  `ejercicio1`.



# 7) Configurar nombre e email globalmente en git.

comando nombre :
```
git config --global user.name Luisa Avila
```
comando email :
```
git config --global user.email luavila.leon@gmail.com
```
# 8) Inicializar el repositorio de git desde la línea de comandos desde la carpeta  `ejercicios`.
comando :
```
git init
```
salida :
```
Initialized empty Git repository in C:/Users/ACER/ejercicios/.git/
```
# 9) Crear un primer commit con el mensaje “Versión Inicial”. 
comando:
```
PS C:\Users\ACER\ejercicios> git add .
PS C:\Users\ACER\ejercicios> git commit -m "Versión Inicial"
```
salida :
```
[master (root-commit) b8b2a5a] Versión Inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ejercicio1/README.md
 ```
 
#  10) Agregar al  `README.md`  los comandos que ejecutaron en cada paso.


# 11) Crear un nuevo commit con el mensaje “Agrega solución primer ejercicio”
comando :
```
PS C:\Users\anyba\ejercicios> git add .
PS C:\Users\anyba\ejercicios> git commit -m "agrega solucion primer ejercicio"
```
salida :
 ```
[master 379231f] agrega solucion primer ejercicio
 1 file changed, 76 insertions(+)
PS C:\Users\ACER\ejercicios>
 ```