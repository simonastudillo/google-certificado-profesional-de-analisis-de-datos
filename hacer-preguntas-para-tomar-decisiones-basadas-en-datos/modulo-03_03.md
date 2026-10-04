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

---

## Funciones 101
- ​Las fórmulas son una excelente manera de ser ​más eficiente al usar hojas de cálculo, ​especialmente cuando agregas métodos abreviados, ​como copiar y pegar, a la mezcla.
- ​A medida que avances como analista de datos, ​lo más probable es que aprendas ​más atajos que te ayudarán en tu proceso.
- ​Pero ahora es el momento de pasar a las funciones.
- ​Si bien están estrechamente relacionadas con las fórmulas, ​no son exactamente lo mismo.
- ​Al final de este vídeo, ​comprenderás la diferencia y ​sabrás cuándo usar ambos.
- ​En el mundo de las hojas de cálculo, ​una función es un comando preestablecido que ​ejecuta automáticamente un proceso ​o tarea específicos utilizando los datos.
- ​Es posible que recuerde algunos de los métodos abreviados ​que aprendimos y que se pueden usar con las fórmulas.

- ​Piensa en las funciones como los atajos más útiles.
- ​La buena noticia es que muchas ​funciones de hojas de cálculo tienen nombres ​que indican lo que hacen.
- ​Hay un montón de funciones por ahí.
- A ​medida que continúe trabajando con hojas de cálculo, ​descubrirá que usa algunas con frecuencia ​y otras, muy poco o nada.
- ​Por ahora, ​veamos algunas de las funciones que podemos ​aplicar a nuestros datos de ventas del vídeo anterior.
- ​Empezaremos con las ventas totales.
- ​Usemos la función SUM para esto en la celda F2.

- ​Los primeros pasos son bastante ​similares a los que hicimos en el último vídeo.
- ​En primer lugar, seleccionaremos la celda ​en la que queremos que aparezca el cálculo.
- ​Escriba equals y, a continuación, añada la palabra SUM como nuestra función.
- ​Una de las mejores cosas de las funciones ​es que no siempre necesitan operadores, ​como un signo más para sumar.
- ​En este caso, después de los paréntesis abiertos, ​puede continuar y seleccionar ​el rango de celdas que va a agregar.
- Si ​aparecen dos puntos entre las referencias de las celdas, ​se indica que está utilizando un rango.
- ​En este caso, el rango incluye celdas de la misma fila.

- ​Tras los paréntesis cerrados, pulsamos Entrar.
- ​Justo así, aparece nuestro número total de ventas.
- ​Al igual que la fórmula que usamos antes, ​las funciones se pueden copiar y ​pegar en otras celdas de la misma columna.
- ​Pero deshagamos ese paso para que puedas ​ver otra forma de copiar una función o fórmula.
- ​Las hojas de cálculo tienen algo llamado identificador de relleno.
- ​Es un pequeño recuadro que aparece en ​la esquina inferior derecha al hacer clic en una celda.
- ​Si coloca el cursor sobre el cuadro, ​puede arrastrar el controlador de relleno hasta ​los demás cuadros de la misma fila o columna.

- ​Cualquier fórmula o función de esa celda ​se agregará automáticamente a las celdas que llene y, además, ​el controlador de relleno actualizará la fórmula para que ​las referencias a las celdas coincidan con ​la fila de las columnas de las celdas que complete.
- ​Esto significa que la fórmula se calcula ​en función de los datos de cada fila o columna independiente.
- ​Rellenar no funcionará en todas las situaciones, ​pero sigue siendo un truco bastante bueno.
- ​Ahora vamos a encontrar la venta promedio de ​cada mes usando la función PROMEDIO.
- ​Las diferentes funciones realizan cálculos diferentes, ​pero funcionan de la misma manera.
- ​Ten en cuenta que no todos los cálculos con los ​que te encontrarás tienen su propia función para ayudarte.
- ​Por ejemplo, para encontrar ​el cambio porcentual en las ventas entre junio y julio, ​usarás la misma fórmula que usaste en un vídeo anterior.

- ​Supongamos que se le pide que busque ​las ventas mensuales más bajas en este conjunto de datos.
- ​Hay una función para eso.
- ​Se llama función MIN, ​que significa mínimo.
- ​Así es como funciona.
- ​Supongamos que necesitas encontrar las ventas mensuales más bajas ​de todo el conjunto.
- ​Todo lo que tiene que hacer es configurar la función.
- ​Después del paréntesis abierto, ​seleccione los valores de las tres filas.

- ​Esta información puede ser importante ​para las partes interesadas.
- ​Añadamos color a la celda con ese valor ​en su conjunto de datos para que destaque.
- ​En este caso, haga clic en la celda D2 y luego en el icono de color de relleno, ​que parece una lata de pintura, ​luego elija un color.
- ​Usaré el amarillo aquí.
- ​Puedes seguir los mismos pasos para conseguir ​las ventas más altas utilizando la ​función MAX, espéralo.
- ​Parece que tenemos un mensaje de error.
- ​¿Qué puede estar mal? 
- ​Se nos olvidó incluir ​un paréntesis abierto después de la función.
- ​No te preocupes, es una solución rápida.
- ​Sin embargo, este es un buen recordatorio para comprobar continuamente ​el formato de las funciones y ​fórmulas a medida que las utiliza.
- Más ​adelante, aprenderemos más sobre los mensajes de error y cómo trabajar con ellos.
- ​Así está mejor.
- Ahora ​también agregaremos color a la celda con las ventas más altas.
- ​Esta es solo una forma de resaltar los datos clave.

- ​Descubrirás algunos otros más adelante.
- ​Ya has visto algunas formas de ​añadir y organizar datos en una hoja de cálculo.
- ​También ha visto lo poderosas que ​pueden ser las fórmulas y funciones cuando se aplican a datos del mundo real.
- ​Como analista de datos, ​esto es solo el principio de ​tu experiencia con las hojas de cálculo.
- ​Pronto descubrirás ​cuánto más pueden ofrecer las hojas de cálculo.
- ​Mientras tanto, puedes ​practicar algunas de estas fórmulas ​, funciones y otros procesos por tu cuenta.
- ​Puede ser divertido experimentar ​y ver todo lo que pueden hacer las hojas de cálculo.

- ​Pronto pasarás de las ​hojas de cálculo al pensamiento estructurado.
- ​Las piezas de análisis de datos están empezando a encajar.
- Están ​por venir cosas interesantes.
- Así que quédate aquí.
- [Excel resuelto](./resources/modulo-03/Monthly-Sales---Functions-101-resuelto.xlsx)

---

## Referencia rápida: Funciones en hojas de cálculo
- Como recordatorio rápido, una función es un comando preestablecido que realiza automáticamente un proceso o tarea específicos utilizando los Datos de una hoja de cálculo.
- Las Funciones ofrecen a los analistas de datos la posibilidad de realizar cálculos, que pueden ser desde simples operaciones aritméticas hasta ecuaciones complejas.
- Utilice esta lectura como ayuda para realizar un seguimiento de algunas de las opciones más útiles.

- Funciones
   - Lo básico
      - Al igual que las fórmulas, comience todas sus funciones con un signo igual; por ejemplo =SUM.
      - El signo igual indica a la hoja de cálculo que lo que sigue es parte de una función, no sólo una palabra o un número en una celda.
      - Después de introducir el signo igual, la mayoría de las aplicaciones de hojas de cálculo mostrarán un menú de autocompletar que enumera las funciones válidas, los nombres y las cadenas de texto.
      - Es una forma estupenda de crear y editar funciones evitando errores de escritura y de sintaxis.
      - Una forma divertida de aprender nuevas funciones es simplemente tecleando un signo igual y una sola letra del alfabeto.
      - Elija una de las opciones que aparecen y aprenda lo que hace esa función.

   - Diferencia entre fórmulas y funciones
      - Una fórmula es un conjunto de instrucciones utilizadas para realizar un cálculo utilizando los datos de una hoja de cálculo.
      - Una función es un comando preestablecido que realiza automáticamente un proceso o tarea específicos utilizando los Datos de una hoja de cálculo.

   - Funciones populares
      - Mucha gente no se da cuenta de que los accesos directos del teclado como cortar, guardar y buscar son en realidad funciones.
      - Estas funciones están integradas en una aplicación y son increíbles ahorradoras de tiempo.
      - El uso de accesos directos le permite hacer más con menos esfuerzo.
      - Pueden hacerle más eficiente y productivo porque no está constantemente buscando el ratón y navegando por los menús.

   - Autorrelleno
      - La esquina inferior derecha de cada Célula tiene un Controlador de relleno.
      - Es un pequeño cuadrado verde en Microsoft Excel y un pequeño círculo azul en Google Sheets.
      - Clic en el Controlador de relleno de una celda y arrástrelo columna abajo para autorellenar otras celdas de la columna con la misma fórmula o función utilizada en esa celda.
      - Clic en el Controlador de relleno de una celda y arrástrelo a través de una fila para autorellenar otras celdas de la fila con la misma fórmula o función utilizada en esa celda.

   - Referencias relativas, absolutas y mixtas
      - Las referencias relativas (celdas referenciadas sin el signo de dólar, como A2) cambiarán cuando copie y pegue la función en una celda diferente.
      - Con las referencias relativas, la ubicación de la celda que contiene la función determina las celdas utilizadas por la función. 
      - Las referencias absolutas (celdas totalmente referenciadas con un signo de dólar, como $A$2) no cambiarán cuando copie y pegue la función en una celda diferente.
      - Con las referencias absolutas, las celdas referenciadas siempre serán las mismas.
      - Las referencias mixtas (celdas parcialmente referenciadas con un signo de dólar, como $A2 o A$2) cambiarán cuando copie y pegue la función en una celda diferente.
      - Con las referencias mixtas, la ubicación de la celda que contiene la función determina las celdas utilizadas por la función, pero sólo la fila o la columna es relativa (no ambas).   
      - En las hojas de cálculo, puede pulsar la tecla F4 para alternar entre referencias relativas, absolutas y mixtas en una función.
      - Clic en la celda que contiene la función, resalte las celdas referenciadas en la barra de fórmulas y, a continuación, pulse F4 para alternar y seleccionar referencias relativas, absolutas o mixtas.

   - Rangos de datos
      - Cuando hace clic en una celda que contiene una función, los rangos de datos coloreados en la barra de fórmulas indican qué celdas se están utilizando en la hoja de cálculo.
      - Hay diferentes colores para cada rango Único en una función.
      - Los rangos de datos coloreados le ayudan a no perderse en funciones complejas.
      - En las hojas de cálculo, puede pulsar la tecla F2 para resaltar el rango de datos utilizado por una función.
      - Haga clic en la celda que contiene la función, resalte el rango de datos utilizado por la función en la barra de fórmulas y, a continuación, pulse F2.
      - La hoja de cálculo irá a las celdas especificadas por el rango y las resaltará.

   - Rangos de datos evaluados para una condición
      - COUNTIF es un ejemplo de una función que devuelve un valor basado en una condición para la que se evalúa el rango de datos.
      - La función cuenta el número de celdas que cumplen los criterios.
      - Por ejemplo, en una hoja de cálculo de gastos, utilice COUNTIF para contar el número de celdas que contienen un reembolso por "billete de avión"
   
   - Para más Información, consulte:
      - [La página de soporte de Microsoft para COUNTIF ](https://support.microsoft.com/en-us/office/countif-function-e0de10c6-f885-4e71-abb4-1f464816df34)
      - D[ocumentación del Centro de Ayuda de Google para COUNTIF](https://support.google.com/docs/answer/3093480?hl=en) donde puede copiar una hoja con [ejemplos de COUNTIF](https://docs.google.com/spreadsheets/d/1PYoKCYZAkWSaMBsiTyvxZzCCt2WQ-QKOC763RWHMB7c/template/preview)

- Puntos clave
   - Hay muchas más funciones que pueden ayudarle a sacar el máximo partido de sus datos.
   - Esto es sólo el principio.
   - Puede seguir aprendiendo a utilizar funciones que le ayuden a resolver problemas complejos con eficacia y precisión a lo largo de toda su carrera.

- Accesos directos del teclado
   - Puede guardar estas funciones para consultarlas en el futuro.
   - No dude en descargarse una versión en .pdf de las funciones a continuación:
      - [DAC2 Keyboard functions 1.pdf](./resources/modulo-03/DAC2 Keyboard functions 1.pdf)
      - [DAC2 Keyboard functions 2.pdf](./resources/modulo-03/DAC2 Keyboard functions 2.pdf)