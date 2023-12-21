
tenemos que darle una base/un promt

es decir, tenemos que indicar como queremos que se comporte


añadimos los ejercicios/requerimientos de esta forma

<requerimientos>

</requerimientos>

![[Pasted image 20231221113840.png]]






Esto es lo que nos muestra
```javascript 

// 1. Guarda el peso y la altura de Pedro y Lucas en variables.
let pesoPedroTest1 = 78;
let alturaPedroTest1 = 1.69;

let pesoLucasTest1 = 92;
let alturaLucasTest1 = 1.95;

let pesoPedroTest2 = 95;
let alturaPedroTest2 = 1.88;

let pesoLucasTest2 = 85;
let alturaLucasTest2 = 1.76;

// 2. Calcula el IMC de ambos.
let imcPedroTest1 = pesoPedroTest1 / (alturaPedroTest1 * alturaPedroTest1);
let imcLucasTest1 = pesoLucasTest1 / (alturaLucasTest1 * alturaLucasTest1);

let imcPedroTest2 = pesoPedroTest2 / (alturaPedroTest2 * alturaPedroTest2);
let imcLucasTest2 = pesoLucasTest2 / (alturaLucasTest2 * alturaLucasTest2);

// 3. Guarda en una variable booleana llamada PedroMayorIMC el resultado.
let PedroMayorIMCTest1 = imcPedroTest1 > imcLucasTest1;
let PedroMayorIMCTest2 = imcPedroTest2 > imcLucasTest2;

// Imprimir los resultados en la consola para verificar
console.log("Test 1 - ¿Pedro tiene mayor IMC que Lucas?:", PedroMayorIMCTest1);
console.log("Test 2 - ¿Pedro tiene mayor IMC que Lucas?:", PedroMayorIMCTest2);

```

