# Grandes conjuntos de datos en SQL

## Conozca BigQuery, incluidas las opciones de sandbox y facturación
- ​Hola y bienvenido de nuevo.
- ​A lo largo de este curso, ha visto cómo Big Consulta se puede ​utilizar para ver y analizar datos de montones de fuentes.
- ​Ahora vamos a explorar ​las diferentes cuentas que ofrece Big Consulta, ​para que sepa cómo elegir la adecuada ​para sus necesidades y cómo puede acceder a ellas.
- ​Big Consulta se las ofrece sin coste alguno.
- ​Hay opciones de pago disponibles, ​pero no las necesitaremos para las actividades de este curso.
- ​En su lugar, vamos a hablar de dos tipos de cuenta, ​de tipo sandbox y de prueba gratuita.
- ​Una cuenta sandbox está disponible sin coste alguno ​y cualquier persona con una cuenta de Google puede iniciar sesión y utilizarla.

- ​Hay un par de limitaciones en este tipo de cuenta.
- ​Por ejemplo, tiene un máximo de 12 proyectos a la vez.
- ​Esto significa que si quiere hacer un decimotercer proyecto, ​tendrá que eliminar uno de sus 12 originales.
- ​Tampoco le permite insertar nuevos registros en ​una base de datos ni actualizar ​los valores de campo de los registros existentes.
- ​Estas operaciones de Lenguaje de Manipulación de datos o DML ​no se admiten en el sandbox.
- ​Sin embargo, no necesitará hacer esto en las actividades del curso, ​Puede leer más sobre las limitaciones de ​una cuenta sandbox en la Documentación de Big Consulta.
- ​Este es el tipo de cuenta que ​utilizaremos para la mayoría de nuestras actividades.

- ​Pero antes de eso, deberíamos hablar de ​la otra forma de utilizar Big Consulta sin cargos, ​la prueba gratuita de Google Nube.
- ​La prueba gratuita le da acceso a más de lo que ofrece ​Big Consulta con menos limitaciones generales.
- ​La prueba gratuita ofrece 300 dólares en crédito ​para su uso en Google Nube durante los primeros 90 días.
- ​No se acercará a ese límite de gasto si ​sólo utiliza la consola de Big Consulta para practicar consultas SQL.
- ​Una vez gastados los 300 dólares de crédito o transcurridos 90 días, ​su prueba gratuita caducará ​y deberá ​elegir personalmente la actualización a una cuenta de pago ​para seguir trabajando en Google Nube.
- ​Su método de pago no se ​cargará automáticamente una vez finalizada su prueba gratuita.
- ​La prueba gratuita sí requiere que ​configure una opción de pago con Google Nube, ​pero a menos que opte por ​una actualización de cuenta, no se le cobrará.

- ​Sin embargo, sí requiere que introduzca un tipo de pago, ​por lo que entendemos si no ​se siente cómodo con esta opción.
- ​Esta es una de las razones por las que existe la cuenta sandbox de Big Consulta, ​para que no tenga que introducir ninguna información de pago.
- ​Con cualquiera de los dos tipos de cuenta, ​puede pasar a una cuenta de pago en ​cualquier momento y conservar todos sus proyectos existentes.
- ​Si crea una cuenta de prueba gratuita, ​pero decide no pasar a ​una cuenta de pago cuando finalice su periodo de prueba, ​puede crear una cuenta sandbox gratuita en ese momento.

---

## Configure su cuenta BigQuery
- Como ha estado aprendiendo, BigQuery es una base de datos que puede utilizar para acceder, explorar y analizar datos de muchas fuentes.
- Ahora, empezará a utilizar BigQuery, que le ayudará a adquirir conocimientos de SQL escribiendo comandos y solucionando problemas.
- Esta lectura le guiará a través del proceso de creación de su propia cuenta BigQuery.
- Nota: Trabajar con BigQuery no es un requisito de este Programa. Al final de esta lectura también se proporcionan recursos adicionales para otras plataformas de bases de datos SQL por si decide utilizarlas en su lugar. 

- Opciones de cuenta BigQuery
   - BigQuery ofrece una variedad de niveles de cuenta para satisfacer las distintas necesidades de los usuarios y tiene dos puntos de entrada gratuitos, una cuenta sandbox y una cuenta de prueba gratuita.
   - Estas opciones le permiten explorar el Programa antes de seleccionar la opción que mejor se adapte a sus necesidades.
   - Una cuenta sandbox le permite practicar la escritura de consultas y explorar conjuntos de datos públicos de forma gratuita, pero tiene cuotas y límites, así como algunas restricciones adicionales.
   - Si prefiere utilizar BigQuery con los límites estándar, puede configurar en su lugar una cuenta de prueba gratuita.
   - La prueba gratuita es un periodo de prueba previo al pago de una suscripción.
   - En este caso, no hay cargo automático, pero se le pedirá información sobre el pago cuando cree la cuenta. 
   - Esta lectura proporciona instrucciones para configurar cualquiera de los dos tipos de cuenta.
   - Un primer paso eficaz es comenzar con una cuenta "sandbox" y Switch a una cuenta de prueba gratuita cuando sea necesario para ejecutar el SQL presentado próximos cursos. 

- Cuenta de caja de arena
   - La cuenta de caja de arena está disponible sin coste alguno y cualquiera que disponga de una cuenta de Google puede utilizarla.
   - Sin embargo, tiene algunas limitaciones.
   - Por ejemplo, está limitada a un máximo de 12 proyectos a la vez.
   - Esto significa que, para crear un decimotercer proyecto, tendrá que eliminar uno de sus 12 proyectos existentes.
   - Además, la cuenta sandbox no admite todas las operaciones que realizará en este programa.
   - Por ejemplo, hay límites en la cantidad de datos que puede procesar y no puede insertar nuevos registros en una base de datos ni actualizar los valores de los registros existentes.
   - Sin embargo, una cuenta de caja de arena es perfecta para la mayoría de las actividades del programa, incluidas todas las de este curso.
   - Además, puede convertir su cuenta de caja de arena en una cuenta de prueba gratuita en cualquier momento.

- Configure su cuenta del cajón de arena
   - Para configurar una cuenta sandbox:
      1. Visite la página de [Documentación del sandbox de BigQuery](https://cloud.google.com/bigquery/docs/sandbox#limits).
      2. Regístrese en su cuenta de Google preferida seleccionando el icono de perfil en la barra de menús de BigQuery.
      3. Seleccione el botón Ir a BigQuery en la página de Documentación.
      4. Se le pedirá que seleccione su país y que lea el acuerdo de términos de servicio.
      5. Esto le llevará al espacio de trabajo SQL, donde realizará las próximas actividades. Por defecto, BigQuery crea un proyecto para usted. 
   - Después de configurar su cuenta, el nombre del proyecto aparecerá en el banner de su consola BigQuery. 

- Prueba gratuita 
   - Si desea explorar más de las capacidades de BigQuery con menos limitaciones, considere la prueba gratuita de Google Nube.
   - Le proporciona 300 dólares de crédito para el uso de Google Nube durante los primeros 90 días.
   - Si utiliza BigQuery principalmente para consultas SQL, es poco probable que se acerque a este límite de gasto.
   - Una vez agotado el crédito de 300 $ o transcurridos 90 días, su prueba gratuita caducará y sólo podrá utilizar esta cuenta si paga por ello.
   - Google no realizará ningún cargo automático en su Método de pago cuando finalice la prueba.
   - Sin embargo, tendrá que configurar una opción de pago con Google Nube.
   - Esto significa que tendrá que introducir su información financiera.
   - Tenga la seguridad de que no se le cobrará a menos que opte conscientemente por cambiar a una cuenta de pago.
   - Si no se siente cómodo proporcionando información de pago, no se preocupe; en su lugar, puede utilizar la cuenta "sandbox" de BigQuery.

- Configure su prueba gratuita 
   1. Vaya a la página de [BigQuery](https://cloud.google.com/bigquery).
   2. Seleccione Probar BigQuery gratis.
   3. Inicie sesión con su correo electrónico de Google o cree una cuenta gratuita si no dispone de ella. Clic aquí para crear una cuenta.
   4. Seleccione su país, una descripción de su organización o necesidades, y la casilla de verificación para aceptar los términos de servicio, A continuación, seleccione CONTINUAR.
   5. Introduzca sus datos de facturación y seleccione COMENZAR MI PRUEBA GRATUITA.
   6. Después de configurar su cuenta, su primer proyecto, titulado Mi primer proyecto, aparecerá en el banner.

- Transferencia entre cuentas BigQuery
   - Con una cuenta sandbox o de prueba gratuita, tiene la flexibilidad de pasar a una cuenta de pago en cualquier momento.
   - Si actualiza, todos sus proyectos existentes se conservarán y se transferirán a su nueva cuenta.
   - Si empezó con una cuenta de prueba gratuita, pero decide no actualizarla cuando finalice, puede cambiar a una cuenta sandbox.
   - Sin embargo, tenga en cuenta que los proyectos de su cuenta de prueba no se transferirán a su caja de arena.
   - Esencialmente, crear un sandbox es como empezar de cero.

- Empezar con otras bases de datos (si no utiliza BigQuery)
   - Es más fácil seguir las actividades del curso si utiliza BigQuery, pero puede utilizar otras plataformas SQL, si lo prefiere.
   - Si decide practicar consultas SQL en otras plataformas de bases de datos, aquí tiene algunos recursos para empezar:
      - [Primeros pasos con MySQL](https://dev.mysql.com/doc/mysql-getting-started/en/)
      - [Primeros pasos con Microsoft SQL Server](https://docs.microsoft.com/en-us/sql/relational-databases/tutorial-getting-started-with-the-database-engine?view=sql-server-ver15)
      - [Primeros pasos con PostgreSQL](https://www.postgresql.org/docs/10/tutorial-start.html)
      - [Primeros pasos con SQLite](https://www.sqlite.org/quickstart.html)

- Puntos clave
   - BigQuery ofrece múltiples opciones de cuenta. Tenga en cuenta lo siguiente cuando elija un tipo de cuenta:
      - Niveles de cuenta: BigQuery ofrece varios niveles de cuenta para satisfacer una amplia gama de requisitos de los usuarios. Tanto si empieza con una cuenta sandbox como si explora una cuenta de pago con la opción de prueba gratuita, BigQuery le ofrece flexibilidad para elegir la opción que mejor se adapte a sus necesidades y presupuesto.
      - Limitaciones del espacio aislado: Aunque una cuenta sandbox es un gran punto de partida, viene con algunas limitaciones, como un tope en el número de proyectos y restricciones en las operaciones de manipulación de datos como insertar o actualizar registros, que encontrará más adelante en este Programa. Sea consciente de estas limitaciones si decide trabajar en este curso utilizando una cuenta sandbox.
      - Fácil configuración y actualizaciones: Empezar con cualquier tipo de cuenta BigQuery es rápido y sencillo. Y si sus necesidades evolucionan, tiene la flexibilidad de modificar el estado de su cuenta en cualquier momento. Además, los proyectos pueden conservarse incluso cuando se pasa de un tipo de cuenta a otro.
   - ¡Elija el tipo de cuenta BigQuery adecuado a sus necesidades específicas y adáptese a medida que cambien sus Requisitos!

---

## Comenzar con BigQuery
- BigQuery es un almacén de datos en Google Cloud Platform que se utiliza para consultar y filtrar grandes conjuntos de datos, agregar resultados y realizar operaciones complejas.
- A lo largo de este programa, vas a utilizar BigQuery para practicar tus habilidades de SQL y recopilar, preparar y analizar datos.
- En este punto, usted ha configurado su propia cuenta.
- Ahora, explora algunos de los elementos importantes del espacio de trabajo SQL.
- Esto lo preparará para las próximas actividades en las que utilizará BigQuery.
- Tenga en cuenta que BigQuery actualiza su interfaz con frecuencia, por lo que su consola puede ser ligeramente diferente de lo que se describe en esta lectura.
- No pasa nada; ¡utiliza tus habilidades de resolución de problemas para encontrar lo que necesitas!

- Iniciar sesión en BigQuery
   - Cuando inicie sesión en BigQuery a través de la Página de destino, se abrirá automáticamente el espacio de su proyecto.
   - Se trata de una visión general de alto nivel de su proyecto, incluida la información del proyecto y los recursos que se están utilizando actualmente.
   - FROM aquí, usted puede comprobar su actividad reciente.
   - Navegue hasta el BigQuery Studio de su proyecto seleccionando BigQuery en el menú de navegación y BigQuery Studio en el menú desplegable.

- Componentes de BigQuery Studio
   - Una vez que haya navegado a BigQuery desde el espacio del proyecto, la mayoría de los componentes principales de la consola BigQuery estarán presentes: el panel de navegación , el panel del explorador y el espacio de trabajo SQL.

- Panel de navegación
   - En la página de la consola, encuentra el panel de Navegación .
   - Así es como se navega desde el espacio del proyecto a la herramienta BigQuery.
   - Este menú también contiene una lista de otras herramientas de datos de Google Cloud Project (GCP).
   - Durante este programa, te centrarás en BigQuery, pero es útil comprender que GCP cuenta con una colección de herramientas conectadas que los profesionales de datos utilizan a diario.

- El panel Explorador
   - El panel Explorador enumera sus proyectos actuales y los proyectos destacados que haya añadido a su consola.
   - También es donde encontrará el botón + AÑADIR, que puede utilizar para añadir conjuntos de datos.
   - Este botón abre el cuadro de diálogo Añadir que le permite abrir o importar diversos conjuntos de datos.

- Añadir conjuntos de datos públicos
   - BigQuery ofrece diversos conjuntos de datos públicos del Programa de conjuntos de datos públicos de Google Cloud.
   - Desplácese por el cuadro de diálogo Añadir hasta la opción Conjuntos de datos públicos.
   - Seleccione Conjuntos de datos públicos.
   - Accederá al mercado de conjuntos de datos públicos, donde podrá buscar y seleccionar conjuntos de datos públicos para añadirlos a su consola BigQuery.
   - Por ejemplo, busque el conjunto de datos "noaa lightning" en la barra de búsqueda del Mercado.
   - Cuando busque este conjunto de datos, encontrará los datos sobre rayos nube-tierra de la NOAA.
   - Seleccione el conjunto de datos para leer su descripción.
   - Seleccione Ver conjunto de datos para crear una ficha con la información del conjunto de datos dentro del espacio de trabajo de SQL.

- Iniciar y examinar conjuntos de datos públicos
   - Ha añadido el conjunto de datos público noaa_lightning a su espacio de trabajo BigQuery, por lo que el panel Explorador muestra el conjunto de datos noaa_lightning, junto con la lista de otros conjuntos de datos públicos.
   - Estos conjuntos de datos están anidados en bigquery-public-data.
   - Inicie bigquery-public-data navegando hasta la parte superior del panel Explorador y seleccionando la estrella junto a bigquery-public-data.
   - Si selecciona bigquery-public-data podrá buscar y añadir conjuntos de datos públicos desplazándose por el panel del Explorador o buscándolos en la barra de búsqueda del Explorador .
   - Por ejemplo, es posible que desee seleccionar otro conjunto de datos públicos. Si selecciona el segundo conjunto de datos, "austin_311", se ampliará para mostrar la tabla almacenada en él, "311_service_requests"
   - Al seleccionar una tabla, su información se muestra en el área de trabajo de SQL. Seleccione la tabla 311_service_requests para examinar varias pestañas que la describen, entre las que se incluyen:
      - Esquema, que muestra los nombres de las columnas del conjunto de datos
      - Detalles, que contiene metadatos adicionales, como la fecha de creación del conjunto de datos
      - Vista previa, que muestra las primeras filas del conjunto de datos
   - Además, puede seleccionar el botón Consulta de la barra de menús del Área de trabajo SQL para consultar esta tabla.

- El Espacio de Trabajo SQL
   - El último panel de menú en su consola es el Espacio de Trabajo SQL.
   - Aquí es donde escribirá y ejecutará las consultas en BigQuery.
   - El espacio de trabajo SQL también le da acceso a su historial personal y de proyectos, que almacena un registro A de las consultas que ha ejecutado.
   - Esto puede ser útil si desea volver a una consulta para ejecutarla de nuevo o utilizar parte de ella en otra consulta.

- Cargue sus datos
   - Además de ofrecer acceso a conjuntos de datos públicos, BigQuery también te permite cargar tus propios datos directamente en tu espacio de trabajo.
   - Acceda a esta función abriendo de nuevo el menú + AÑADIR o haciendo clic en los tres puntos verticales junto al nombre de su proyecto en el panel del Explorador.
   - Esto le dará la opción de crear su propio conjunto de datos y cargar sus propias tablas.
   - Tendrá la oportunidad de cargar sus propios datos en una próxima actividad para practicar el uso de esta función.
   - En BigQuery también encontrarás potentes herramientas de IA que te ayudarán con tu código, como Gemini Cloud Assist y la herramienta de generación de SQL.
   - Estas herramientas funcionan como asistentes que pueden ayudar a analizar el código y encontrar errores, sugerir modificaciones y también interactuar de forma conversacional para responder a muchas otras preguntas, ya sean técnicas o más conceptuales.
   - Para activar Gemini Cloud Assist, busque el icono Gemini en la esquina superior derecha de la consola BigQuery para activar un panel Gemini Cloud Assist.
   - Aquí, puede consultar Gemini utilizando lenguaje natural.
   - Para utilizar la herramienta de generación SQL dentro del propio editor SQL, localice el icono de la varita mágica en la esquina superior izquierda de la ventana de consulta SQL.
   - Al hacer clic aquí se abrirá una ventana en la que podrá pedir a Gemini que genere consultas SQL para sus datos.
   * Aunque funciones como la generación de SQL impulsada por IA, la finalización de código y el conocimiento de los datos dentro de BigQuery pueden acelerar su flujo de trabajo, recuerde que esta tecnología aún está evolucionando.
   - Es posible que las sugerencias, el código o las explicaciones proporcionadas no siempre sean perfectamente precisas, óptimas o seguras.
   - Revise y valide siempre cualquier resultado generado por IA antes de ejecutar consultas o confiar en la información.
   - Trate la ayuda de la IA como un copiloto útil, pero mantenga la supervisión y la responsabilidad de sus consultas y análisis finales.
   - Para obtener más información sobre estas herramientas y guías detalladas, consulte las páginas siguientes:
      - [Visión general de Gemini en BigQuery](https://cloud.google.com/gemini/docs/bigquery/overview)
      - [Escribir consultas con la ayuda de Gemini](https://cloud.google.com/bigquery/docs/write-sql-gemini)

- Puntos clave
   - El espacio de trabajo SQL de BigQuery le permite buscar conjuntos de datos públicos, ejecutar consultas SQL e incluso cargar sus propios datos para analizarlos.
   - Tanto si trabaja con conjuntos de datos públicos, como si ejecuta consultas SQL o carga sus propios datos, el espacio de trabajo SQL de BigQuery ofrece una serie de funciones que le permitirán realizar todo tipo de tareas de análisis de datos.
   - A lo largo de este programa, utilizará BigQuery para practicar sus habilidades SQL, por lo que estar familiarizado con los principales componentes de su consola BigQuery le ayudará a navegar por ella con eficacia en el futuro

---

## Paso a paso: BigQuery en acción
- Esta lectura le proporciona los pasos que el instructor realiza en el siguiente vídeo, BigQuery en acción.
- El vídeo se centra en cómo crear una consulta para ver una pequeña sección de datos de un gran conjunto de datos.
- Mantenga esta guía abierta mientras ve el vídeo.
- Puede servir como referencia útil si necesita contexto adicional o aclaración mientras sigue los pasos del vídeo.
- No se trata de una actividad calificada, pero puedes completar estos pasos para practicar las habilidades demostradas en el vídeo.

- Lo que necesitas
   - Para seguir los ejemplos de este vídeo, inicie sesión en su cuenta de BigQuery y siga las instrucciones para iniciar bigquery-public-data en la sección
   - El panel del explorador de la lectura anterior, Introducción a BigQuery. 

- Ejemplo 1: Vista previa de una sección desde un visor de tablas
   - Una base de datos es una colección de datos almacenados en un sistema informático.
   - Lenguajes de consulta como SQL permiten la comunicación entre las bases de datos y los analistas de datos.
   - Antes ha descubierto que una base de datos relacional se compone de varias tablas que pueden unirse para crear relaciones.
   - Las Claves primaria y foránea sirven como representaciones de estas relaciones.
   - Para extraer datos de estas tablas, los analistas de datos utilizan consultas.
   - Para saber más al respecto, explore BigQuery en acción:
      1. Inicie sesión en [BigQuery](https://console.cloud.google.com/bigquery) y vaya a su consola.
         - Debería encontrar abierta la Página de destino ¡Bienvenido a su espacio de trabajo SQL!
         - Seleccione COMPONER UNA NUEVA CONSULTA en la consola de BigQuery.
         - Asegúrese de que no hay pestañas abiertas para que se muestre todo el espacio de trabajo, incluido el panel Explorador.
      2. Introduzca techo solar en la barra de búsqueda.
         - En los resultados de la búsqueda, expanda sunroof_solar y seleccione el conjunto de datos solar_potential_by_postal_code.
      3. Observe la pestaña Esquema del panel Explorador para explorar los campos de la tabla. 
      4. Seleccione la pestaña Vista previa para ver las regiones, los estados, la luz solar anual, etc. 

- Ejemplo 2: Escribir una consulta
   - Para ver el conjunto de datos completo, tendrá que escribir una consulta.
      1. El primer paso es encontrar la ruta completa y correcta a la tabla con la que desea trabajar.
         - Seleccione las elipses (tres puntos verticales) junto al conjunto de datos solar_potential_by_postal_code y, a continuación, seleccione Consultar.
         - Aparecerá una nueva pestaña en la pantalla.
         - Seleccione la pestaña.
         - La ruta a la tabla debe estar escrita dentro de dos puntos. 
      2. Seleccione la ruta completa resaltando el texto que incluye los puntos y cópielo.
         - (Nota: También puede obtener la ruta completa al proyecto, base de datos y tabla directamente haciendo clic en las elipses junto al nombre de la tabla en el panel Explorador de la izquierda y seleccionando Copiar ID)
      3. Ahora, haga clic en el signo más para crear una nueva consulta.
         - Observe que BigQuery no genera automáticamente una sentencia SELECT en esta ventana.
         - Introduzca SELECT  y añada un espacio después.
      4. Ponga un asterisco * después de SELECT para indicar que desea devolver todo el conjunto de datos.
         - El asterisco indica a la base de datos que debe incluir todas las columnas.
         - Sin este método abreviado, tendría que introducir manualmente todos los nombres de las columnas
      5. A continuación, pulse la tecla Intro/Retorno e introduzca FROM  en la segunda línea. FROM indica de dónde proceden los datos. Después de FROM, añade otro espacio.
      6. Pega la ruta a la tabla que has copiado antes. Se leerá `bigquery-public-data.sunroof_solar.solar_potential_by_postal_code`
      7. Ejecuta la consulta seleccionando el botón EJECUTAR .
   - Importante
      - Muchas de las bases de datos públicas en BigQuery son registros vivos y, como tales, se actualizan periódicamente con nuevos datos.
      - A lo largo de este curso (y de otros de este programa de certificación), si sus resultados difieren de los que encuentra en los vídeos o capturas de pantalla, es muy probable que se deba a una actualización de los datos.
      - Puede comprobar cuándo se ha actualizado una tabla seleccionándola en el panel Explorador y haciendo clic en Detalles.
      - Encontrará la fecha de creación de la tabla, cuándo se modificó por última vez, así como otra información útil. 

- Ejemplo 3: Utilizar SQL para ver un dato
   - Si el proyecto no requiere que se completen todos los campos, puede utilizar SQL para ver uno o varios datos concretos.
   - Para ello, especifique un determinado nombre de columna en la consulta. 
      1. Por ejemplo, puede que sólo necesite datos de Pensilvania. Empezarías la consulta de la misma forma que en los ejemplos anteriores: Haga clic en el signo más, introduzca SELECT, añada un espacio, un asterisco (*) y, a continuación, pulse Intro/Retorno.
      2. Introduzca FROM  y, a continuación, pegue `bigquery-public-data.sunroof_solar.solar_potential_by_postal_code`. Pulsa Intro/Retorno.
      3. Esta vez, añada WHERE. Estará en la misma línea que la sentencia FROM. Añada un espacio e introduzca state_name con un espacio antes del estado y un espacio después del nombre. state_name es un nombre de columna de la tabla.
      4. Como sólo quieres datos de Pennsylvania, añade = y 'Pennsylvania' en la misma línea que state_name. En SQL, las comillas simples representan el principio y el final de una cadena.
      5. Ejecute la consulta con el botón EJECUTAR .
      6. Revise los datos sobre el potencial solar de Pensilvania. Desplácese por los resultados de la consulta.
   - Tenga en cuenta que las consultas SQL pueden escribirse de muchas formas diferentes y seguir devolviendo los mismos resultados.
   - Puede que descubras otras formas de escribir estas consultas

---

## BigQuery en acción
- ​Ha aprendido cómo la clasificación y el filtrado de datos en ​las hojas de cálculo ayudan a ​los analistas de datos a personalizar la información.
- La ​personalización de los datos hace que sean más significativos y ​fáciles de entender, analizar y visualizar.
- ​También descubriste que algunas hojas de cálculo ​pueden ser extremadamente largas y complejas.
- ​Saber cómo concentrarse en los datos exactos que necesita y dejar de ​lado el resto le ayuda a centrarse en el análisis.
- ​Esto también es válido para las bases de datos.
- ​A veces, un conjunto de datos es demasiado grande ​para descargarlo o no cabe en una hoja de cálculo, ​por lo que un analista de datos utilizará SQL para crear una consulta a ​fin de ver los datos específicos ​que desea del conjunto más grande.
- ​Hemos aprendido que una base de datos ​es una colección de datos almacenados en ​un sistema de computadora y que ​SQL significa Lenguaje de Consulta Estructurada.

- ​Los analistas de datos utilizan lenguajes de consulta ​para comunicarse con la base de datos.
- ​En un vídeo anterior, también ​aprendió que una base de datos relacional ​contiene una serie de tablas que ​se pueden conectar a relaciones extranjeras.
- ​Estas relaciones se representan ​mediante claves principales y externas.
- ​Los analistas de datos escriben consultas ​para obtener datos de estas tablas.
- ​Vamos a ver cómo funciona esto.
- ​Empezaremos con nuestro Visor de Tablas.
- ​Aquí podemos ver qué conjuntos de datos públicos están disponibles.

- ​Revisaremos los datos antes de empezar a usarlos ​para hacernos una idea de qué se ​trata y asegurarnos de que están limpios.
- ​Algunos visores de tablas permiten previsualizar ​algunas filas incluso antes de escribir una consulta.
- ​Esto es útil si quieres echar un vistazo rápido ​para asegurarte de que el conjunto de datos será el adecuado para tu proyecto.
- ​Para mostrarle cómo funciona esto, ​veamos un conjunto de datos de muestra.
- ​Esta muestra la cantidad de luz solar que llega a los tejados en un año.
- ​Esto sería muy ​útil para un analista de datos que trabaje en ​un proyecto de energía solar, por ejemplo.
- ​Empezaremos por obtener una vista previa del conjunto de datos.

- ​Luego, seleccionaremos un subconjunto de estos datos, ​donde encontraremos regiones, ​estados, luz solar anual y más.
- ​Ahora, para ver todo el conjunto de datos, escribamos una consulta.
- ​El primer paso es averiguar ​el nombre completo y correcto del conjunto de datos.
- ​Para ello, seleccione el conjunto de datos, el ​potencial solar por código postal y seleccione la tabla de consulta.
- ​El nombre del conjunto de datos se ​muestra dentro de las dos comillas invertidas.
- ​Esto nos ayuda a leer la consulta con mayor facilidad.
- En ​este caso, también podemos eliminar las comillas invertidas y nuestra consulta seguirá ejecutándose.

- ​Las palabras que aparecen antes del punto representan el ​nombre de la base de datos y ​las palabras que aparecen después del punto representan el nombre de la tabla.
- ​Vamos a seleccionar y copiar ​el nombre del conjunto de datos ahora porque lo necesitaremos en un segundo.
- ​Ahora haremos clic en el signo más para crear una nueva consulta.
- ​La mayoría de las consultas comienzan con la palabra ​seleccionar y luego agregamos un espacio.
- ​Como queremos ver todo el conjunto de datos, ​pondremos un asterisco a continuación.
- ​El asterisco dice que queremos incluir todas las columnas.
- ​Este es un excelente acceso directo porque sin él, ​tendríamos que escribir todos los nombres de campo.

- ​A continuación, presionaremos «Return» y escribiremos FROM.
- ​FROM hace exactamente lo que ​parece, indica de dónde provienen los datos.
- ​Después de eso, agregaremos otro espacio.
- ​Ahora pegamos el nombre del conjunto de datos que copiamos ​anteriormente y finalmente ejecutamos la consulta.
- ​Ahora podemos inspeccionar cuidadosamente ​el conjunto de datos antes de empezar a trabajar con él.
- ​Una cosa importante a tener en cuenta es que ​las consultas SQL se pueden escribir de muchas maneras diferentes, ​pero aun así proporcionan los mismos resultados.
- ​Por ejemplo, podríamos haber escrito ​esta consulta como una larga línea de instrucciones como ​esta y seguiríamos obteniendo los mismos resultados.

- ​Las líneas y los espacios adicionales ​no afectan al resultado de la consulta ​, pero mantienen la consulta organizada y es ​más fácil de leer para usted y para los demás.
- ​Ahora, si el proyecto no requiere todos estos campos, ​podemos usar SQL para ver ​un fragmento o fragmentos de datos en particular.
- ​Para ello, especificamos ​un nombre de columna determinado en la consulta.
- ​Por ejemplo, tal vez solo ​queramos ver los datos de Pensilvania.
- ​Empezaríamos nuestra consulta de la misma manera que acabamos de enterarnos.
- ​SELECT, espacio y añada un asterisco.
- ​Luego, DESDE nuestra base de datos de potencial solar ​, pero esta vez agregaremos dónde.

- ​Agregue un espacio y un nombre de subrayado de estado ​, el nombre de la columna.
- ​Ahora, como solo queremos ver los datos de Pensilvania, ​agregamos un signo igual y la palabra Pensilvania ​entre comillas simples.
- ​En SQL, las comillas simples ​indican el principio y el final de una cadena.
- ​Por último, ejecutamos la consulta.
- ​Ahora podemos revisar los datos sobre el ​potencial solar solo para Pensilvania.
- ​Ahora tenemos los datos que queremos y ​estamos listos para empezar a ponerlos en práctica, ​lo que trataremos más adelante.
- ​Pero por ahora, celebremos la finalización de otro módulo.

- ​Ha cubierto una gran cantidad de ​información compleja y altamente técnica.
- ​Sin embargo, a medida que sigas practicando, ​las cosas comenzarán a sentirse mucho más naturales.
- ​Por ahora, tómate un momento para ​sentarte y pensar en todo lo que has aprendido.
- ​Descubrió los metadatos y cómo mantienen ​los datos organizados al describir de qué se tratan esos datos.
- ​Ha visto cómo se ​accede a los datos internos y externos y cómo ​los analistas de datos los utilizan para encontrar ​información convincente para resolver problemas empresariales.
- ​Puede ordenar y filtrar los datos ​para identificar realmente la información que necesita.
- ​Finalmente, acabas de aprender sobre ​las consultas e incluso practicas escribiendo algunas.

- ​Próximamente, tendrás algunas lecturas y ​luego un desafío semanal para poner a prueba tus conocimientos.
- ​Esto te ayudará a confirmar que has entendido en qué ​hemos trabajado en estos vídeos y, como siempre, ​si alguna vez tienes dudas sobre alguna pregunta, ​te animo a que revises ​los vídeos y las lecturas para encontrar la respuesta.
- ​Ahora eres el detective de datos, así que usa esas habilidades.
- ​Sigan con este gran trabajo y nos ​vemos después del desafío semanal.

---

## Actividad práctica: Introducción a BigQuery
- Resumen de la actividad
   - Recientemente ha conocido BigQuery, un almacén de datos en Google Cloud que los analistas de datos utilizan para consultar, filtrar grandes conjuntos de datos, agregar resultados y realizar operaciones complejas.
   - En esta actividad, explorará la Interfaz de BigQuery; cargará datos públicos en su consola; y escribirá algunas consultas SQL sencillas utilizando SELECT, FROM, y WHERE. 
   - Cuando complete esta actividad, estará más familiarizado con la escritura de consultas en la interfaz de BigQuery.
   - Esto le permitirá practicar SQL, que es importante para trabajar con bases de datos en su carrera como analista de datos.

- Instrucciones paso a paso

1. Obtenga una cuenta BigQuery
   - Para esta actividad, necesitará una cuenta BigQuery.
   - Si aún no la tienes, sigue las instrucciones de la lectura Uso de BigQuery.
   - Una vez que tengas tu cuenta, ¡empieza a explorar!

2. Abra su consola BigQuery
   - Inicie sesión en [BigQuery](https://cloud.google.com/bigquery).
   - Seleccione el botón Ir a la consola en la página principal de BigQuery. Esto abrirá una nueva pestaña con su consola. 
   - Tómese un momento para explorar su consola.
      - El menú Explorador incluye una barra de búsqueda que puede utilizar para encontrar recursos, proyectos anclados y el botón + AÑADIR para añadir datos.
      - En la página de bienvenida del Editor podrá navegar hasta un editor de consultas, probar datos de muestra, añadir archivos de datos locales, añadir almacenamiento en la nube de Google o añadir otras conexiones externas.
      - También puede encontrar aquí su historial de trabajos, historial de consultas y consultas guardadas.

3. Acceso a los datos públicos en BigQuery
   - Para empezar a escribir consultas, necesitará algunos datos con los que trabajar.
   - Una vez que se haya familiarizado con la interfaz de BigQuery, podrá acceder a un conjunto de datos públicos directamente desde su consola. 
      - Seleccione la barra de búsqueda en el panel Explorador.
      - Introduzca "london bicycle" en el cuadro de búsqueda y pulse Intro; esto le devolverá la base de datos london_bicycles de la Autoridad del Gran Londres.
      - Seleccione la Base de datos para obtener más detalles.
      - Si no la encuentra, asegúrese de que está buscando en todos los proyectos.
      - La base de datos london_bicycles se encuentra en el proyecto bigquery-public-data.
      - Seleccione la flecha situada a la izquierda del nombre de la base de datos london_bicycles.
      - Esto amplía el conjunto de datos para revelar dos nombres de tabla: cycle_hire y cycle_stations.
      - Seleccione el nombre de la tabla cycle_hire en el panel del Explorador .
      - Esto arrastrará el esquema cycle_hire a la consola.
      - Tómese un momento para explorar los nombres de los campos y la información asociada.
      - Ahora, seleccione la pestaña VISTA PREVIA para encontrar una muestra de los datos con los que va a trabajar.
      - Una vez que haya terminado de previsualizar los datos, ¡escriba una consulta!

4. Revisar las partes básicas de una consulta
   - Hasta ahora, ha aprendido tres partes básicas de una consulta: SELECT, FROM, y WHERE. A modo de repaso: 
      - SELECT es la sección de una consulta que indica qué datos desea que SQL le devuelva.
      - FROM es la sección de una consulta que indica de qué tabla proceden los datos deseados. Debe proporcionar una ruta completa a la tabla. La ruta incluye el nombre del proyecto, el nombre de la base de datos y el nombre de la tabla, cada uno separado por un punto.
      - WHERE es la sección de una consulta que indica cualquier filtro que desee aplicar a la tabla.

5. Redactar una consulta básica
   - Ahora, ¡construya un comando sencillo utilizando las partes básicas de una consulta que ya ha aprendido!
   - Por ejemplo, puede seleccionar una columna específica de la tabla cycle_hire, como la columna end_station_name.  
      1. Seleccione el botón azul + o CONSULTA - En nueva pestaña para comenzar una nueva consulta.
      2. Comience su consulta con una cláusula SELECT, e indique qué columna desea seleccionar de la tabla; en este caso, introducirá end_station_name. 
      3. Después de indicar qué columna está seleccionando, escriba su cláusula FROM. Especifique la tabla desde la que realiza la consulta introduciendo la siguiente ubicación: `bigquery-public-data.london_bicycles.cycle_hire`; 
         - La consulta completada debería aparecer así:
         ```sql
         SELECT 
            end_station_name 
         FROM 
            `bigquery-public-data.london_bicycles.cycle_hire`;
         ```
      4. Ejecute su consulta completada seleccionando el botón azul EJECUTAR . 
         - Esta consulta puede tardar unos segundos en ejecutarse.
         - Una vez finalizada, encontrará la Lista de nombres de estaciones que solicitó en el panel de la consola Resultados de la consulta. 

6. Redactar una consulta para responder a una pregunta
   - Después de ejecutar la primera consulta básica, intente responder a una pregunta específica sobre los datos.
   - Por ejemplo, ¿cuántos viajes en bicicleta duraron 20 minutos o más?
      1. Seleccione el botón azul + o CONSULTA - En nueva pestaña para iniciar una nueva consulta. Comience de nuevo con su consulta SELECT. Esta vez, incluya las dos columnas duration  y start_station_name en la consulta. Los datos de estas columnas indicarán dónde comenzó el viaje y la duración del mismo. Asegúrese de separar cada nombre de columna con una coma.
      2. A continuación, añada la sentencia FROM  . Utilizará la misma tabla que en la consulta anterior: FROM `bigquery-public-data.london_bicycles.cycle_hire`;. Nota: Los puntos suspensivos alrededor de la tabla en esta línea de código son opcionales.
      3. Por último, añada una sentencia WHERE  para especificar que sólo desea filtrar los trayectos en bicicleta de 20 minutos o más. Si compruebas la vista previa de estos datos, te darás cuenta de que duration  se registra en segundos, por lo que especificarás 1200 segundos en tu consulta. Escríbelo como WHERE duration >= 1200;
         - Tu consulta completada debería escribirse así:
         ```sql
         SELECT 
            duration,
            start_station_name
         FROM 
            `bigquery-public-data.london_bicycles.cycle_hire` 
         WHERE 
            duration >= 1200;
         ```
      4. Ejecute su consulta completa haciendo clic en el botón EJECUTAR .
   - Esta consulta puede tardar unos segundos en ejecutarse.
   - Una vez finalizada, encontrará una Lista de trayectos de esta tabla que se ajustan a sus criterios.
   - Hay millones de filas con trayectos en bicicleta de 20 minutos o más

7. ¿Le apatece un reto?
   - Si se siente cómodo utilizando consultas para responder a preguntas, pruebe a crear y ejecutar consultas para completar las tareas que se indican a continuación: 
      - ¿Cuál es el nombre de la estación cuyo start_station_id es 111?
      ```sql
      SELECT
         start_station_name
      FROM `bigquery-public-data.london_bicycles.cycle_hire` 
      WHERE start_station_id = 111;
      ```
         - Park Lane , Hyde Park
      - Devuelva todos los rental_ids, ID de estación y nombres de estación de los que bike_id 1710 partió.
      ```sql
      SELECT
         rental_id,
         start_station_id,
         start_station_name,
         end_station_id,
         end_station_name
      FROM `bigquery-public-data.london_bicycles.cycle_hire` 
      WHERE bike_id = 1710
      ```
      - ¿Cuál es el bike_model de bike_id 58782?
      ```sql
      SELECT
         bike_model
      FROM `bigquery-public-data.london_bicycles.cycle_hire` 
      WHERE bike_id = 58782
      ```
         - CLASSIC

1. Reflexión
   - Realice otra consulta en su tabla:
   ```sql
   SELECT
      end_station_name
   FROM
      `bigquery-public-data.london_bicycles.cycle_hire` 
   WHERE
      rental_id = 57635395;
   ```
   - ¿En qué estación terminó el viaje en bicicleta con rental_id 57635395?
      - [ ] Villa Este, Parque Olímpico Reina Isabel
      - [ ] Calle Southwark, Bankside
      - [ ] Tower Gardens, Torre
      - [ ] Estación Notting Hill Gate, Notting Hill
   > La dirección que figuraba en la columna end_station_name de la fila 1 de su tabla de resultados era East Village, Queen Elizabeth Olympic Park. Para averiguarlo, ha ejecutado correctamente una consulta. En adelante, seguirá utilizando las sentencias SELECT, FROM y WHERE en sus consultas para interactuar con las bases de datos mediante SQL. Esto le ayudará a construir consultas SQL más complicadas cuando analice datos en el futuro.

2. En esta actividad, ha tenido la oportunidad de familiarizarse con BigQuery y con la escritura de consultas SQL. En el cuadro de texto que aparece a continuación, escriba de 2 a 3 frases (de 40 a 60 palabras) en respuesta a cada una de las siguientes preguntas:
   - ¿Cómo cree que puede utilizar los conjuntos de datos públicos en BigQuery para desarrollar sus habilidades de análisis de datos?
   - ¿Cómo cree que la comprensión de la sintaxis básica de las consultas le ayudará a escribir consultas más complejas en el futuro?

- Respuestas
- ¿Cómo cree que puede utilizar los conjuntos de datos públicos en BigQuery para desarrollar sus habilidades de análisis de datos?
Los conjuntos de datos públicos en BigQuery ofrecen una gran oportunidad para practicar y mejorar mis habilidades de análisis de datos. Puedo explorar diferentes tipos de datos, realizar consultas SQL y analizar resultados sin necesidad de crear mis propios conjuntos de datos. Esto me permite aprender a manejar grandes volúmenes de información y a aplicar técnicas de análisis en un entorno realista.
- ¿Cómo cree que la comprensión de la sintaxis básica de las consultas le ayudará a escribir consultas más complejas en el futuro?
Comprender la sintaxis básica de las consultas me proporciona una base sólida para escribir consultas más complejas en el futuro. Al dominar SELECT, FROM y WHERE, puedo construir consultas más avanzadas utilizando funciones agregadas, subconsultas y uniones. Esto me permitirá extraer información más específica y realizar análisis más profundos a medida que mis proyectos de datos se vuelvan más sofisticados.

> ¡Enhorabuena por haber completado esta actividad práctica! Ha explorado BigQuery, ha cargado datos públicos en su consola y ha construido algunas consultas. Una respuesta eficaz sería señalar que los conjuntos de datos públicos de BigQuery le ayudan a practicar la escritura de SQL. En las próximas actividades, seguirá explorando el trabajo con bases de datos y la escritura de consultas con SQL, una herramienta esencial en la caja de herramientas de todo analista de datos. 