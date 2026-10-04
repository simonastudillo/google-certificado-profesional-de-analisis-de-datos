# Funciones en hojas de cálculo

## Paso a paso: Funciones 101
- Esta lectura resume los pasos que el instructor realiza en el siguiente video, Funciones 101.
- En el video, el instructor demuestra cómo utilizar las funciones de la hoja de cálculo para realizar cálculos. 
- Mantenga esta guía paso a paso abierta mientras ve el video. Puede servir como una referencia útil si necesita contexto adicional o clarificación mientras sigue los pasos del video.
- No se trata de una actividad puntuable, pero puedes completar estos pasos para practicar las habilidades demostradas en el vídeo.

- Qué necesitas
   - Si deseas acceder a la otra hoja de cálculo que el instructor utiliza en este vídeo, haz clic en el enlace al Conjunto de datos para crear una copia.
   - Si no tienes una cuenta de Google, puedes descargar los datos directamente de los archivos adjuntos que aparecen a continuación.
   - [Ejemplo](./resources/modulo-03/Monthly-Sales---Functions-101.xlsx)

- Ejemplo: Comenzar con el total de ventas
   - Utilice la función SUM para calcular el valor total de un rango de celdas.
   - Abra la hoja de cálculo Ventas mensuales - Funciones 101.
   - Selecciona la celda F2.
   - Introduce =SUM(B2:E2) y pulsa Intro para calcular las ventas totales para este periodo de tiempo.
   - Nota: Los dos puntos (:) entre B2 y E2 en la fórmula indican que estás especificando un Rango. En este caso, es el rango de celdas de B2 a E2. La función SUM sumará los valores de estas celdas para calcular el total de ventas del periodo especificado.

- Ejemplo: Texto publicitario (Copy) utilizando el Controlador de relleno
   - Utilice el controlador de relleno para copiar rápidamente una función en varias celdas. 
   - En la hoja de cálculo Ventas Mensuales , selecciona la celda F2 y haz clic y mantén pulsado el controlador de relleno con el cursor. 			 Nota: El instructor se refiere al controlador de relleno como una "cajita", pero en las nuevas versiones o interfaces, es un círculo. 
   - Arrastre el controlador de relleno para incluir las celdas F3 y F4 y suelte el controlador de relleno.
   - Las ventas totales de 2018 y 2019 están en las celdas de referencia F3 y F4, respectivamente. Esto sucede porque al arrastrar el controlador de relleno se actualiza automáticamente la fórmula para tener en cuenta el cambio de fila, lo que garantiza que el cálculo sigue siendo preciso para cada fila que se rellena.
   - Clic en la celda F3 para mostrar su fórmula en la barra de fórmulas. Esta es una barra de herramientas que muestra la información contenida en una Célula. Te permite inspeccionar la fórmula y asegurarte de que la fórmula se actualiza cuando se copia de la celda F2 a la celda F3.

- Ejemplo: Hallar la venta media
   - Utiliza la función AVERAGE para hallar la venta media de cada año.
   - En la hoja de cálculo Ventas Mensuales, selecciona la celda G2.
   - Introduce =AVERAGE(B2:E2) y pulsa Intro para calcular la venta media de 2017.
   - Utiliza el Controlador de relleno o copia y pega la función de la celda G2 a las celdas G3 y G4 para calcular las ventas medias de 2018 y 2019, respectivamente.

- Ejemplo: Utilizar fórmulas para casos especiales
   - Algunos cálculos pueden no tener funciones dedicadas. Por ejemplo, para calcular el cambio porcentual de junio a julio, tendrás que utilizar la fórmula de cambio porcentual que utilizaste anteriormente en el curso.
   - En la hoja de cálculo Ventas mensuales, selecciona la celda H2 e introduce =(E2-D2)/D2. Pulsa Intro para calcular el cambio porcentual de junio a julio de 2017.
   - Copia la Función de la celda H2 y pégala en las celdas H3 y H4 para calcular el cambio porcentual de junio a julio de 2018 y 2019, respectivamente. 
   - Selecciona las celdas de referencia H2, H3 y H4 y pulsa el botón de porcentaje (%) para mostrar los cambios en porcentajes.

- Ejemplo: Encontrar las ventas más bajas y más altas
   - Para encontrar las ventas mensuales más bajas (MIN function):
   - En la hoja de cálculo Ventas mensuales, seleccione la celda I1 e introduzca Lowest Monthly Sales.
   - Selecciona la celda I2 e introduce =MIN( , luego usa el cursor para seleccionar los valores de las tres filas, B2:E4, y luego introduce  )  para cerrar el paréntesis. Para seleccionar un bloque de celdas:
      - a. Clic y mantén el cursor en la celda B2.
      - b. Sin soltar el cursor, arrástralo por todos los valores que quieras incluir en el cálculo (en este caso, de B2 a E4).
      - c. Suelta el cursor para seleccionar todos los valores e introduce  `)`.
   - La hoja de cálculo rellenará automáticamente las referencias de celda.
   - Puede que se trate de información importante para las partes interesadas, así que rellena la celda con un color para que destaque:
      - a. Selecciona la celda D2.
      - b. En la barra de herramientas, elige el icono del cubo de pintura.
      - c. Selecciona un color de tu elección de la paleta de colores que aparece. Ese color rellenará la Célula D2.
   - Para hallar las ventas mensuales más altas (FunciónMAX ):
   - Selecciona la celda J1 e introduce Highest Monthly Sales. 
   - Selecciona la celda J2 e introduce =MAX(, luego utiliza el cursor para seleccionar los valores de las tres filas, B2:E4, y a continuación introduce  )  para cerrar el paréntesis.
   - Esto puede ser información importante para tus partes interesadas, así que selecciona la celda E4 y rellénala con un color de tu elección para que destaque.
      - a. Selecciona la celda E4.
      - b. En la barra de herramientas, elige el icono del cubo de pintura.
      - c. Selecciona un color de tu elección de la paleta de colores que aparece. Ese color rellenará la celda E4.

- Ejemplo: Solucionar errores
   - Cuando encuentres errores, asegúrate de solucionar el formato de tus funciones y fórmulas en la barra de fórmulas.