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