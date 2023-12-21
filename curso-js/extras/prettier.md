[Documentación de  prettier](https://prettier.io/)

herramienta para que nos preformatee el código 

en el momento que lo instalemos, el archivo package.json tendrá otra dependencia más

```bash
npm i -D prettier
```
Crear un  fichero *.prettierrc.json* vacío (con dos llaves):
```bash
echo {}> .prettierrc.json
```


nos crea un fichero así 
![[Pasted image 20231219111444.png]]


Se ha añadido esto en el *package.json*:

```json
  "devDependencies": {
    "prettier": "^2.8.4"
  }
```
Sigue [[Versionado semántico]]

También se crea un package-lock.json con mis dependencias exactas.

instalamos de nuevo la dpendencia en visual estilo code

![[Pasted image 20231219111738.png]]

### Para Integrarlo:
vamos a la ruedecita de configuracion
![[Pasted image 20231219112010.png]]
buscamos arriba default
![[Pasted image 20231219112042.png]]
añadimos en este apartado Default formate -> prettier
![[Pasted image 20231219112102.png]]
volvemos a introducir lo siguiente en el buscador
![[Pasted image 20231219112126.png]]

marcamos esta opción
![[Pasted image 20231219112147.png]]
nos aplicará lo que hemos indicado en la configuración del linter y el prettier 

### Configurar en [[Plugins en Visual Studio Code|Visual Studio Code]]


