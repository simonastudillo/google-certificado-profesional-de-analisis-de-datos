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