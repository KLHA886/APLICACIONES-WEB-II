Reflexión - Calculadora en GO ¿Cuántas líneas tiene tu función principal al final del taller? Cuéntalas con cuidado. Mi función principal tiene aproximadamente 75 líneas de código. Esto ocurre ya que toda la lógica del programa está concentrada en una sola función.

Si tuvieras que agregar 5 operaciones más (raíz cuadrada, logaritmo, seno, coseno, módulo), ¿qué tan grande se haría tu principal? ¿Sería fácil de leer para alguien que vea el código por primera vez? La función principal crecería bastante, aproximadamente entre unas 130 o 150 líneas. No seria facil de leer porque el switch tendria muchas mas cosas y el codigo se volveria mas largo y dificil de entender.

Note que el código para 'pedir un número al usuario' o 'imprimir el resultado' se repite varias veces. ¿No sería mejor escribirlo una sola vez y reutilizarlo en muchos lugares? En mi código se repite el proceso de pedir datos al usuario y manejar resulrado. Seria mejor crear funciones para evitar repetir código, mejorar el orden y facilitar posibles cambios.

Tu historial es una cadena variable gigante. ¿Qué pasaría si quisieras: ordenarlo alfabéticamente, eliminar la operación número 2, o contar cuántas veces se usó la operación de suma? Seria dificil de manejar porque es solo una cuerda. No se podrá modificar fácilmente. Lo ideal sería usar un arreglo dinámico.

Después de este taller, ¿qué fue lo más difícil de Go para ti? ¿Y lo más interesante? Lo mas dificil fue manejar los tipos de datos y conversiones. Los mas interesante fue usar switch y for para resolver las operaciones.