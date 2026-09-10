# Filesystem real: /etc, /var/log y /proc sin memorizar

**Ruta:** linux-real
**Fecha:** 2026-09-09
**Nivel:** beginner

## Objetivo del lab

Un recorrido práctico por las carpetas que más vas a tocar en Linux: configuración, logs, procesos, discos y rutas. La idea no es memorizar nombres, es saber dónde mirar.


## Comandos que usé
```bash
cd
```
Use este comando para cambiar de directorios en la terminal. 

```bash
ls
ls -lah
```
Use el primer comando para listar los archivos y directorios que esten dentro de una carpeta. Basicamente si no se que archivos o directorios busco, simplemente ejecuto el comando ls dentro del directorio de mi interes, y asi puedo visualizar que directorios contiene.
Use el segundo comando para ver los permisos, dueno, tamano y fechas de los archivos o directorios. 
```bash
pwd
```
Use pwd para que me diga la ruta actual en la que me encuentro pero igual de normalidad, en mi terminal me menciona en cual ruta me encuentro.

```bash
stat .
```
stat me dio metadata mas precisa del archivo o directorio.

```bash
df -h
```
MUestra los filesystems montados. 

```bash
du -sh
```
Suma el tamano de una carpeta. Es decir si tengo una carpeta con varias cosas y acceso a su directorio, y uso el comando, me va a dar la suma de todo lo que tiene.



## Qué aprendí / por qué funciona
`/proc:` procesos como archivos
El directorio proc no es una carpeta normal. Basicamente, lo que hace es mostrar el estado vivo del kernel y de procesos.


## Evidencia (output, capturas, archivos generados)


## Reto final
- [ ] Resuelto
- Notas sobre cómo lo resolví:

## Dudas / cosas para repasar después


