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