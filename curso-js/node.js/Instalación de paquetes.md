
## Objetivos

- [ ] Instalar librerías para un proyecto base 
- [ ] Buscar librerías en el repositorio de npm


## Instalación de paquetes

**Producción:**
enriquecen nuestro sitio web.
Como un mapa de Google, un formulario de contacto, un chat de Whatsapp...

```bash
npm install --save-prod <nombre paquete>
# o más fácil
npm i <nombre paquete>
(sino ponemos nada indicamos que es de producción)```

**Desarrollo:**
enriquecen el código, cambia el código, que avisen de errores de código, hacen minify del código, comprime imágenes sin pérdida de calidad, etc

```bash
npm install --save-dev <nombre paquete>
# o más fácil
npm i -D <nombre paquete>
(con -D indicamos que es de desarrollo)``` 

Cuando instalemos un paquete tenemos que indicar si es de desarrollo o producción;
si es una dependencia de desarrollo no la subiremos al servidor ni a la página posterior, si es de producción si que necesitamos que esté esa dependencia en el servidor.

Sino le decimos nada va a ser una dependencia de producción.

## Borrar paquetes

```bash
npm remove <nombre-paquete>
```


## Ficheros de dependencias

### package.json
Guardamos listado de dependencias de nuestro proyecto.  Usa [[Versionado semántico]].

### package-lock-json
Asegura la replica exacta de nuestra instalación. Versiones exactas.


## Repositorio npm

Ver https://www.npmjs.com/


