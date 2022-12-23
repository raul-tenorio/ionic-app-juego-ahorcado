# JUEGO DEL AHORCADO

![imagen](https://user-images.githubusercontent.com/74626123/209367230-4f8500f0-b851-46ba-8c07-54486a82f23a.jpg)

## Lógica del juego
En el momento que seleccionamos una letra del desplegable y pulsamos sobre el botón seleccionar letra, estamos llamando al método compruebaLetra() y es aquí donde realizamos las siguientes comprobaciones:

• Seleccionar letra:
  • Comprobar que se haya seleccionado una letra.
  • Comprobar si la letra está en la palabra secreta:
  • SI:
    • Recorremos la palabra secreta y reemplazamos los huecos por la letra seleccionada tantas veces como corresponda.
    • Sumamos puntos.
    • Lanzamos mensaje toast de acierto.
    • Comprobamos si quedan huecos en la palabra secreta:
      • SI: Seguimos jugando.
      • NO: @Ganador solución indirecta.
  • NO:
  • Restamos puntos.
  • Restamos vida.
  • Comprobamos si quedan vidas:
    • SI: Seguimos jugando.
    • NO: Fin del juego.
  • Lanzamos mensaje toast de error.
  • Cambiamos imagen añadiendo un palito al muñeco del ahorcado.
• Resolver directamente:
  • Solución directa:
    • SI: Sumamos más puntos que en la solución indirecta.
    • NO: Restamos puntos y seguimos jugando.
