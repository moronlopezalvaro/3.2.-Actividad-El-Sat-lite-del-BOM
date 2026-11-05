## 1. El objeto window se considera el objeto global del entorno del navegador (BOM). Explica la diferencia entre este y un objeto nativo global del lenguaje JavaScript como Math o JSON. ¿Por qué no hace falta escribir window.Math?

```window``` es el objeto de más alto nivel en el entorno del cliente que representa la ventana del navegador y actúa como el ámbito global de toda ejecución JavaScript en el navegador. ```Math``` y ```JSON``` son objetos nativos del lenguaje JavaScript que proporcionan funcionalidades para operaciones matemáticas y el manejo de datos en formato JSON, respectivamente. No hace falta escribir ```window.Math``` porque ```Math``` es un objeto nativo del lenguaje JavaScript que proporciona funcionalidades para operaciones matemáticas.

## 2. Identifica a qué categoría (BOM u objeto nativo de JS) pertenecen las siguientes instrucciones que utilizaremos en la práctica:

- window.open()
- parseFloat()
- Math.floor()
- navigator.userAgent