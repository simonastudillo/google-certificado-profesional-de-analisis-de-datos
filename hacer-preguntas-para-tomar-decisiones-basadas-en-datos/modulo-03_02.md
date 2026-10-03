# Fórmulas en hojas de cálculo

## Paso a paso: Fórmulas para el éxito
- Esta lectura esboza los pasos que el instructor realiza en el siguiente vídeo, Fórmulas para el éxito.
- En el vídeo, el instructor explica los fundamentos del uso de fórmulas de hojas de cálculo para realizar cálculos. 
- Mantenga abierta esta guía paso a paso mientras ve el vídeo.
- Puede servirle como referencia útil si necesita contexto o aclaraciones adicionales mientras sigue los pasos del vídeo.
- No se trata de una actividad calificada, pero puede completar estos pasos para practicar las habilidades demostradas en el vídeo.

- Qué necesitará
   - Si desea seguir el primer ejemplo de este vídeo, elija una herramienta de hoja de cálculo y abra una hoja en blanco. 
   - Si desea acceder a la otra hoja de cálculo que el instructor utiliza en este vídeo, haga clic en el enlace al Conjunto de datos para crear una copia.
   - Si no tiene una cuenta de Google, descargue los datos directamente de los archivos adjuntos a continuación.
   - [Archivo ejemplo](./resources/modulo-03/Monthly-Sales.xlsx)

- Ejemplo 1: Crear una fórmula
   - Las fórmulas constituyen la base de tareas más complejas en una hoja de cálculo.
   - He aquí un ejercicio sencillo: 
      - Abra una nueva hoja de cálculo.
      - Seleccione la celda A1. 
      - Introduzca =2-2 y pulse Intro. La Célula muestra el resultado de 0. 
      - Seleccione la celda A2. 
      - Introduzca =31982-17795 y pulse Intro.
      - La Célula muestra el resultado 14187.
      - Nota: El signo igual (=) significa que está comenzando una fórmula.
- Ejemplo 2: Utilizar referencias de celda en una fórmula
   - Las referencias de celda hacen que su hoja de cálculo sea flexible y responda a los cambios de datos.
   - Para Implementar esto:
      - Abra la hoja de cálculo Ventas mensuales.
      - Para hallar las ventas totales de abril a julio de 2017, seleccione la celda F2. 
      - Introduzca la fórmula =B2+C2+D2+E2 y pulse Intro.
      - Ahora tiene el total de ventas para este periodo de tiempo.
      - Pero, ¿qué pasaría si los Datos de una de las Células fueran incorrectos?
      - Seleccione la celda D2 e introduzca 47002 para corregir la entrada.
      - Pulse Intro.
      - Observe que su hoja de cálculo recalcula automáticamente la suma en la celda F2.
- Ejemplo 3: Copiar una fórmula
   - Copiar y pegar fórmulas ahorra tiempo y ayuda a garantizar la coherencia de sus cálculos.
   - Para ello:
      - En la hoja de cálculo Ventas mensuales, seleccione la celda F2. 
      - En el menú Edición , seleccione Texto publicitario (Copiar).
      - También puede utilizar el acceso directo del teclado de Windows Ctrl+C o el acceso directo del teclado de Mac Comando+C para copiar la fórmula.
      - Seleccione la celda F3 y, en el menú Edición , elija Pegar.
      - También puede pulsar Ctrl+V (Windows) o Comando+V (Mac) para pegar la fórmula en la celda F3. 
      - Nota: Después de pegar en la celda F3, la fórmula en esa celda será =B3+C3+D3+E3.
- Ejemplo 4: Calcular las ventas medias
   - Utilice fórmulas para diferentes cálculos, como por ejemplo para hallar una media:
      - En la hoja de cálculo Ventas mensuales , seleccione la celda G1.
      - Introduzca Ventas medias en la celda G1 y pulse Intro. 
      - Seleccione de nuevo la celda G1.
      - En la barra de herramientas, seleccione Negrita para poner el texto en negrita.
      - Nota: Nombrar las columnas en las hojas de cálculo mejora la claridad al indicar el propósito de los números.
      - Seleccione la celda G2.
      - Introduzca =(B2+C2+D2+E2)/4 y pulse Intro para calcular la media de ventas en este periodo de tiempo.
      - Nota: Esta fórmula calcula la media de las ventas del mes, incluidos los casos en los que no hay ventas (celdas en blanco), que se tratan como ceros en el cálculo.
      - Si el negocio tuvo cero ventas durante un mes, la celda en blanco se sigue incluyendo en el cálculo para mantener la exactitud.
      - Copie y pegue la fórmula de la celda G2 en las celdas G3 y G4. 
- Ejemplo 5: Calcular el cambio porcentual en las ventas 
   - Utilice una fórmula diferente para calcular el cambio porcentual:
      - En la hoja de cálculo Ventas mensuales , seleccione la celda H1.
      - En la Célula H1, introduzca Cambio de junio a julio.
      - Ponga este texto en negrita.
      - En la celda H2, introduzca =(E2-D2)/D2 para calcular el cambio porcentual en las ventas.
      - Para formatear el valor como porcentaje, en la barra de herramientas, seleccione el botón %.
      - Ahora encontrará que el cambio porcentual en las ventas entre junio y julio es de 247,5%. 
      - Copie esta fórmula en la Célula H3.
      - Observe que la hoja de cálculo copia tanto la fórmula como el formato del porcentaje.
- Ejemplo 6: Corregir un error de fórmula
   - Corregir los errores de fórmula garantiza que sus análisis de datos sigan siendo precisos y fiables.
   - He aquí cómo solucionar un error común:
      - En la hoja de cálculo Ventas mensuales, copie la fórmula de la celda H2 a la celda H4 y pulse Intro. 
      - Observe el error que aparece en la celda H4.
      - Este error se produce porque la fórmula está intentando dividir por un valor de cero.
      - La razón de este error es que la celda D4 está en blanco y, en este contexto, la hoja de cálculo interpreta que tiene un valor de cero.
      - Para resolver el error, escriba 75866 en la celda D4 y pulse Intro.
      - Observe que el error desaparece, y la celda H4 muestra ahora 121,16%. 

---

## Fórmulas para el éxito
- ​Hasta ahora hemos explicado cómo crear una nueva hoja de cálculo, ​introducir datos y hacer que parezca ​refinada y lista para un análisis serio.
- ​Ahora aprenderemos cómo realizar ​cálculos en tu hoja de cálculo.
- ​Es posible que tengas que calcularlo todo, ​desde sumas hasta promedios, ​hasta encontrar cantidades mínimas y máximas.
- ​Usarás los cálculos para ​muchos tipos diferentes de tareas.
- ​En este vídeo, nos centraremos en aprender los conceptos básicos ​y, a continuación, haremos algunos cálculos matemáticos con ​algunos datos de ventas para practicar.
- ​Hablemos primero de las fórmulas.
- ​Tal vez recuerde que una fórmula es un conjunto de ​instrucciones que realizan un cálculo específico.

- ​Básicamente, las fórmulas pueden hacer los cálculos por ti.
- ​Ahora, no solo hacen matemáticas, ​pueden hacer mucho más.
- ​Pronto aprenderá diferentes maneras de ​utilizarlos en los procesos de análisis de datos.
- ​Las fórmulas se basan en operadores, que son símbolos que ​indican el tipo de operación o ​cálculo que se va a realizar.
- ​Por ejemplo, el signo más es un operador común.
- ​Las fórmulas que utiliza como analista de datos ​suelen incluir al menos un operador.
- ​Ahora, hablemos de expresiones o ecuaciones matemáticas.

- ​Estas pueden adoptar muchas formas diferentes, ​pero es posible que ya las conozcas.
- ​3 menos 1, 15 más 8 dividido por 2, 846 veces 513.
- ​Todos estos son ejemplos de expresiones.
- ​¿Esto me trae recuerdos de la escuela primaria? ​Bueno, en la clase de matemáticas, ​lo más probable es que hayas aprendido a completar una expresión ​incluyendo un signo igual y la solución.
- ​Es un poco diferente con las hojas de cálculo.
- ​Cuando se crea una fórmula con ​una expresión de una hoja de cálculo, se ​inicia la fórmula con un signo igual.
- ​Por ejemplo, si queremos restar, ​escribimos un signo igual seguido del resto de ​la expresión sin espacios en la fórmula.

- ​Ahora probemos con una expresión ​que sea un poco más difícil.
- ​Escribiremos 31982, luego ​un guión para el signo menos y, a continuación, 17795.
- ​Para calcular, presionamos «Enter».
- ​Lo más probable es que utilices ​fórmulas de esta manera cuando trabajes con ​números grandes o expresiones con varios pasos.
- ​Estos son los operadores que usará para completar las fórmulas.
- ​El signo más para la suma, ​el menos o el guión para la resta, ​el asterisco para la multiplicación ​y la barra diagonal para la división.
- ​Los símbolos de división y multiplicación ​pueden ser diferentes a los que estás acostumbrado.

- ​Cambios pequeños, pero importantes a tener en cuenta.
- ​Si ya tienes datos en la hoja de cálculo, ​puedes usar referencias de celda en tus fórmulas en su lugar.
- ​Una referencia de celda es una sola celda o un ​rango de celdas de ​una hoja de cálculo que se puede usar en una fórmula.
- ​Las referencias a las celdas contienen ​la letra de la columna y el número de la fila donde están los datos.
- ​Un rango de celdas es un conjunto de dos o más celdas.
- ​Un rango puede incluir celdas de la misma fila o columna, ​o de diferentes columnas y filas agrupadas juntas.
- ​Te mostraremos un ejemplo en un próximo vídeo.

- ​Ahora vamos a aplicar lo que acabamos de aprender a algunos datos de ventas.
- ​Si queremos agregar estas cifras para encontrar las ​ventas totales de la primera fila de datos, ​puede hacer clic en la «celda F2".
- ​A partir de ahí, comenzaremos con un signo igual y usaremos ​las referencias de celda para introducir valores en la expresión.
- ​Empezamos con la celda B2 porque el año en ​A2 no es un valor que queramos añadir al total.
- ​A continuación, pulse «Entrar».
- ​Así de simple, ​se calcularon sus ventas totales, ​pero ¿qué pasaría si se diera cuenta de que uno de ​los valores de sus datos era incorrecto? ​No hay problema ​Puedes cambiar el valor de cualquier celda usando ​la fórmula y el total se actualizará automáticamente.

- ​Lo mejor de usar referencias de celda es que ​también se actualizan automáticamente cuando ​se copia una fórmula en una celda nueva.
- ​Hable sobre un ahorro de tiempo.
- ​En lugar de volver a escribir la misma fórmula ​para cada nuevo conjunto de referencias de celda, ​basta con copiar la fórmula mediante ​el menú o un método abreviado de teclado, como Control más C.
- ​Después, pega la fórmula donde quieras aplicarla con ​Control más V.
- ¡Y listo! ​La fórmula actualiza ​correctamente todas las celdas y valores nuevos.
- ​Ahora supongamos que también quieres que encuentre el promedio de ventas.

- ​Para ello, crea una nueva fórmula en una celda diferente.
- ​Para agrupar valores en una fórmula, utilice paréntesis.
- ​Esto permite que la hoja de cálculo sepa qué valores se deben calcular ​juntos y el orden de las operaciones que se van a realizar.
- ​Por ejemplo, abra paréntesis, ​luego B2 más C2 más D2 más E2 ​, cierre los paréntesis y, a continuación, ​divida el valor de todo esto escribiendo la barra cuatro.
- ​Estás sumando los valores de las cuatro celdas ​y luego usando la barra para dividir el total entre cuatro, ​y al igual que en la última, ​podemos copiar y pegar la fórmula.
- ​Esta es otra fórmula que puedes usar si quieres encontrar ​el cambio porcentual en las ventas entre junio y julio.
- ​Una vez que una fórmula calcula el valor, ​puede usar el botón de porcentaje ​para cambiar el valor a un porcentaje.

- ​Al aplicar la fórmula a las demás filas, ​tanto la fórmula como ​el porcentaje se actualizarán automáticamente.
- ​No parece la respuesta correcta.
- ​Parece que tenemos un error.
- No te preocupes ​Los errores pueden producirse en cualquier etapa del análisis de datos, ​incluso cuando se utilizan hojas de cálculo.
- ​Una fórmula tiene que ser hermética.
- ​Si hay algún problema con una de ​las referencias de celda, no funcionará.
- ​Entonces, ¿cuál es nuestro error? 
- ​Bueno, podemos ver que falta el valor en la celda D4.
- ​Puede que te lleve algo de tiempo e ​investigar para encontrar el valor correcto, pero vale la pena.
- ​Desea que su análisis sea lo más preciso posible.
- ​Cuando añadas el valor, ​la fórmula se encarga del resto.
- ​Era mucho para asimilar.
- ​Gracias por quedarte conmigo.
- ​Podrá aplicar lo que ​ha aprendido sobre las fórmulas aquí y más adelante ​en el programa para hacer que ​su análisis sea más eficiente y su trabajo, ​un poco más fácil, y ​pronto trabajará en su propia hoja de cálculo.
- ​Felices hojas de cálculo.

---

## Referencia rápida: Fórmulas en hojas de cálculo
- Ha estado aprendiendo mucho sobre las hojas de cálculo y todo tipo de cálculos que ahorran tiempo y las funciones organizativas que ofrecen.
- Una de las características más valiosas de las hojas de cálculo es la fórmula.
- Como recordatorio rápido, una fórmula es un conjunto de instrucciones que realiza un cálculo específico utilizando los datos de una hoja de cálculo.
- Las fórmulas facilitan a los analistas de datos la realización automática de cálculos potentes, lo que les ayuda a analizar los datos con mayor eficacia.
- A continuación encontrará una guía de referencia rápida que le ayudará a sacar el máximo partido de las fórmulas.

- Fórmulas
   - Conceptos básicos
      - Cuando se introduce una fórmula en matemáticas, generalmente termina con un signo igual (2 + 3 = ?).
         - Pero con las fórmulas, siempre empiezan por uno en su lugar (=A2+A3).
         - El signo igual indica a la hoja de cálculo que lo que sigue es parte de una fórmula, no sólo una palabra o un número en una celda.
      - Después de introducir el signo igual, la mayoría de las aplicaciones de hojas de cálculo mostrarán un menú de autocompletar que enumera las fórmulas, los nombres y las cadenas de texto válidos.
         - Es una forma estupenda de crear y editar fórmulas evitando errores de escritura y de sintaxis.
      - Una forma divertida de aprender nuevas fórmulas es simplemente tecleando un signo igual y una sola letra del alfabeto.
         - Elija una de las opciones que aparecen y aprenderá lo que hace esa fórmula.

- Operadores matemáticos
   - Los operadores matemáticos utilizados en las fórmulas de las hojas de cálculo son:
      - Resta - signo menos ( - )
      - Suma - signo más ( + )
      - División - barra diagonal ( / )
      - Multiplicación - asterisco ( * )

- Autorrelleno 
   - La esquina inferior derecha de cada Célula tiene un Controlador de relleno.
   - Es un pequeño cuadrado verde en Microsoft Excel y un pequeño círculo azul en Google Sheets.
      - Clic en el cuadrado o círculo del controlador de relleno de una celda y arrástrelo hacia abajo en una columna para autorellenar otras celdas de la columna con el mismo valor o fórmula de esa celda.
      - Haga clic en el cuadrado o círculo del controlador de relleno de una celda y arrástrelo a través de una fila para rellenar automáticamente otras celdas de la fila con el mismo valor o fórmula en esa celda.
      - Si desea crear una secuencia numerada en una columna o fila, haga lo siguiente: 1) Rellene los dos primeros números de la secuencia en dos celdas adyacentes, 2) Seleccione para resaltar las celdas y 3) Arrastre el cuadrado o círculo del controlador de relleno hasta la última celda para completar la secuencia de números.
      - Por ejemplo, para insertar del 1 al 100 en cada fila de la columna A, introduzca el 1 en la celda A1 y el 2 en la A2.
      - A continuación, seleccione para resaltar ambas celdas, haga clic en el cuadrado o círculo del controlador de relleno de la celda A2 y arrástrelo hacia abajo hasta la celda A100.
      - Esto rellena automáticamente los números de forma secuencial para que no tenga que introducirlos en cada celda.

- Referenciación absoluta
   - Las referencias absolutas están marcadas con un signo de dólar ($).
   - Por ejemplo, =$A$10 tiene referenciación absoluta tanto para la columna como para el valor de la fila
   - Las referencias relativas (que es lo que se hace normalmente, por ejemplo "=A10") cambiarán cada vez que se copie y pegue la fórmula.
   - Están en relación con el lugar donde se encuentra la celda referenciada.
   - Por ejemplo, si copiara "=A10" en la celda de la derecha, se convertiría en "=B10".
   - Con la referenciación absoluta "=$A$10" copiado a la celda de la derecha seguiría siendo "=$A$10".
   - Pero si copiara $A10 a la celda de abajo, cambiaría a $A11 porque el valor de la fila no es una referencia absoluta.
   - Las referencias absolutas no cambiarán cuando copie y pegue la fórmula en una celda diferente.
   - La celda a la que se hace referencia es siempre la misma.
   - Para cambiar fácilmente entre referencias absolutas y relativas en la barra de fórmulas, resalte la referencia que desea cambiar y pulse la tecla F4; por ejemplo, si desea cambiar la referencia absoluta, $A$10, de su fórmula por una referencia relativa, A10, resalte $A$10 en la barra de fórmulas y pulse la tecla F4 para realizar el cambio.

- Rango de datos
   - Cuando haga clic en su fórmula, los rangos coloreados le permitirán ver qué celdas se están utilizando en su hoja de cálculo.
   - Hay diferentes colores para cada rango Único en su fórmula.
   - En muchas aplicaciones de hojas de cálculo, puede pulsar la tecla F2 (o Intro) para resaltar el rango de datos de la hoja de cálculo al que se hace referencia en una fórmula.
   - Haga clic en la celda con la fórmula y, a continuación, pulse la tecla F2 (o Intro) para resaltar los datos de su hoja de cálculo.

- Combinación con funciones
   - COUNTIF() es una fórmula y una función.
   - Esto significa que la función se ejecuta en función de los criterios establecidos por la fórmula.
   - En este caso, COUNT es la fórmula; se ejecutará SI las condiciones que usted cree son verdaderas.
   - Por ejemplo, podría utilizar =COUNTIF(A1:A16, “7”) para contar sólo las celdas que contienen el número 7.
   - Combinar fórmulas y funciones le permite hacer más trabajo con un solo comando.

---

## Actividad práctica: Análisis de datos y fórmulas: Estadísticas de ventas en panadería
- Resumen de la actividad
   - Hasta ahora, usted ha sido introducido a los fundamentos del uso de fórmulas para realizar cálculos para el Análisis de datos.
   - En esta actividad, editarás la hoja de cálculo Ventas de panadería que creaste anteriormente en la actividad Práctica: Introducción a Google Sheets.
   - Volverás a consultar los datos y revisarás los datos nuevos; a continuación, utilizarás fórmulas para calcular las Métricas clave y obtener información estadística.
   - Cuando termines esta actividad, estarás más familiarizado con el uso de fórmulas sencillas para analizar y extraer información significativa de los conjuntos de datos.
   - Saber utilizar fórmulas en aplicaciones de hojas de cálculo es una habilidad esencial para cualquier analista de datos, ya que le ayudan a automatizar cálculos, tomar decisiones basadas en datos y ahorrar tiempo.

- Instrucciones paso a paso
   - Siga las instrucciones para completar cada paso de la actividad.
   - A continuación, responda a la pregunta al final de la actividad antes de pasar al siguiente punto del curso.

1. Acceder a la hoja de cálculo
- Para empezar, determine qué software desea utilizar, como Google Sheets o Microsoft Excel.
- También necesitará la hoja de cálculo actualizada Ventas de panadería marzo 2020, que contiene datos nuevos que no estaban en la actividad anterior. 
- Para utilizar la plantilla para este tema del curso, haga clic en el enlace de abajo y seleccione "Usar plantilla" 
- Plantilla: Ventas de panadería marzo 2020 
- [archivo](./resources/modulo-03/Bakery-Sales-March-2020.xlsx)

2. Editar una hoja previa existente
- La nueva hoja de cálculo Ventas de panadería marzo 2020 se ha actualizado con los datos de ventas de la panadería local para los días restantes del mes.
- En esta actividad, utilizará fórmulas para calcular métricas esenciales que revelen los ingresos generados por cada producto.
- Este análisis de datos le proporcionará información valiosa sobre el rendimiento de la panadería local. 
- El gerente de la panadería local quiere saber cuántas unidades de cada producto se vendieron y cuántos ingresos aportó cada producto durante este periodo de ventas.
- Para encontrar las respuestas, siga estos pasos:
   1. Cree un nuevo Atributo llamado Ingresos en la celda E1. Ponga en negrita y centre el nombre de esta columna como hizo anteriormente.
   2. Para calcular los ingresos de las 30 magdalenas vendidas el 25/3, seleccione la celda E2. A continuación, multiplique el número de magdalenas vendidas por el precio de cada magdalena. Introduzca =C2*D2 y pulse Intro.
   3. Copie la fórmula (o utilice el tirador de relleno) de la celda E2 a E3:E22.
   4. Para hallar el número total de cada producto vendido, calcule primero la cantidad total de cada uno. Empiece por hacer que los datos sean claros y fáciles de leer. En la celda G3, introduzca el Nº total de Cookies vendidas. En la celda G4, introduzca # Total de Magdalenas Vendidas. En la celda G5, introduzca # Total de Magdalenas Vendidas. En la celda G6, introduzca # Total de Pasteles vendidos.
   5. Ahora, calcule la cantidad total de Cookies vendidas. Seleccione la celda H3, introduzca =D3+D8+D13+D18+D22 y pulse Intro.
   6. A continuación, calcule la cantidad total de magdalenas, muffins y tartas vendidas siguiendo los mismos pasos.
   7. El director de la panadería también desea saber cuántos ingresos le ha reportado cada producto.
   8. Empiece por hacer que los datos sean claros y fáciles de leer. En la celda G9, introduzca Ingresos por galletas. En la celda G10, introduzca Ingresos por magdalenas. En la celda G11, introduzca Ingresos por magdalenas. En la celda G12, introduzca Ingresos por pasteles.
   9. Para calcular los ingresos totales de las galletas, multiplique el número total de galletas vendidas por el precio de cada galleta.
   10. Seleccione la celda H9, introduzca =H3*1, y pulse Intro.
   11. Por último, calcule los ingresos del resto de los productos (magdalenas, muffins y tartas) vendidos siguiendo los mismos pasos.

- Reflexión
   - En esta actividad, ha utilizado fórmulas para calcular el número total de productos vendidos de cada tipo y los ingresos totales de cada uno. En el espacio que se proporciona a continuación, escriba de 2 a 3 frases (de 40 a 60 palabras) para responder a cada una de las siguientes preguntas:
   - ¿Qué producto vendió más la panadería? ¿Recomendaría algún cambio en la estrategia de ventas de la panadería basándose en esta información?
   - ¿Qué producto generó más Ingresos para la panadería? Basándose en esta conclusión, ¿qué medidas recomendaría que tomara la panadería para mejorar su rentabilidad?
   - Considere cómo ha utilizado las fórmulas en esta actividad. ¿De qué manera mejorarán las fórmulas su eficacia como Analista de datos? ¿Cuáles son las ventajas de las fórmulas para el Análisis de datos?
> El producto que más vendió en la panadería fueron los Cupcakes con 291 unidades. Basado en los datos aprovecharía de hacer ofertas relacionadas, como un cupcake más un té, café o incluso 2 cupcake a un precio un pooc menor. El producto con mayor ingreso son los Cupcakes, ya que vendieron bastante más que otros productos aunque a un precio menor. Para mejorar la rentabilidad verificaría si se puede ahorrar un porcentaje en el proceso de producción de Cupcakes para obtener mayor ganancia o ver un margen de aumento de precio verificando mensualmente como afecta a la ventas. Las formulas ayudan a agilizar el proceso de obtención de información, por ejemplo, no fue necesario usar la calculadora para calcular el revenue para cada producto, realizamos la formula una sola vez y luego aplicamos la misma al resto.

- Comentarios
Gran trabajo analizando los datos y haciendo recomendaciones que la panadería puede aprovechar para mejorar sus operaciones. A medida que siga desarrollando sus habilidades como analista de datos, esta experiencia le resultará inestimable. Demuestra su destreza en el uso de fórmulas para extraer estadísticas de los datos y tomar decisiones con conocimiento de causa. Se trata de una habilidad altamente transferible a escenarios del mundo real en su futura carrera. Siga perfeccionando sus habilidades analíticas, ya que serán un recurso clave en su trayectoria profesional.

- [Archivo resuelto](./resources/modulo-03/Bakery-Sales-March-2020-resuelto.xlsx)

---

## Hoja de cálculo errores y correcciones
- ​Hola y bienvenidos de nuevo.
- ​Recientemente hemos estado aprendiendo sobre fórmulas.
- ​A veces los Analistas de datos nos encontramos ​con un problema con nuestras fórmulas y obtenemos un error.
- ​Todos hemos pasado por eso y puede ser frustrante.
- ​Pero hay soluciones, ​eso es lo que vamos a explorar en este vídeo.
- ​Un error que puede encontrarse es el error DIV.
- ​El error DIV se produce cuando una fórmula está intentando dividir ​un valor de una celda por cero o por una celda vacía.

- ​En esta hoja de cálculo, ​los valores de porcentaje Completo en ​la columna C se calculan ​dividiendo los valores de ​la columna Tareas Completadas entre ​los valores de la columna Tareas Requeridas.
- ​Note que la columna C ya está ​formateada como porcentaje.
- ​El error DIV está en la celda C4 porque estamos ​dividiendo por cero el valor de la celda A4.
- ​Para evitar este problema, ​podemos hacer que esta hoja de cálculo ​introduzca automáticamente no aplicable ​siempre que una celda de la columna A ​contenga un cero que provocaría el error.
- ​Para ello, utilizaremos la función IFERROR.
- ​Si encuentra un error DIV ​causado por una celda que contenga el cero, ​se insertará la frase "No aplicable".
- ​También podemos copiar la fórmula al resto de celdas de la ​columna C para que compruebe ​cualquier otra celda que contenga un cero.

- ​Ahora pasemos al ERROR.
- ​En Google Sheets, ​ERROR nos indica que la fórmula no puede ​interpretarse tal y como se introduce.
- ​También se conoce como error de análisis sintáctico.
- ​Digamos que queremos contar el número de ​total de tareas en las columnas B y C, ​utilizamos la función SUM, ​pero la fórmula igual suma B2 a B6, ​C2 a C6 provoca un error.
- ​Examinándolo más detenidamente, ​vemos que falta una coma entre ​los rangos de celdas B2 a B6 y C2 a C6.
- ​Podemos solucionarlo insertando una coma entre los rangos de celdas ​para indicar el final de cada elemento de datos.
- ​Esto se denomina un delimitador, ​del que aprenderá más próximamente.

- ​Ahora, la fórmula puede ​calcular correctamente el número total de tareas como 25.
- ​Otro tipo de error es N/A.
- ​El error N/A le indica que los datos ​de su fórmula no pueden ser encontrados por la hoja de cálculo.
- ​Generalmente, esto significa que los datos no existen.
- ​Este error suele producirse ​cuando se utilizan funciones como VLOOKUP, ​que busca un determinado valor en una columna ​para devolver un dato correspondiente.
- ​Aquí, vemos una lista maestra de frutos secos y sus precios.
- ​Usando VLOOKUP, la hoja de cálculo encuentra los precios en la lista, ​y luego calcula los precios de ​cada tienda utilizando el margen de beneficio asignado.

- ​Pero tenemos un error N/A en las celdas B49 y C49.
- ​La fórmula VLOOKUP es correcta, ​entonces, ¿qué está pasando? ​Bueno, si nos fijamos bien en el nombre del fruto seco, ​"almendra" no tiene ningún MATCH en la tabla de búsqueda, ​la tabla de búsqueda utiliza el plural "almendras" en su lugar.
- ​Así que cambiamos almendra por almendras, ​y con esa errata corregida, ​se rellenan los precios correctos.
- ​Hablando de erratas, a veces ​una errata puede causar un error de NOMBRE.
- ​Un error de NOMBRE puede producirse cuando ​no se reconoce o no se entiende el nombre de una fórmula.
- ​Supongamos que vemos un error de NOMBRE ​en la hoja de cálculo de los precios de los frutos secos.

- ​Si nos fijamos bien, ​la función VLOOKUP en la Célula B21 está mal escrita, ​tiene una O de más; ​esto provoca un error de NOMBRE tanto para ​el precio como para ​el cálculo de margen resultante para la tienda.
- ​Para solucionar este error, ​podemos eliminar la O de más en VLOOKUP.
- ​Perfecto.
- A veces, un error ​está causado por datos incoherentes o erróneos.
- ​Por ejemplo, el error NUM nos dice que ​el cálculo de una fórmula no puede ​realizarse tal y como especifican los datos.
- ​Los datos no tienen sentido para ese cálculo.
- ​A esto me refiero.

- ​Supongamos que estamos trabajando en ​un gran proyecto de construcción utilizando ​una hoja de cálculo para hacer un seguimiento ​de cuántos meses se tarda en alcanzar los hitos clave.
- ​Podemos utilizar la función DATEDIF para ​calcular el número de meses ​entre las fechas de inicio y fin.
- ​La función requiere que la fecha de inicio ​esté en la primera celda ​referenciada y que la fecha de fin ​esté en la segunda celda referenciada.
- ​En nuestro caso, las celdas B2 y C2 respectivamente.
- ​La M representa meses, ​ya que queremos que esta hoja de cálculo calcule el número de ​meses entre nuestras fechas inicial y final.
- ​Pero obtenemos un error NUM en la celda D6.
- ​Nos damos cuenta de que la fecha final es anterior a la fecha inicial, ​por lo que la función DATEDIF ​no puede calcular el número de meses entre ambas.

- ​Es probable que las fechas de inicio y fin ​se hayan intercambiado por accidente.
- ​Podemos solicitar la verificación de los datos para asegurarnos.
- ​Mientras tanto, invirtamos el orden de ​las celdas de la fórmula para ​salvar temporalmente el error.
- ​Ahora, el resultado es nueve meses.
- ​¿Y si el nombre del cliente se ​insertó accidentalmente en la fecha de inicio de la hoja de cálculo? ​Adivinó, obtenemos un error.
- ​El error VALUE puede indicar ​un problema con una fórmula o celdas referenciadas.

- ​A menudo no está claro de inmediato cuál es el problema, ​por lo que este error puede requerir un poco más de esfuerzo para solucionarlo.
- ​En este caso, se introdujo John Welty como fecha de inicio, ​haciendo imposible el cálculo para ​la función DATEDIF en la celda D6.
- ​Simplemente sustituimos el texto, John Welty, ​por la fecha de inicio correcta del 1 de septiembre de 2016.
- ​El último es el error REF, ​que suele aparecer cuando se han eliminado celdas a las que se ​hace referencia en una fórmula, ​haciendo así que la fórmula no pueda ​realizar el cálculo.
- ​Aquí tiene una hoja de cálculo utilizada para calcular ​el número de asientos disponibles para una comida de empresa.
- ​Digamos que la empresa ​decidió no realizar la segunda planta, ​así que borramos la fila 4.
- ​Esto da lugar a un error REF cuando ​calculamos el total de asientos disponibles en la celda B5.

- ​Para solucionarlo, podemos cambiar la fórmula para ​añadir los valores de las celdas B2 y B3.
- ​Además, en este caso, ​podríamos haber evitado ​el error REF utilizando la función SUM y ​un Rango de celdas en lugar de añadir ​el valor de la celda por referencia directa.
- ​Ahora, si borramos la fila 10, ​la función SUM calcula el total de asientos ​disponibles.
- Ya está.
- ​Ahora hemos corregido algunos de ​los errores más comunes de las hojas de cálculo.
- ​Cuando vuelva a verlos, ​sabrá lo que significan.
- ​La solución de problemas es una parte importante del análisis de datos, ​por lo que ser capaz de encontrar soluciones ​es una habilidad clave para los analistas de datos.
- [archivo del video](./resources/modulo-03/Spreadsheet-Errors-and-Fixes-Demo-Sheets.xlsx)