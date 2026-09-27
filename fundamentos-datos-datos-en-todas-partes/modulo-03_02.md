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