# Incidencia de constructores DAM2_6_3_JACP

## 1.-¿Qué es un constructor y para qué lo usamos ?
    Un constructor es una función que se usa para inicializar el contenido de una clase o el contenido
    de las nuevas instancias de la clase.

## 2.-¿Cuantos tipos de constructores nos podemos encontrar en kotlin y diferencias?
    Está el constructor primario que funciona desde la cabecera de la clase, ahí recibe como argumentos
    los datos que necesita para inicializarse.
    El constructor secundario, parecido al primario pero esta vez no está en la cabecera, está dentro de
    la clase llamandolo antes como "constructor()" y dentro de los parentesis se pondría los argumentos.
    La diferencia entre estos a parte del lugar donde pasar los argumentos es que el constructor secundario
    delega del constructor primario.

## 3.-¿De qué manera afecta y como hay que usar los constructores en la herencia?
    Si la superclase tiene constructor hay que inicializarlo  pasando los parámetros en la sintaxis de herencia.
    Si es mediante un constructor secundario debemos de llamarlo junto a la palabra "super" para que la llame.    
