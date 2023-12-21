
## Instalación

### Instalación interactiva
```bash
npm init @eslint/config
```
Nos instala eslint y nos crea un fichero de configuración
![[Pasted image 20231219105252.png]]

nos pregunta para qué vamos a querer el linter

![[Pasted image 20231219105328.png]]

estas son un ejemplo de opciones de configuración que vamos a usar:
![[Pasted image 20231219105823.png]]

indicamos que usaremos npm
![[Pasted image 20231219105906.png]]

### Instalación manual
```bash
npm install -D eslint
```
Copiamos el fichero de configuración de eslint de otro proyecto

vemos que nos ha creado una carpeta node_modules donde nos ha metido las dependencias de eslint

![[Pasted image 20231219110449.png]]
en el node_modules nos inserta todas las dependencias que necesita 

ahora necesitamos instalarlo en el sistema por lo que vamos a extensiones, vamos a Eslint y lo instalamos

le damos al icono de abajo a la izquierda, buscamos ESLint y lo instalamos para que se aplique
![[Pasted image 20231219110929.png]]



## Integración con  [[prettier]]

para que prettier y eslint trabajen bien juntos

(nos instalará otras dependencia más y al llevar -D indicamos que es una dependencia de desarrollo)
```bash
npm install -D eslint-config-prettier
```

Añadir en  el fichero *.eslintrc.json*:
```js
{
  "extends": [
    "some-other-config-you-use",
    "prettier"
  ]
}
```
nosotros, como ya tenemos esa parte automáticamente en el código vamos a hacer unos cambios 

```js
"extends": ["eslint:recommended",

"prettier"

],

"parserOptions": {

"ecmaVersion": "latest",

"sourceType": "module"

},
```
## Configurar en [[Plugins en Visual Studio Code|Visual Studio Code]]