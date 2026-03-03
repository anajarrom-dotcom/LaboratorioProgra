# 1.Identificacion de tareas repetitivas

## ¿Qué partes del código pueden convertirse en métodos?
Lo que puedo convertir en método es casi todo lo que esta dentro del while, como donde se muestra el menú, agregar un  estudiante y calcular promedio.

## ¿Qué bloques de código se repiten?
Uno de los bloques que se repite es la validación de lista para mostrar estudiante, calcular promedio o mostrar el mejor estudiante se revisa si la lista esta vacia.

## ¿Qué responsabilidades pueden separarse?
Una principal es el mostrar el menú, solo mostrar las opciones al usuario, leer opción, agregar estudiante, mostrar estudiante. Al separarlas logramos que el código este mas ordenado y fácil de entender y permite modificar un método sin tocar los demás.

# 2. Variables Locales vs Globales

## ¿Qué variables deberían declararse como globales?
En mi programa solo agrege una variable global además de las que ya estaban, que fue Scanner por que es usado para leer entradas del usuario en varios métodos.

## ¿Cuáles deberían ser locales dentro de un método?
Las variables locales deben ser con sentido al método que estemos realizando ya que el tiempo de estas es solo mientras se ejecuta el método.


# 3. Validaciones y manejo de excepciones

## Qué errores podrían ocurrir?
En el código original había problemas que podían hacer que el programa se cierre.
Como por ejemplo: hola o cualquier cosa en vez de números daba error y se cerraba.
Qué validaciones implementaron.
Validacion de numero para el menú con try-catch esto evita que el programa se cierre si escribe texto y permite que el usuario vuelva a intentarlo.
Por qué son importantes.
Para evitar que el programa se cierre inesperadamente.
Garantizar que los dato sean correctos.

# 4. Preguntas de reflexión

## ¿Qué ventajas tiene dividir el código en métodos?
Tenemos cada método muy bien organizado entendible en el código lo que permite reutilizar segmentos de código en cualquier otro programa, podemos corregir un método sin afectar los otros y al tener cada método separado tenes muy claro que realiza cada parte.










