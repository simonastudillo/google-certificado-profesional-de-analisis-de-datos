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

---

## Actividad práctica: Crear una tabla de datos personalizada
- Resumen de la actividad
   - En esta actividad, utilizará una hoja de cálculo para construir una tabla de datos personalizada y analizar sus datos con funciones.
   - Para empezar, suponga que es un analista de datos que trabaja para una agencia de contratación.
   - Esta agencia de contratación ayuda a todo tipo de empresas a encontrar personas cualificadas para cubrir puestos vacantes de analista de datos.
   - La agencia ha recopilado datos sobre las solicitudes de empleo para las oportunidades publicadas en su sitio web en el transcurso de un año. 

- Escenario
   - Revise el siguiente escenario.
   - A continuación, complete las instrucciones paso a paso.
   - La Agencia ha pedido a su Equipo que optimice su proceso de aplicación en línea.
   - Su tarea consiste en resumir los datos de la solicitud de empleo de la agencia.
   - En concreto, quiere responder a las siguientes preguntas: 
      - ¿Cuál fue el número total de aplicaciones recibidas cada mes?
      - ¿Cuántas solicitudes se recibieron?
      - ¿En qué meses se recibieron el menor y el mayor número de solicitudes? 
      - ¿Cuál fue el número medio de aplicaciones recibidas al mes?
   - Para ello, trabajará con una hoja de cálculo.
   - Utilizará funciones de la hoja de cálculo para hacer cálculos basados en sus Datos y creará una tabla de datos personalizada para resumir sus resultados. 
   - Cuando termine esta actividad, será capaz de importar un archivo de hoja de cálculo, ordenar datos, crear una tabla de datos personalizada y utilizar funciones de hoja de cálculo para trabajar con sus datos.
   - Las hojas de cálculo son una herramienta esencial para todo Analista de datos.
   - Utilizar hojas de cálculo para organizar y analizar datos es una habilidad importante que seguirá desarrollando a lo largo de su carrera.  

- Instrucciones paso a paso
   - Siga las instrucciones para completar cada paso de la actividad.
   - A continuación, responda a las preguntas al final de la actividad antes de pasar al siguiente punto del curso.

1. Acceder a la hoja de cálculo
- Para utilizar la hoja de cálculo para este tema del curso, seleccione el enlace que aparece más abajo y, a continuación, seleccione el botón "Utilizar plantilla" para abrir su propia versión de la hoja de cálculo.  
- [Plantilla](./resources/modulo-03/Untitled-spreadsheet.xlsx)

2. Comprender los datos
- Los datos de la agencia contienen información sobre todas las solicitudes de empleo de análisis de datos recibidas.
- Los datos incluyen los siguientes encabezados de columna: ID del solicitante, Fecha, Título del puesto, Lugar del puesto, Contratado y Solicitud fácil.
- A continuación encontrará una descripción de cada encabezado de columna y valores de muestra.

| Nombre de la columna | Descripción de la columna | Datos de Muestra |
| -------------------- | ------------------------- | ---------------- |
| ID del solicitante   | Identificador único de los solicitantes | 11578773 |
| Fecha                | Fecha y hora de recepción de cada solicitud | 1/1/2023 0:01:00 |
| Puesto               | El puesto de Analítica de datos solicitado  | ANALISTA DE DATOS FARMACÉUTICOS |
| Ubicación del puesto | Donde se encuentra el puesto de trabajo     | Lima, Perú                      |
| Contratado           | Indica si un candidato fue contratado       | TRUE                            |
| Solicitud fácil      | TRUE si la solicitud fue enviada directamente en la página web de la agencia; FALSE si la solicitud fue descargada y enviada por correo electrónico  | TRUE  |

3. Ordenación de los datos
- Dado que desea responder a preguntas basadas en un marco temporal específico (en este caso, las solicitudes recibidas por mes en 2023), comience ordenando los datos por fecha.
- Clasificar implica disponer los datos en un orden significativo para facilitar su comprensión, análisis y visualización.
- Tener en cuenta el orden en que se recibió cada solicitud puede ayudarle a descubrir tendencias en las solicitudes de empleo de análisis de datos.

   1. En primer lugar, cambie el nombre de su hoja de cálculo. Seleccione Hoja de cálculo sin título e introduzca un nuevo nombre. Utilice data_analyst_jobs_2023 o un nombre similar que describa claramente los datos que contiene su hoja de cálculo. 
   2. Cuando trabaje en una hoja de cálculo, puede tener varias hojas abiertas. Actualmente, su hoja de cálculo contiene una hoja denominada 2023_data_analyst_job. Cambie el nombre de esta hoja seleccionando la pestaña de la hoja y eligiendo Cambiar nombre en el menú. A continuación, introduzca los datos brutos. 
   3. Haga más anchas las columnas Título del puesto (C) y Ubicación del puesto (D) arrastrando el límite derecho de los títulos de las columnas.
   4. Seleccione todos los datos de la hoja de cálculo seleccionando la celda en la que se cruzan las filas y las columnas. 
   5. En la barra de menús, seleccione Datos > Rango de ordenación > Opciones avanzadas de ordenación por rango.
   6. En la ventana emergente, seleccione la casilla Los datos tienen encabezado de fila. 
   7. En el desplegable Ordenar por, seleccione la Fecha de cabecera. A continuación, seleccione A a Z para ordenar en orden ascendente. 
   8. Por último, seleccione Ordenar. 
- Su hoja de cálculo muestra ahora las solicitudes de empleo recibidas por orden cronológico.

4. Crear una tabla de datos personalizada
- Ahora que ha clasificado sus datos, está listo para crear una tabla de datos personalizada que le ayude a responder a cada una de sus preguntas.
- Su tabla resumirá claramente los datos.
- Además, si quiere compartir sus resultados, su tabla estará bien organizada y será fácil de entender.

- Cuente el número de solicitudes recibidas cada mes
   - En primer lugar, utilice las funciones de la hoja de cálculo para ayudarle a encontrar el número total de solicitudes recibidas en cada mes.
   1. Para empezar, seleccione el icono Añadir hoja (el signo más) en la barra de menús para añadir una nueva hoja a su hoja de cálculo. Creará su tabla de datos en esta hoja
   2. Cambie el nombre de la nueva hoja. Seleccione la pestaña de la hoja y elija Cambiar nombre en el menú. A continuación, introduzca los datos del resumen. 
   3. A continuación, añada encabezados de columna a su tabla. En la celda A1 de su hoja de datos resumidos, introduzca Mes. En la celda B1, introduzca Aplicaciones.
   4. Debajo de la etiqueta Mes , en la celda A2, introduzca Enero. Pulse Intro. 
   5. Ahora, utilice el autorrelleno para añadir el resto de los meses del año. Seleccione de nuevo la celda A2. El tirador de relleno aparecerá en la celda. Seleccione en el tirador de relleno y arrástrelo hacia abajo hasta la celda A13 para autorrellenar todos los meses del año.
   6. A continuación, convierta los valores numéricos de la columna Fecha de la hoja de datos brutos en texto. Seleccione la pestaña de datos brutos para volver a la hoja de datos brutos. En la celda G1, introduzca Mes. 
   7. La función TEXT  convierte un número en texto según un formato especificado. En este caso, enumera en qué mes se recibió una solicitud. Utilice el formato "mmmm" para el nombre completo del mes. En la celda G2, introduzca el siguiente Código (no copie+pegue):
      -  =TEXT(B2,"mmmm") 
      - La primera entrada B2 se refiere a la celda que desea convertir. La segunda entrada ("mmmm") se refiere al formato específico que desea utilizar. Pulse Intro.
      - (Nota: Es muy importante que introduzca manualmente todas las fórmulas y funciones. No debe copiarlas y pegarlas desde la actividad, ya que esto provocará un mensaje de error)
   8. Si aparece un cuadro con la opción de autocompletar la columna, seleccione la marca de verificación o introduzca Ctrl + Intro (Windows) o Cmd + Retorno (Mac). Si no aparece este cuadro, seleccione la celda G2. A continuación, haga doble clic en el tirador de relleno para copiar la función hacia abajo en la columna. Esto rellenará todas las celdas de la columna con el mes correspondiente.
   9. Ahora está listo para totalizar las solicitudes por mes. Podría hacerlo manualmente, filtrando los datos y contando el número de entradas de cada mes, pero esto le llevaría mucho tiempo y sería propenso a errores. En su lugar, utilice la función COUNTIF  . 
   10. La función COUNTIF  cuenta rápidamente cuántos elementos de un rango de celdas cumplen un criterio determinado. En primer lugar, seleccione la pestaña de datos de resumen para volver a su hoja de datos de resumen. A continuación, en la celda B2, introduzca =COUNTIF('raw data'!G:G,A2). La primera entrada 'raw data'!G:G se refiere al Rango donde está contando los datos. El rango se encuentra en su hoja de datos brutos 'raw data'! e incluye todas las entradas de la columna G G:G. Esta columna contiene los datos de los meses. La segunda entrada A2 se refiere al criterio que desea contar. En este caso, es "enero", el valor de la celda A2 de su hoja de datos de resumen. La función calcula cuántas veces aparece enero (el criterio) en la columna Mes (el Rango). 
   11. Pulse Intro. Observará que aparece el valor 2387 en la celda B2. Esto significa que en enero se presentaron 2.387 solicitudes de empleo. 
   12. Seleccione la celda B2. Haga doble clic en el tirador de relleno para copiar la función hacia abajo a través de la celda B13.
   - Ahora su tabla muestra el número total de solicitudes presentadas en cada mes: 

| Mes     | Solicitudes |
| ------- | ----------- |
| Enero   | 2387        |
| Febrero | 2312        |
| Marzo   | 2536        |
| Abril   | 2544        |
| Mayo    | 2954        |
| Junio   | 2990        |
| Julio   | 3138        |
| Agosto  | 2969        |
| Septiembre | 2865     |
| Octubre    | 2751     |
| Noviembre  | 2508     |
| Diciembre  | 2642     |

5. Hallar el número total de aplicaciones recibidas
- Ahora que ha calculado el número de solicitudes recibidas en cada mes, utilice las fórmulas de la hoja de cálculo para calcular el número total de solicitudes recibidas.
- Etiqueta la Célula en la que calcularás el resultado. En la Célula A14, introduzca Total. 
- En la Célula B14, introduzca =SUM(B2:B13). Esta función calcula el número de aplicaciones recibidas de enero a diciembre. 
- La Célula B14 contiene el número total de aplicaciones, 32596.

6. Encontrar los meses con menor y mayor número de aplicaciones recibidas
- Utilice las funciones MIN y MAX para calcular esta información.
- Primero, haga etiquetas para sus resultados. En la Célula A16, introduzca Mín. En la Célula A17, introduzca MAX.
- La función MIN  devuelve el valor mínimo en un rango numérico. En la celda B16, introduzca =MIN(B2:B13). El resultado, 2312, es el menor número de aplicaciones recibidas en cualquier mes de 2023. 
- La función MAX  devuelve el valor máximo en un conjunto de datos numéricos. En la Célula B17, introduzca =MAX(B2:B13). El resultado, 3138, es el mayor número de aplicaciones recibidas en cualquier mes de 2023.

7. Encuentre el número medio de aplicaciones recibidas al mes
- Utilice la función AVERAGE para calcular esta información.
- Primero, haga etiquetas para sus resultados. En la Célula A18, introduzca Avg. 
- La función AVERAGE  devuelve el valor medio en un conjunto de datos numéricos. En la Célula B18, introduzca =AVERAGE(B2:B13). El resultado, 2716,33, es el número medio de aplicaciones mensuales recibidas en 2023.
- Su trabajo ayudará a su Equipo a descubrir tendencias y Patrones importantes en los datos de la Agencia y a generar estadísticas para optimizar el proceso de aplicación. Por ejemplo, como sus hallazgos revelan que febrero fue el mes más lento, la agencia puede dedicar una mayor parte de su presupuesto de publicidad y divulgación a febrero y menos al mes punta de julio. Este es el Impacto estratégico del Análisis de datos. 

8. Explore las opciones de formato
- No dude en explorar las opciones de formato para su tabla de datos mediante negrita, alineación al centro, color de relleno, bordes y mucho más.
- El formato le permite resaltar la información importante y le ayuda a captar la atención de su público.

- [Excel resuelto](./resources/modulo-03/data_analyst_jobs_2023.xlsx)

- Reflexión
   - ¿Cuál de las siguientes funciones cuenta cuántos elementos de un Rango de celdas cumplen un criterio determinado? 
      - [ ] COUNTIF  
      - [ ] TEXT
      - [ ] MAX
      - [ ] SUM
   > La función COUNTIF cuenta rápidamente cuántos elementos de un rango de celdas cumplen un criterio determinado. El uso de funciones para realizar cálculos y analizar datos es una habilidad importante para un analista de datos. En el futuro, seguirá desarrollando esta habilidad a medida que trabaje con conjuntos de datos más complejos. 

   - En esta actividad ha aprendido a analizar Datos utilizando funciones de hoja de cálculo. En el cuadro de texto que aparece a continuación, escriba de 2 a 3 frases (de 40 a 60 palabras) en respuesta a cada una de las siguientes preguntas:
      - ¿Cómo le ayuda el uso de funciones a obtener rápidamente información estadística sobre grandes cantidades de Datos?
      - ¿Cómo le ayuda la creación de una tabla de datos a organizar y comunicar aspectos importantes de sus datos? 
   > Las funciones de las hojas de cálculos ayudan a procesar la información de forma rápida y eficiente, siempre y cuando los datos estén normalizados, para este caso el que más me llamó la atención fue la función COUNTIF, la cual ayudó a contar rápidamente la cantidad de solicitudes por mes, hacer esto de forma manual podría tomar 1 hora o más, además de dejar espacio para el error humano. Crear una nueva hoja con una nueva tabla para resumen ayuda a no modificar la hoja de datos, evitar problemas de mover, eliminar o modificar la información.
   - Comentarios
   ¡Enhorabuena por haber completado esta actividad práctica! En esta actividad, ha importado un conjunto de datos, ha ordenado sus datos, ha creado una tabla de datos y ha utilizado funciones para realizar cálculos y analizar sus datos.  

   Una respuesta eficaz señalaría que las funciones de las hojas de cálculo ayudan a los profesionales de los datos a analizar rápidamente grandes cantidades de datos. También mencionaría que la creación de tablas de datos puede ayudar a resumir y comunicar aspectos importantes de los datos. En las próximas actividades, seguirá explorando las formas en que las funciones de las hojas de cálculo pueden ayudarle a trabajar con conjuntos de datos complejos. 