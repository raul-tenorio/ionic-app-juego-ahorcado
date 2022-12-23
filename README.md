# JUEGO DEL AHORCADO

![imagen](https://user-images.githubusercontent.com/74626123/209367230-4f8500f0-b851-46ba-8c07-54486a82f23a.jpg)

## Lógica del juego
En el momento que seleccionamos una letra del desplegable y pulsamos sobre el botón seleccionar letra, estamos llamando al método compruebaLetra() y es aquí donde realizamos las siguientes comprobaciones: </br>

• Seleccionar letra: </br>
  • Comprobar que se haya seleccionado una letra. </br>
  • Comprobar si la letra está en la palabra secreta: </br>
  • SI: </br>
    • Recorremos la palabra secreta y reemplazamos los huecos por la letra seleccionada tantas veces como corresponda. </br>
    • Sumamos puntos. </br>
    • Lanzamos mensaje toast de acierto. </br>
    • Comprobamos si quedan huecos en la palabra secreta: </br>
      • SI: Seguimos jugando. </br>
      • NO: @Ganador solución indirecta. </br>
  • NO: </br>
  • Restamos puntos. </br>
  • Restamos vida. </br>
  • Comprobamos si quedan vidas: </br>
    • SI: Seguimos jugando. </br>
    • NO: Fin del juego. </br>
  • Lanzamos mensaje toast de error. </br>
  • Cambiamos imagen añadiendo un palito al muñeco del ahorcado. </br>
• Resolver directamente: </br>
  • Solución directa: </br>
    • SI: Sumamos más puntos que en la solución indirecta. </br>
    • NO: Restamos puntos y seguimos jugando. </br>
