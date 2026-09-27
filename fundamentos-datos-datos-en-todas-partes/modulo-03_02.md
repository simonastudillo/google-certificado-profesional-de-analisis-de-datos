# Empezar con SQL y la visualización de datos

## SQL en acción
- ​Como recordará, anteriormente ​hablamos del Lenguaje de consulta SQL.
- ​En este vídeo, verá SQL en ​acción y aprenderá lo que puede hacer con él, ​con algunos ejemplos de `query` específicas.
- ​Supongo que puede llamarse a esto la secuela de SQL.
- ​Intentaremos que ésta sea incluso mejor que la original.
- ​Recuerde, SQL puede hacer con los datos muchas ​de las mismas cosas que pueden hacer las hojas de cálculo.
- ​Puede utilizarlo para almacenar, ​organizar y analizar sus datos, entre otras cosas.
- ​Pero como toda buena secuela, ​es a mayor escala, más grande, más llena de acción.

- ​Piense en ella como en hojas de cálculo supergrandes.
- ​Por ejemplo, podría considerar ​una hoja de cálculo cuando tenga un conjunto de datos más pequeño, ​como uno con sólo 100 filas.
- ​Pero si su conjunto de datos parece no tener fin, ​y su hoja de cálculo tiene dificultades para seguirle el ritmo, ​SQL sería el camino a seguir.
- ​Cuando utilice SQL, necesitará ​un lugar donde se entienda el lenguaje SQL.
- ​Si alguna vez ha ido a algún sitio y no conoce el idioma, ​puede ser un reto comunicarse.
- ​Puede pensar que está pidiendo ​una cosa y obtener algo completamente diferente.
- ​Bueno, SQL conoce esa sensación.

- ​SQL necesita una base de datos que entienda su lenguaje.
- ​Hablemos.
- Hay una serie ​de bases de datos por ahí que utilizan SQL.
- ​Es posible que utilice varias de ellas ​durante su tiempo como Analista de datos.
- ​Pero aquí está la cosa, ​no importa qué base de datos utilice, ​SQL funciona básicamente para lo mismo en cada una.
- ​Por ejemplo, en SQL, las `query` son universales.
- ​Hemos hablado de `query` antes, ​pero nunca está de más tener un repaso.

- ​Una `query` es una solicitud de ​datos o información de una base de datos.
- ​Aquí tiene la estructura de una `query` básica.
- ​Puede ver que con esta `query` podemos ​seleccionar datos específicos de ​una tabla añadiendo donde podemos ​filtrar los datos basándonos en determinadas condiciones.

<img src="./resources/modulo-03/image.png" width="500px">

- ​Comencemos.
- Abriremos nuestra base de datos y veremos cómo ​SQL puede comunicarse con ella para realizar alguna tarea de datos sencilla.
- ​Primero, vamos a seleccionar nuestro conjunto de datos.
- (La Base de datos mostrada es BigQuery, que se trata en el Curso 3 de este certificado.)
- ​Usaremos un asterisco para ​seleccionar todos los datos de la tabla.

- ​Con esa sencilla `query`, ​la base de datos llama a la tabla que necesitamos.
```SQL
SELECT *
FROM movie_data.movies;
```
- ​Magic.
- Vamos a añadir Where ​a nuestra `query` para mostrar cómo eso cambia los datos que obtenemos.
```SQL
SELECT *
FROM movie_data.movies
WHERE Genre__1_ = 'Action';
```
- ​Puede ver que los datos ahora sólo muestran, ​películas que pertenecen al género de acción.
- ​Eso es todo, una `query` básica en SQL.
- ​Magnífico, ¿verdad? Pronto ​aprenderá a crear `query` más complejas.

- ​Por ahora, sin embargo, podemos celebrar ​el aprendizaje de la estructura de una `query` SQL básica, ​select, from y where.
- ​A medida que continúe con el Programa, ​tendrá la oportunidad de utilizar SQL usted mismo.
- ​Espero que este vídeo haya sido ​un útil anticipo de lo que vendrá más adelante.

---

## Guía SQL: Comenzar
- Al igual que los humanos utilizamos distintos lenguajes para comunicarnos con los demás, también lo hacen las computadoras.
- El Lenguaje de `query` Estructurado (o SQL, a menudo pronunciado "sequel") permite a los analistas de datos hablar con sus bases de datos.
- SQL es una de las herramientas más útiles de los analistas de datos, sobre todo cuando trabajan con grandes conjuntos de datos en tablas.
- Puede ayudarle a investigar enormes bases de datos, rastrear textos (denominados cadenas) y números, y filtrar para encontrar el tipo exacto de datos que necesita, mucho más rápido de lo que puede hacerlo una hoja de cálculo.
- Si no ha utilizado SQL antes, esta lectura le ayudará a aprender los conceptos básicos para que pueda apreciar lo útil que es SQL y, en particular, las `query`s SQL.
- Escribirá `query`s SQL en un abrir y cerrar de ojos.

- ¿Qué es una `query`?
   - Una `query` es una petición de datos o información a una base de datos.
   - Cuando `query` bases de datos, utiliza SQL para comunicar su pregunta o solicitud.
   - Usted y la base de datos siempre pueden intercambiar información, siempre que hablen el mismo idioma.
   - Todos los lenguajes de programación, incluido el SQL, siguen un conjunto único de pautas conocidas como sintaxis.
   - La sintaxis es la estructura predeterminada de un lenguaje que incluye todas las palabras, símbolos y signos de puntuación necesarios, así como su correcta colocación.
   - En cuanto introduzca sus criterios de búsqueda utilizando la sintaxis correcta, la `query` empezará a funcionar para extraer los datos que ha solicitado de la base de datos de destino.
- La sintaxis de todas las `query`s SQL es la misma:
   - Utilice SELECT para elegir las columnas que desea devolver.
   - Utilice FROM para elegir las tablas donde se encuentran las columnas que desea.
   - Utilice WHERE para filtrar determinada información.
- Una `query` SQL es como rellenar una plantilla.
- Si está escribiendo una `query` SQL desde cero, le resultará útil comenzar la `query` escribiendo las palabras clave SELECT, FROM y WHERE en el siguiente formato:
```sql
SELECT 

FROM 

WHERE 
```
- A continuación, introduzca el nombre de la tabla después de FROM; las columnas de la tabla que desee después de SELECT; y, por último, las condiciones que desee colocar en su `query` después de WHERE.
- Asegúrese de añadir una nueva línea y una sangría al añadirlas, como se muestra a continuación:

| SELECT | Especifica las columnas de las que recuperar los datos |
| ----   | --------------                                         |
| FROM   | Especifica la tabla de la que recuperar los datos      |
| WHERE  | Especifica los criterios que deben cumplir los Datos   |

- Si sigue este Método cada vez, le resultará más fácil escribir `query` SQL.
- También puede ayudarle a cometer menos errores de sintaxis.

- Ejemplo de consulta
   - He aquí cómo aparecería una consulta sencilla en BigQuery, un almacén de datos en la plataforma Google Cloud Platform.
   ```sql
   SELECT first_name
   FROM customer_data.customer_name
   WHERE first_name = 'Tony'
   ```
   - La consulta anterior utiliza tres comandos para localizar a los clientes con la dirección first_name, 'Tony':
      1. SELECT la columna denominada first_name
      2. FROM una tabla denominada customer_name (en un conjunto de datos denominado customer_data) (El nombre del conjunto de datos siempre va seguido de un punto y, a continuación, el nombre de la tabla)
      3. Pero sólo devuelve los datos WHERE el first_name es 'Tony'
   - Los resultados de la consulta podrían ser similares a los siguientes:

   | first_name |
   | -------    |
   | Tony       |
   | Tony       |
   | Tony       |

   - Como puede concluir, esta consulta tenía la sintaxis correcta, pero no era muy útil una vez devueltos los datos.

- Varias columnas en una consulta
   - Por supuesto, como profesional de los datos, necesitará trabajar con más datos aparte de Clientes llamado Tony.
   - Varias columnas seleccionadas con el mismo comando SELECT pueden sangrarse y agruparse.
   - Si solicita varios campos de datos de una tabla, deberá incluir estas columnas en su comando SELECT.
   - Cada columna se separa con una coma como se muestra a continuación:
   ```sql
   SELECT
      ColumnA,
      ColumnB,
      ColumnC
   FROM
      Table where the data lives
   WHERE
      Certain condition is met
   ```
   - He aquí un ejemplo de cómo aparecería en BigQuery:
   ```sql 
   SELECT
      customer_id,
      first_name,
      last_name
   FROM
      customer_data.customer_name
   WHERE
      first_name = 'Tony'
   ```
   - La consulta anterior utiliza tres comandos para localizar clientes con los first_name, 'Tony'.
      1. SELECT las columnas denominadas customer_id, first_name, y last_name
      2. FROM una tabla denominada customer_name (en un conjunto de datos denominado customer_data) (El nombre del conjunto de datos siempre va seguido de un punto y, a continuación, el nombre de la tabla)
      3. Pero sólo devuelve los datos WHERE el first_name es 'Tony'
   - La única diferencia entre esta consulta y la anterior es que se seleccionan más columnas de datos.
   - La consulta anterior sólo seleccionaba first_name mientras que esta consulta selecciona customer_id y last_name además de first_name.
   - En general, es un uso más eficiente de los recursos seleccionar sólo las columnas que se necesitan.
   - Por ejemplo, tiene sentido seleccionar más columnas si realmente va a utilizar los campos adicionales en su cláusula WHERE.
   - Si tiene varias condiciones en su cláusula WHERE , pueden escribirse así:
   ```sql
   SELECT
      ColumnA,
      ColumnB,
      ColumnC
   FROM
      Table where the data lives
   WHERE
      Condition 1
      AND Condition 2
      AND Condition 3
   ```
   - Observe que a diferencia del comando SELECT que utiliza una coma para separar campos / variables / parámetros, el comando WHERE utiliza la sentencia AND para conectar condiciones.
   - A medida que se convierta en un escritor de `query` más avanzado, hará uso de otros conectores / operadores como OR y NOT.
   - He aquí un ejemplo de BigQuery con varios campos utilizados en una cláusula WHERE:
   ```sql
   SELECT
      customer_id,
      first_name,
      last_name
   FROM
      customer_data.customer_name
   WHERE
      customer_id > 0
      AND first_name = 'Tony'
      AND last_name = 'Magnolia'
   ```
   - La consulta anterior utiliza tres comandos para localizar a los Clientes con un campo válido (mayor que 0), customer_id cuyo first_name es 'Tony' y last_name es 'Magnolia'.
      1. SELECT las columnas denominadas customer_id, first_name, y last_name
      2. FROM una tabla denominada customer_name (en un conjunto de datos denominado customer_data) (El nombre del conjunto de datos siempre va seguido de un punto y, a continuación, el nombre de la tabla)
      3. Pero sólo devuelve los datos WHERE customer_id es mayor que 0, first_name es Tony, y last_name es Magnolia.
   - Observe que una de las condiciones es una condición lógica que comprueba si customer_id es mayor que cero.
   - Si sólo hay un cliente llamado Tony Magnolia, los resultados de la consulta podrían ser:

   | customer_id | first_name | last_name |
   | -----       | ----       |  ------   | 
   | 1967        | Tony       | Magnolia  |

   - Si más de un cliente tiene el mismo nombre, los resultados de la consulta podrían ser:

   | customer_id | first_name | last_name |
   | -----       | ----       |  ------   | 
   | 1967        | Tony       | Magnolia  |
   | 7689        | Tony       | Magnolia  |

- Claves
   - Las cláusulas SELECT, FROM y WHERE son los componentes esenciales de las `query` SQL.
   - Las `query` con múltiples campos serán más sencillas después de que practique escribiendo sus propias `query` SQL más adelante en el programa.

---

## Angie: Luchas cotidianas al aprender nuevas habilidades
- Soy Angie, Gerente del Programa ​de Ingeniería en Google.
- ​Actualmente estoy trabajando en el certificado de Analítica de Datos.
- ​Antes, fui investigadora en analítica de personas.
- ​También fui lo que yo llamo una mercenaria analítica ​trabajando para un montón de empresas diferentes ​para ayudarles a dar sentido a sus datos.
- ​Cada vez que aprendo una nueva habilidad, ​me siento como si estuviera aprendiendo a hablar de nuevo.
- ​Recuerdo la primera vez que aprendí SQL, ​estaba tan frustrada porque todo el mundo a mi alrededor, ​tenía la sensación de que hablaban con fluidez, ​sabían exactamente lo que estaban haciendo.
- ​Recuerdo que luchaba con las cosas más básicas, ​como sacar los datos de la tabla o recuerdo ​que alguien me pidió que encontrara la media ​de algo y seguía obteniendo un error.

- ​Realmente se siente como si estuvieras ​aprendiendo un nuevo idioma y estuvieras ​en el nivel de un niño pequeño y ​todo el mundo a tu alrededor es como si tal vez lo hablara con fluidez.
- ​Mis padres emigraron a ​este país cuando tenían unos 30 años.
- ​Después de haber aprendido ​otro idioma y tuvieron que empezar ​de nuevo y aprender inglés.
- ​Recuerdo de niña verlos ​luchar cada día para aprender un nuevo idioma, ​para hacer cosas realmente básicas, ​como pedir ayuda en el supermercado.
- ​Recuerdo llamar a la compañía de cable cuando tenía seis años, ​hacerles preguntas sobre ​la factura porque mis padres no podían.
- ​Recuerdo lo duro que trabajaron para ​aprender este nuevo lenguaje y llegar a ser ​fluidos y cada vez que estoy aprendiendo ​un nuevo lenguaje de datos como ​SQL o R, pienso en lo duro que debe haber sido.
- ​Pienso que si ellos pueden hacer eso, yo puedo aprender SQL.
- ​Si pueden pedir ayuda para las cosas más básicas, ​puedo preguntar a los Analistas de datos que tengo al lado cómo ​escribir una sentencia SQL y ​cómo sacar datos de una tabla.
- ​Eso me ayudó mucho, ​es simplemente tener esa mentalidad ​y saber que puedo pedir ayuda.

---

## Infinitas posibilidades SQL
- Ha aprendido que una consulta SQL utiliza SELECT, FROM y WHERE para especificar los datos que debe devolver la consulta.
- Esta lectura proporciona información más detallada sobre el formato de las `query`, el uso de las condiciones de WHERE, la selección de todas las columnas de una tabla, la adición de comentarios y el uso de alias.
- Todo ello le facilitará la comprensión (y la escritura) de `query` para poner SQL en acción.
- La última sección de esta lectura ofrece un ejemplo de lo que haría un analista de datos para extraer datos de empleados para un proyecto.

- Mayúsculas, indentación y punto y coma
   - Puede escribir sus `query` SQL en minúsculas y no tendrá que preocuparse por los espacios adicionales entre palabras.
   - Sin embargo, utilizar mayúsculas y sangría puede ayudarle a leer la información más fácilmente.
   - Mantenga sus `query` ordenadas y le resultarán más fáciles de revisar o solucionar si necesita comprobarlas más adelante.
   ```sql
   SELECT field1
   FROM table
   WHERE field1 = condition;
   ```
   - Observe que la sentencia SQL mostrada anteriormente tiene un punto y coma al final.
   - El punto y coma es un terminador de sentencia y forma parte de la norma SQL-92 del Instituto Nacional Estadounidense de Estándares (ANSI), que es una sintaxis común recomendada para su adopción por todas las bases de datos SQL.
   - Sin embargo, no todas las bases de datos SQL han adoptado o aplican el punto y coma, por lo que es posible que se encuentre con algunas sentencias SQL que no estén terminadas con punto y coma
   - Si una sentencia funciona sin punto y coma, está bien.

- Condiciones WHERE
   - En la consulta mostrada anteriormente, la cláusula SELECT identifica la columna de la que desea extraer datos por su nombre, field1, y la cláusula FROM identifica la table en la que se encuentra la columna por su nombre, tabla.
   - Por último, la cláusula WHERE acota su consulta para que la base de datos le devuelva sólo los datos con una coincidencia de valor exacta o los datos que coincidan con una determinada condición que desee satisfacer.
   - Por ejemplo, si busca un cliente concreto con el apellido Chávez, la cláusula WHERE sería:
      - `WHERE field1 = 'Chavez'`
   - Sin embargo, si busca todos los clientes cuyo apellido empiece por las letras "Ch", la cláusula WHERE sería:
      - `WHERE field1 LIKE 'Ch%'`
   - Puede concluir que la cláusula LIKE es muy potente porque le permite indicar a la base de datos que busque un patrón determinado
   - El signo de porcentaje % se utiliza como comodín para hacer coincidir uno o varios caracteres.
   - En el ejemplo anterior, se devolverían tanto Chávez como Chen.
   - Tenga en cuenta que en algunas bases de datos se utiliza un asterisco * como comodín en lugar del signo de porcentaje %.

- SELECT todas las columnas
   - ¿Puede utilizar SELECT *?
   - En el ejemplo, si sustituye SELECT field1 por SELECT *, estaría seleccionando todas las columnas de la tabla en lugar de sólo la columna campo1.
   - Desde el punto de vista de la sintaxis, se trata de una sentencia SQL correcta, pero debe utilizar el asterisco * con moderación y precaución.
   - Dependiendo del número de columnas que tenga una tabla, podría estar seleccionando una enorme cantidad de datos.
   - Seleccionar demasiados datos puede hacer que una consulta se ejecute con lentitud.

- Comentarios
   - Algunas tablas no están diseñadas con convenciones de nomenclatura suficientemente descriptivas.
   - En el ejemplo, field1 era la columna correspondiente al apellido de un cliente, pero no la reconocería por el nombre.
   - Un nombre mejor habría sido algo como last_name.
   - En estos casos, puede colocar comentarios junto a su SQL para ayudarle a recordar lo que representa el nombre.
   - Los Comentarios son texto colocado entre ciertos caracteres, /* y */, o después de dos guiones --) como se muestra a continuación.
   ```sql
   SELECT
      field1 /* this is the last name column */
   FROM
      table -- this is the customer data table  
   WHERE
      field1 LIKE 'Ch%';
   ```
   - Los Comentarios también pueden añadirse fuera de una sentencia, así como dentro de una sentencia.
   - Puede utilizar esta flexibilidad para proporcionar una descripción general de lo que va a hacer, notas paso a paso sobre cómo lo consigue y por qué establece diferentes parámetros/condiciones.
   ```sql
   -- This is an important query used later to join with the accounts table 
   SELECT
         rowkey,  -- key used to join with account_id
   Info.date,  -- date is in string format YYYY-MM-DD HH:MM:SS
   Info.code  -- e.g., 'pub-###'

   FROM  Publishers
   ```
   - Cuanto más cómodo se sienta con SQL, más fácil le resultará leer y comprender las `query` de un vistazo.
   - Aun así, nunca está de más incluir comentarios en una consulta para recordar lo que intenta hacer.
   - Esto también facilita que otros entiendan su consulta si ésta se comparte.
   - A medida que sus `query` se vuelvan más y más complejas, esta práctica le ahorrará mucho tiempo y energía para entender `query` complejas que escribió hace meses o años.

- Ejemplo de consulta con comentarios
   - He aquí un ejemplo de cómo se pueden escribir comentarios en BigQuery:
   ```sql
   -- Pull basic information from the customer table
   SELECT
      customer_id, --main ID used to join with customer_addresss
      first_name, --customer's first name from loyalty program
      last_name --customer's last name
   FROM
      customer_data.customer_name
   ```
   - En el ejemplo anterior, se ha añadido un comentario antes de la sentencia SQL para explicar lo que hace la consulta.
   - Además, se ha añadido un comentario junto a cada uno de los nombres de las columnas para describir la columna y su uso.
   - Generalmente se admiten dos guiones --.
   - Por lo tanto, es mejor utilizar -- y ser coherente con él.
   - Puede utilizar # en lugar de -- en la consulta anterior, pero # no se reconoce en todas las versiones de SQL; por ejemplo, MySQL no reconoce #.
   - También puede colocar comentarios entre /* y */ si la base de datos que utiliza lo admite.
   - A medida que desarrolle sus habilidades profesionales, en función de la base de datos SQL que utilice, podrá elegir los símbolos delimitadores de comentarios que prefiera y ceñirse a ellos como estilo coherente.
   - A medida que sus `query` se vuelvan más y más complejas, la práctica de añadir comentarios útiles le ahorrará mucho tiempo y energía para comprender `query` que puede haber escrito meses o años antes. 

- Asignación de alias
   - También puede facilitarse las cosas asignando un nuevo nombre o alias a los nombres de las columnas o tablas para que le resulte más fácil trabajar con ellos (y evitar la necesidad de comentarios).
   - Esto se hace con una cláusula SQL AS.
   - En el ejemplo siguiente, se utilizan alias tanto para el nombre de una tabla como para el de una columna.
   - Dentro de la base de datos, la tabla se llama actual_table_name y la columna de esa tabla se llama actual_column_name.
   - Se les asigna el alias my_table_alias y my_column_alias, respectivamente.
   - Estos alias sólo sirven para la duración de la consulta.
   - Un alias no cambia el nombre real de una columna o tabla de la base de datos.
   - Ejemplo de consulta con alias
   ```sql
   SELECT 
      my_table_alias.actual_column_name AS my_column_alias
   FROM
      actual_table_name AS my_table_alias
   ```

- Poner SQL a trabajar como Analista de datos
   - Imagine que es usted analista de datos de una pequeña empresa y su jefe le pide algunos datos sobre sus empleados.
   - Decide escribir una consulta con SQL para obtener lo que necesita de la base de datos.
   - Quiere obtener todas las columnas: empID, firstName, lastName, jobCode y salary.
   - Como sabe que la base de datos no es tan grande, en lugar de introducir el nombre de cada columna en la cláusula SELECT, utiliza SELECT *.
   - Esto seleccionará todas las columnas de la tabla Empleado en la cláusula FROM.
   ```sql
   SELECT
      *
   FROM
      Employee
   ```
   - Ahora, puede ser más específico sobre los datos que desea de la tabla Empleados.
   - Si desea todos los datos sobre los empleados que trabajan en el código de puesto 'SFI', puede utilizar una cláusula WHERE para filtrar los datos en función de este requisito adicional.
   - En este caso, se utiliza
   ```sql
   SELECT
      *
   FROM
      Employee
   WHERE
      jobCode = 'SFI'
   ```
   - Una parte de los datos resultantes devueltos por la consulta SQL podría tener el siguiente aspecto:

   | empID | firstName | lastName | jobCode | salario |
   | ----  | -----     | -----    | ---     | ----    |
   | 0002  | Homer     | Simpson  | SFI     | 15000   |
   | 0003  | Marge     | Simpson  | SFI     | 30000   |
   | 0034  | Bart      | Simpson  | SFI     | 25000   |
   | 0067  | Lisa      | Simpson  | SFI     | 38000   |
   | 0088  | Ned       | Flandes  | SFI     | 42000   |
   | 0076  | Barney    | Gumble   | SFI     | 32000   |

   - Supongamos que observa un amplio rango salarial para el código de puesto 'SFI'.
   - Tal vez quiera marcar a todos los empleados de todos los departamentos con salarios más bajos para su gestor.
   - Como los becarios también están incluidos en la tabla y tienen sueldos inferiores a 30.000 $, quiere asegurarse de que sus resultados le dan sólo los empleados a tiempo completo con sueldos iguales o inferiores a 30.000 $.
   - En otras palabras, quiere excluir a los becarios con el código de puesto 'INT' que también ganan menos de 30.000 $.
   - La cláusula AND le permite comprobar ambas condiciones.
   - Cree una consulta SQL similar a la siguiente, donde <> significa "no es igual":
   ```sql
   SELECT
      *
   FROM
      Employee
   WHERE
      jobCode <> 'INT' 
         AND salary <= 30000;
   ```
   - Los datos resultantes de la consulta SQL podrían parecerse a los siguientes (no se devuelven los becarios con el código de puesto INT ):

   | empID | firstName | lastName | jobCode | salario |
   | ----  | -----     | -----    | ---     | ----    |
   | 0002  | Homer     | Simpson  | SFI     | 15000   |
   | 0003  | Marge     | Simpson  | SFI     | 30000   |
   | 0034  | Bart      | Simpson  | SFI     | 25000   |
   | 0108  | Edna      | Krabappel  | TUL     | 18000   |
   | 0099  | Moe       | Szyslak  | ANA     | 28000   |

   - Con un acceso rápido a este tipo de datos mediante SQL, puede proporcionar a su gerente un montón de estadísticas diferentes sobre los datos de los empleados, incluyendo si los salarios de los empleados en toda la empresa son equitativos.
   - Afortunadamente, la consulta muestra que sólo dos empleados más podrían necesitar un ajuste salarial y usted comparte los resultados con su jefe.
   - Extraer los datos, analizarlos e implementar una solución podría, en última instancia, ayudar a mejorar la satisfacción y la lealtad de los empleados.
   - Eso convierte a SQL en una herramienta bastante poderosa.

- Recursos para saber más
   - Los no suscriptores pueden acceder a estos recursos de forma gratuita, pero si un sitio limita el número de artículos gratuitos al mes y usted ya ha alcanzado su límite, marque el recurso y vuelva a él más tarde.
      - [Tutorial SQL de W3Schools](https://www.w3schools.com/sql/default.asp):
         - Si desea explorar un tutorial detallado de SQL, éste es el lugar perfecto para empezar.
         - Este tutorial incluye ejemplos interactivos que puede editar, probar y recrear.
         - Utilícelo como referencia o complete todo el tutorial para practicar el uso de SQL.
         - Clic en el botón verde Empezar a aprender SQL ahora o en el botón Siguiente  para comenzar el tutorial.
      - [Hoja de trucos SQL](https://www.sqltutorial.org/sql-cheat-sheet/):
         - Para los alumnos más avanzados, consulte este práctico recurso de 3 páginas para obtener una visión general de las funciones y fórmulas SQL adicionales.
         - Cuando haya terminado de consultar la hoja de trucos, sabrá mucho más sobre las distintas técnicas SQL y estará preparado para utilizarlas en el análisis empresarial y otras tareas.

- Puntos clave
   - Las `query` SQL utilizan SELECT, FROM y WHERE para especificar los datos que debe devolver la consulta.
   - Las mayúsculas, la indentación y el punto y coma son útiles para facilitar la lectura de las `query` SQL.
   - Además, se pueden añadir comentarios para explicar las `query` a otras personas.
   - A medida que avance en este curso, seguirá descubriendo muchas formas en las que SQL puede ser una herramienta muy poderosa para recuperar, analizar e interpretar datos.

---

## Conviértase en un genio de la visualización de Datos
- ​Su caja de herramientas de análisis de datos se está llenando.
- ​Aprender sobre hojas de cálculo y ​SQL lo llevará lejos en el mundo del análisis de datos.
- ​Hay más que aprender, por supuesto, ​y muchas más herramientas que podrás usar, ​pero tu futuro se ve prometedor.
- ​Está a punto de tener un aspecto aún más brillante, ​porque estamos aquí para hablar más sobre la visualización de datos.
- ​Te contaré un poco más sobre el papel de ​las herramientas de visualización y análisis de datos, ​y te daré la oportunidad de ver ​esas herramientas en acción más adelante en este vídeo.
- ​Tal vez recuerde que la visualización de datos ​es la representación gráfica de la información.
- ​Para muchos analistas de datos, ​es la parte más emocionante de ​su trabajo porque ​ven que su arduo trabajo da sus frutos con algo interesante.

- ​Sin mencionar que la visualización de datos ​es hermosa y útil.
- ​Me quedé boquiabierto cuando llegué a Google y ​empecé a recibir un informe de datos trimestral en ​mi correo electrónico y tenía ​una gran presentación de diapositivas en la que la ​gente contribuía con sus visualizaciones.
- ​Definitivamente fue una fuente de luz cuando ​empecé a crear mis propias visualizaciones.
- ​Si no te impresiona mi historia, ​déjame contarte sobre Florence Nightingale.
- ​¿Te suena ese nombre? ​Es responsable de gran parte de ​la filosofía de la enfermería moderna ​y, aunque no lo crea, ​también fue analista de datos.
- ​Durante la Guerra de Crimea en la década de 1850, ​miles de soldados morían todos los días, ​Nightingale quería encontrar una manera de ​reducir el número de muertes.

- ​Tras examinar los datos, ​descubrió que la mayoría de los ​soldados morían a causa de enfermedades evitables.
- ​Para convencer a los administradores de los hospitales de ​que tenían que centrarse en estas afecciones, ​creó un gráfico que muestra ​el número de muertes durante varios meses.
- ​Las secciones azules mucho más grandes de ​la visualización representan las muertes evitables.
- ​Su trabajo condujo directamente a cambios importantes en la atención a los pacientes.
- ​Hizo todo esto hace más de ​150 años sin una computadora.
- ​Una de las principales razones por las que Nightingale creó ​esta visualización fue para que ​los datos fueran más fáciles de digerir para su audiencia.
- ​Pensó que tendría más ​éxito convenciendo a la parte interesada ​utilizando imágenes en lugar de solo palabras y números.

- ​Tenía razón: las tablas llenas de datos, ​si bien son necesarias para el análisis, ​simplemente no pueden mostrar tendencias y patrones con la ​rapidez y claridad que las visualizaciones.
- ​Imagina que recibes una ​tarea que debes completar el mismo día.
- ​Reúne los datos que necesita en una tabla, ​¿podría explicar sus hallazgos usando la tabla? ​Sí, probablemente puedas, ​pero una mejor idea sería usar ​una visualización como este gráfico de barras.
- ​Algo como esto hace que ​te resulte mucho más fácil explicar rápidamente, ​y tienes la ventaja de contar con ​un gráfico atractivo para respaldar tu análisis.
- ​Como analista de datos, ​querrá crear visualizaciones que ​hagan que los datos sean fáciles de entender ​e interesantes de ver, así que preséntelos.
- ​Es posible que las partes interesadas no tengan ​mucho tiempo para dedicar a los datos, ​su trabajo consistirá en hacer que su tiempo valga la pena.

- ​Volvamos a la tabla de datos que ​creamos anteriormente en el curso.
- ​Si creaste la tuya propia para practicar, ​puedes abrirla ahora o probarla más tarde.
- ​Estos son los datos que agregamos anteriormente.
- ​Vamos a crear una visualización de los datos ​insertando un gráfico, un gráfico de barras.
- ​Puede ver que la hoja de cálculo visualizó ​los datos de nuestra tabla de ​la manera que tenía más sentido.
- ​Creó un gráfico de barras o un ​gráfico de columnas para comparar las edades de cada persona por su nombre, ​pero es posible que ya lo hayas descubierto.
- ​Esa es la belleza de la visualización, ​muestra el análisis de datos de forma rápida y clara.

- ​Podemos usar el editor de gráficos para ajustar el gráfico.
- Los ​distintos programas de hojas de cálculo pueden ​tener diferentes maneras de hacerlo, ​pero todos tienen funciones de visualización ​y formas de editar esas visualizaciones.
- ​Por ahora, veamos los gráficos sugeridos.
- ​Podemos hacer que las barras vayan horizontalmente usando un gráfico de barras.
- ​Se ve muy bien, así que cerremos el editor de Gráficos.
- ​Hay muchas opciones que considerar, ​pero por ahora lo mantendremos básico.
- ​No dudes en probar otras visualizaciones ​si practicas más adelante.

- ​Ahora, podemos ajustar nuestro gráfico para que ​toda nuestra hoja de cálculo tenga un aspecto limpio y profesional.
- ​Excelente.
- Espero que aprendas a amar la ​visualización de datos tanto como a mí.
- ​Tal vez te conviertas en un pionero de la visualización de datos, al ​igual que Florence Nightingale.
- ​Como analista de datos en ciernes, ​empezaste a llenar tu cinturón de servicios con ​valiosas herramientas que ​utilizarás durante el resto del programa.
- ​Tener ​conocimientos sobre hojas de cálculo, SQL y visualización de datos lo ayudará a convertirse en un excelente detective de datos.
- ​Podrá utilizar estas herramientas durante todo ​el proceso de análisis de datos a medida que avance.

- ​A continuación, completarás ​algunas actividades para concluir esta parte del programa.
- ​También completará una evaluación para ​comprobar su comprensión de todo lo que aprende.
- ​Esta es una gran oportunidad para ​pensar en algunas de las áreas ​que continuará explorando ​en este curso y en su carrera.
- ​Como siempre, no dudes en revisar los vídeos y ​las lecturas para recordar ciertos temas e ideas, ​incluso si ya te sientes preparado.
- ​Estás a solo unos pasos del próximo curso, ​eso es un gran progreso.
- Sigan así.
- [archivo](./resources/modulo-03/haga-de-las-hojas-de-calculo-su-amigo-v2.xlsx)

---

## Planificación de una visualización de datos
- Antes ha aprendido que la visualización de datos es la representación gráfica de la información.
- Como analista de datos, querrás crear visualizaciones que hagan que tus datos sean fáciles de entender e interesantes de ver.
- Debido a la importancia de la visualización de datos, la mayoría de las herramientas de análisis de datos (como hojas de cálculo y bases de datos) tienen un componente de visualización incorporado, mientras que otras (como Tableau) se especializan en la visualización como su principal valor añadido.
- En esta lectura, explorarás los pasos implicados en el proceso de visualización de datos y algunas de las herramientas de visualización de datos más comunes disponibles.

- Pasos para planificar una visualización de datos
   - Veamos un ejemplo de una situación real en la que un analista de datos puede necesitar crear una visualización de datos para compartirla con las partes interesadas.
   - Imagina que eres analista de datos de un distribuidor de ropa.
   - La empresa ayuda a las pequeñas tiendas de ropa a gestionar su inventario, y las ventas están en auge.
   - Un día, se entera de que su empresa se dispone a realizar una importante actualización de su sitio web.
   - Para orientar las decisiones relativas a la actualización del sitio web, se le pide que analice los datos del sitio web existente y los registros de ventas.
   - Veamos los pasos a seguir.
      - Paso 1: Explorar los datos en busca de patrones
         - En primer lugar, pide a tu jefe o al propietario de los datos acceso a los registros de ventas actuales y a los informes analíticos del sitio web.
         - Esto incluye información sobre cómo se comportan los clientes en el sitio web actual de la empresa, información básica sobre quién lo visitó, quién compró a la empresa y cuánto compró.
         - Mientras revisa los datos, observa un patrón entre quienes visitan con más frecuencia el sitio web de la empresa: geografía e importes de compra más elevados.
         - Con un análisis más profundo, esta información podría explicar por qué las ventas son tan fuertes ahora mismo en el noreste, y ayudar a su empresa a encontrar formas de hacerlas aún más fuertes a través del nuevo sitio web.
      - Paso 2: Planificar los elementos visuales
         - Ha llegado el momento de afinar los datos y presentar los resultados del análisis.
         - En este momento, tiene un montón de datos repartidos en varias tablas diferentes, lo que no es una forma ideal de compartir sus resultados con la dirección y el equipo de marketing.
         - Querrá crear una visualización de datos que explique sus conclusiones de forma rápida y eficaz a su público objetivo.
         - Como sabes que tu público está orientado a las ventas, ya sabes que la visualización de datos que utilices debe
            - Mostrar las cifras de ventas a lo largo del tiempo
            - Relacionar las ventas con la ubicación
            - Mostrar la relación entre las ventas y el uso del sitio web
            - Mostrar qué clientes impulsan el crecimiento
      - Paso 3: Cree sus imágenes
         - Ahora que ha decidido qué tipo de información y perspectivas desea mostrar, es el momento de empezar a crear las visualizaciones reales.
         - Tenga en cuenta que crear la visualización adecuada para una presentación o para compartirla con las partes interesadas es un proceso.
         - Implica probar diferentes formatos de visualización y hacer ajustes hasta que consigas lo que buscas.
         - En este caso, la mejor forma de comunicar los resultados y convertir el análisis en la historia más convincente para las partes interesadas es utilizar una combinación de distintos formatos visuales.
         - Así que puedes utilizar las funciones de gráficos integradas en tus hojas de cálculo para organizar los datos y crear tus visuales.

- Construye tu conjunto de herramientas de visualización de datos
   - Hay muchas herramientas diferentes que puedes utilizar para la visualización de datos.
      - Puedes utilizar las herramientas de visualización de tu hoja de cálculo para crear visualizaciones sencillas, como gráficos de líneas y barras.
      - Puedes utilizar herramientas más avanzadas, como Tableau, que te permiten integrar los datos en visualizaciones de tipo cuadro de mando.
      - Si trabajas con el lenguaje de programación R, puedes utilizar las herramientas de visualización de RStudio.
   - La elección de la visualización dependerá de varios factores, como el tamaño de los datos o el proceso utilizado para analizarlos (hoja de cálculo, bases de datos/consultas o lenguajes de programación).
   - Por ahora, considera sólo lo básico.

- Hojas de cálculo (Microsoft Excel o Google Sheets)
   - En nuestro ejemplo, los cuadros y gráficos incorporados en las hojas de cálculo hicieron que el proceso de creación de elementos visuales fuera rápido y sencillo.
   - Las hojas de cálculo son estupendas para crear visualizaciones sencillas, como gráficos de barras y de tarta, e incluso ofrecen algunas visualizaciones avanzadas, como mapas y diagramas de cascada y de embudo (que se muestran en las siguientes figuras).
   - Pero a veces se necesita una herramienta más potente para dar vida a los datos.
   - Tableau y RStudio son dos ejemplos de plataformas ampliamente utilizadas que pueden ayudarle a planificar, crear y presentar visualizaciones de datos eficaces y convincentes.

- Software de visualización (Tableau)
   - Tableau es una popular herramienta de visualización de datos que le permite extraer datos de casi cualquier sistema y convertirlos en atractivas visualizaciones o perspectivas procesables.
   - La plataforma ofrece las mejores prácticas visuales integradas, lo que hace que analizar y compartir datos sea rápido, fácil y (lo más importante) útil.
   - Tableau funciona bien con una amplia variedad de datos e incluye un panel interactivo que le permite a usted y a las partes interesadas hacer clic para explorar los datos de forma interactiva.
   - Puede empezar a explorar Tableau desde los recursos de [vídeos de instrucciones](https://public.tableau.com/en-us/s/resources).
   - Tableau Public es gratuito, fácil de usar y está repleto de información útil.
   - La página de recursos es una ventanilla única para vídeos de instrucciones, ejemplos y conjuntos de datos con los que puede practicar.
   - Para explorar lo que otros analistas de datos están compartiendo en Tableau, visite la página [Viz of the Day](https://public.tableau.com/en-us/gallery/?tab=viz-of-the-day&type=viz-of-the-day), donde encontrará hermosos visuales que van desde una visión general de los [Faros de Grecia](https://public.tableau.com/app/profile/george.koursaros/viz/LighthousesofGreece/Lighthouses) hasta [Quién habla en las películas populares](https://public.tableau.com/app/profile/bo.mccready8742/viz/WordDataWorking/WhoIsTalking).

- Lenguaje de programación (Python y R)
   - Muchos analistas de datos trabajan con un lenguaje de programación como Python y R para crear visualizaciones de datos.
   - Python tiene potentes capacidades de visualización de datos gracias a su amplio ecosistema de bibliotecas de código abierto.
   - La base es la biblioteca Matplotlib, que proporciona un alto grado de flexibilidad para crear gráficos estáticos, animados e interactivos.
   - Seaborn está construido sobre Matplotlib y está diseñado para producir rápidamente gráficos estadísticos atractivos e informativos.
   - Seaborn crea automáticamente visuales de aspecto pulido y profesional, que permiten observar patrones y relaciones en los datos con sólo unas pocas líneas de código.
   - La biblioteca Plotly es útil para crear visuales interactivos como gráficos y cuadros de mando para sitios web.
   - Interactivo significa que un usuario puede hacer clic en los puntos de datos, ampliarlos o pasar el ratón sobre ellos para explorar los detalles.
   - Echa un vistazo a la [Python Graph Gallery](https://python-graph-gallery.com/) para descubrir una amplia colección de visualizaciones hechas con Python.

>[!NOTE] Una biblioteca de Python es una colección de código preescrito diseñado para ayudar con tareas específicas, como el análisis de datos o el aprendizaje automático. Aprenderás más sobre bibliotecas en un curso posterior.

   - El lenguaje de programación R también dispone de potentes herramientas de visualización.
   - La mayoría de las personas que trabajan con R acaban utilizando también Posit (antes RStudio), un entorno de desarrollo integrado (IDE), para sus necesidades de visualización de datos.
   - Visita su página web para saber más sobre [Posit](https://posit.co/products/open-source/rstudio/?sid=1).

- Puntos clave
   - Los mejores analistas de datos utilizan muchas herramientas y métodos diferentes para visualizar y compartir sus datos.
   - A medida que continúe aprendiendo más sobre la visualización de datos a lo largo de este curso, asegúrese de mantener la curiosidad, investigar diferentes opciones y probar continuamente nuevos programas y plataformas para ayudarle a sacar el máximo provecho de sus datos.

---

## Lilah El poder de una visualización
- Mi nombre es Lilah Jones y formo parte de nuestro equipo de nube.
- ​Tengo la oportunidad de dirigir un equipo de personas increíbles que se centran en ayudar a ​los clientes a llegar a la nube.
- ​Datos visualizables, esa es una palabra larga y ​que también puede hacer que tus ojos se pongan vidriosos.
- ​Pero me pregunto si, cuando eras pequeño y estabas con tus padres, ​tal vez ellos tenían una rutina para dormir o tal vez tienes hijos, ​estás haciendo una rutina para dormir con ellos.
- ​Muy pocas veces vas a acudir a esos niños con un montón de datos y ​cifras antes de que se vayan a dormir.
- ​Pero apuesto a que probablemente les estás contando una historia, les estás mostrando imágenes, ​sé que siempre me han gustado los cómics, las imágenes cuentan una historia.
- ​Las visualizaciones de datos son imágenes, son una forma maravillosa de tomar ​ideas muy básicas sobre datos y puntos de datos y hacerlas realidad.

- ​Puedes hacer diferentes tipos de combinaciones de visualizaciones, ​pero las que son interactivas, vaya, son enormes.
- ​¿Te imaginas ser el ejecutivo de una organización y ​tratar de averiguar cómo deberíamos abrir otro sitio en Bangkok? ​¿Tiene sentido? Y el hecho de que podamos entrar y decir: ​He aquí por qué tiene sentido tener excelentes visualizaciones de datos que respalden todos ​nuestros puntos de vista, hace que sea una obviedad.
- ​Curiosamente, sí recuerdo la primera vez que me encontré con una ​visualización increíble, fue en mi vida personal.
- ​Cambié mi software de presupuestación de un proveedor a otro, y ​el proveedor al que me cambié se centró realmente en que cada dólar tuviera un trabajo y en ​asegurarse de que se presupueste, cada dólar.
- ​Ofrecían visualizaciones que cambiaban, según la entrada que se le ​añadiera y, en realidad, eso cambió por completo mi perspectiva, todo el asunto.
- ​Por lo tanto, tener los datos es como tener la hoja de respuestas para una prueba, en ​realidad solo te permite saber que vas a tomar buenas decisiones porque está ​respaldada por datos.