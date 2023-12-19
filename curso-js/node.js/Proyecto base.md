
## Objetivos

- [ ] Aprender a crear un nuevo proyecto en node  #entorno 
- [ ] Instalar librerías para un proyecto base  #entorno


## Nuevo proyecto

Le damos a terminal, nueva terminal
![[Pasted image 20231219101331.png]]
![[Pasted image 20231219101342.png]]
Instalaremos todas las dependencias dentro de ese proyecto

En cada proyecto que se realice se instalan las dependencias.

(Usaremos la terminal para instalar las dependencias que nos hagan falta)

Para crear dependencias del proyecto:

```bash
mkdir <carpeta proyecto>
cd <carpeta proyecto>
npm init
# damos varias veces al Enter
```

Crea un fichero package.json **sin dependencias**

le daremos al enter aceptando las opciones (modificaremos las opciones según queramos)

Nos pedirá que confirmemos los cambios
![[Pasted image 20231219101729.png]]

nos crea un archivo con estructura 
![[Pasted image 20231219101807.png]]
[[Definición de Json]]

crearemos nuestras dependencias de desarrollo

y las guardaremos sobre cada proyecto y las veremos reflejadas como archivos json

habrá un objeto que serán dependencias y otro que se llamará dependencias de desarrollo

## Instalación de paquetes

[[eslint]]
[[prettier]]

- Para que nuestro proyecto nos busque errores y nos los señale necesita un lintern
- así que vamos a nmp y buscamos linter javascript

podemos ordenar por distintos metodos segun si queremos el mas optimo, mas popular etc
![[Pasted image 20231219104322.png||400]]



## Fichero de dependencias

Son  *package.json* y *package-lock.json*
