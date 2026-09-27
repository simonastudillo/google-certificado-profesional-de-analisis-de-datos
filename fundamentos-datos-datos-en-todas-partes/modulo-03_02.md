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