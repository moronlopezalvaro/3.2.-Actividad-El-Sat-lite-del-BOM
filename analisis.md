## 1. El objeto window se considera el objeto global del entorno del navegador (BOM). Explica la diferencia entre este y un objeto nativo global del lenguaje JavaScript como Math o JSON. ¿Por qué no hace falta escribir window.Math?

```window``` es el objeto de más alto nivel en el entorno del cliente que representa la ventana del navegador y actúa como el ámbito global de toda ejecución JavaScript en el navegador. ```Math``` y ```JSON``` son objetos nativos del lenguaje JavaScript que proporcionan funcionalidades para operaciones matemáticas y el manejo de datos en formato JSON, respectivamente. No hace falta escribir ```window.Math``` porque, en el navegador, ```window``` es el objeto global. Todos los objetos globales, incluidos los nativos como ```Math``` o ```JSON```, son propiedades suyas.

## 2. Identifica a qué categoría (BOM u objeto nativo de JS) pertenecen las siguientes instrucciones que utilizaremos en la práctica:

- window.open() -> BOM, es un método del objeto ```window```. Abre una nueva ventana del navegador, algo que solo existe en el entorno del navegador.
- parseFloat() -> Nativo de JS, es una función global del lenguaje (ECMAScript) que convierte un texto en un número decimal. Funciona igual en cualquier entorno.
- Math.floor() -> Nativo de JS, es un método del objeto nativo ```Math```. Redondea hacia abajo y no depende del navegador.
- navigator.userAgent -> BOM, es una propiedad del objeto ```navigator```, que da información sobre el navegador y el sistema operativo del cliente.