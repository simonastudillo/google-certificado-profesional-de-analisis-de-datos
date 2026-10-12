# Integridad de datos y objetivos analíticos

## Por qué es importante la integridad de los datos
- ​Bienvenido de nuevo.
- En este vídeo, ​analizaremos la integridad de los datos y ​algunos riesgos a los que podría enfrentarse como analista de datos.
- ​Un análisis sólido depende de la integridad de los datos.
- ​Si los datos que utiliza se ven comprometidos de alguna manera, ​su análisis no será tan sólido como debería ser.
- La ​integridad de los datos es la precisión, la integridad, la ​coherencia y la confiabilidad de los ​datos a lo largo de su ciclo de vida.
- ​Eso puede parecer un montón ​de cualidades que los datos deben cumplir.
- ​Pero créeme, vale la pena comprobarlos ​todos antes de continuar con el análisis.

- ​De lo contrario, su análisis podría estar equivocado.
- ​No porque haya hecho algo mal, ​sino porque los datos ​con los que estaba trabajando eran incorrectos desde el principio.
- ​Cuando la integridad de los datos es baja, ​puede provocar cualquier cosa, desde la pérdida de un solo píxel en ​una imagen hasta una decisión médica incorrecta.
- ​En algunos casos, la ​falta de una pieza puede hacer que todos los datos sean inútiles.
- ​La integridad de los datos puede verse ​comprometida de muchas maneras diferentes.
- ​Existe la posibilidad de que los datos se ​vean comprometidos cada vez que se replican ​, transfieren o manipulan de alguna manera.
- La ​Replicación de datos es el proceso de ​almacenamiento de datos en varias ubicaciones.

- ​Si estás replicando datos en ​diferentes momentos y lugares, ​existe la posibilidad de que tus datos no estén sincronizados.
- ​Estos datos carecen de integridad ​porque es posible que diferentes personas no estén ​utilizando los mismos datos para ​sus hallazgos, lo que puede provocar inconsistencias.
- ​También está el tema de la transferencia de datos, ​que es el proceso de copiar ​datos de un dispositivo de almacenamiento ​a la memoria o de una computadora a otra.
- ​Si se interrumpe la transferencia de datos, es ​posible que acabe con un conjunto de datos incompleto, ​lo que puede no ser útil para sus necesidades.
- ​El proceso de manipulación de datos implica cambiar ​los datos para que estén más organizados y sean más fáciles de leer.
- ​La Manipulación de ​datos tiene por objeto hacer que el proceso de análisis de datos sea más eficiente, ​pero un error durante el proceso ​puede comprometer la eficiencia.
- ​Por último, los datos también pueden verse comprometidos debido ​a errores humanos, virus, ​software malicioso, piratería informática y fallos del sistema, ​lo que puede provocar aún más dolores de cabeza.

- ​Me detendré ahí.
- ​Esas son suficientes noticias potencialmente malas como para digerirlas.
- ​Pasemos a algunas noticias potencialmente buenas.
- ​En muchas empresas, el ​equipo de almacenamiento de datos o ingeniería de datos se ​encarga de garantizar la integridad de los datos.
- ​Próximamente, aprenderemos cómo comprobar ​la integridad de los datos como analistas de datos.
- ​Pero tenga la seguridad de que ​alguien más normalmente también lo respaldará.
- ​Una vez que hayas descubierto con qué datos estás trabajando, ​es importante que compruebes que los datos están ​completos y son válidos antes del análisis.

- ​Esto ayudará a garantizar que su análisis y sus ​posibles conclusiones sean precisos.
- La ​verificación de la integridad de los datos es un paso vital en el ​procesamiento de los datos a fin de prepararlos para el análisis, ​ya sea que lo esté haciendo usted o alguien más de su empresa.
- ​Próximamente, aprenderá aún más ​sobre la integridad de los datos.
- ¡Nos vemos pronto! 

---

## Más información sobre integridad y conformidad de los datos
- Esta lectura ilustra la importancia de la integridad de los datos mediante un ejemplo de los datos de una empresa global.
- Al final se proporcionarán definiciones de términos relevantes para la integridad de los datos.

- Escenario: fechas de calendario para una empresa global
   - Las fechas del calendario se representan de muchas formas abreviadas diferentes.
   - Dependiendo de dónde viva, puede que se utilice un formato diferente.
      - En algunos países, 12/10/20 (DD/MM/AA) significa 12 de octubre de 2020.
      - En otros países, el estándar nacional es AAAA-MM-DD, por lo que 12 de octubre de 2020 se convierte en 2020-10-12.
      - En Estados Unidos, (MM/DD/AA) es el formato aceptado por lo que el 12 de octubre de 2020 será 10/12/20.
   - Ahora, piense qué pasaría si trabajara como analista de datos para una empresa global y no comprobara los formatos de fecha.
   - Pues que la integridad de sus datos sería probablemente cuestionable.
   - Cualquier análisis de los Datos sería inexacto.
   - ¡Imagínese pedir inventario extra para diciembre cuando en realidad se necesitaba en octubre!
   - Un buen análisis depende de la integridad de los datos, y la integridad de los datos suele depender del uso de un formato común.
   - Por eso es importante comprobar dos veces el formato de las fechas para asegurarse de que lo que usted cree que es el 10 de diciembre de 2020 no es en realidad el 12 de octubre de 2020, y viceversa.

- He aquí otras cosas de las que hay que cuidarse:
   - Replicación de datos que comprometa la integridad de los mismos:
      - Siguiendo con el ejemplo, imagine que pide a sus homólogos internacionales que verifiquen las fechas y se ciñan a un formato.
      - Un analista copia un gran conjunto de datos para comprobar las fechas.
      - Pero por problemas de memoria, en realidad sólo se copia una parte del conjunto de datos.
      - El analista estaría verificando y normalizando datos incompletos.
      - Ese conjunto de datos parcial se certificaría como conforme, pero el conjunto de datos completo seguiría conteniendo fechas que no se han verificado.
      - Dos versiones de un Conjunto de datos pueden introducir resultados incoherentes.
      - Una auditoría final de los resultados sería esencial para revelar lo sucedido y corregir todas las fechas. 
   - Transferencia de datos que compromete la integridad de los datos:
      - Otro analista comprueba las fechas en una hoja de cálculo y decide importar los datos validados y normalizados de nuevo a la base de datos.
      - Pero supongamos que el campo de fecha de la hoja de cálculo se clasificó incorrectamente como campo de texto durante el proceso de importación (transferencia) de datos.
      - Ahora algunas de las fechas de la base de datos se almacenan como cadenas de texto.
      - En este punto, es necesario limpiar los datos para restaurar su integridad.
   - Manipulación de datos que compromete la integridad de los mismos:
      - Al comprobar las fechas, otro analista observa lo que parece ser un registro duplicado en la base de datos y lo elimina.
      - Pero resulta que el analista eliminó un registro Único para la filial de una empresa y no un registro duplicado para la empresa.
      - A su Conjunto de datos le faltan ahora datos y hay que restaurar los datos para que estén completos.

- Conclusión
   - Afortunadamente, con un formato de fecha estándar y el cumplimiento por parte de todas las personas y sistemas que trabajan con los datos, se puede mantener la integridad de los datos.
   - Pero no importa de dónde procedan sus datos, asegúrese siempre de comprobar que son válidos, completos y limpios antes de iniciar cualquier análisis.

- Referencia: Limitaciones de datos y ejemplos
   - A medida que avance en su viaje de datos, se encontrará con muchos tipos de limitaciones de datos (o criterios que determinan la validez).
   - La tabla siguiente ofrece definiciones y ejemplos de términos de limitaciones de datos con los que podría encontrarse. 

| Limitaciones de datos    | Definición         | Ejemplos           |
| ------------------------ | ------------------ | ------------------ |
| Tipo de datos            | Los Valores deben ser de un tipo determinado: fecha, número, porcentaje, booleana, etc. | Si el Tipo de datos es una fecha, un solo número como 30 fallaría la restricción y sería inválido |
| Rango de datos           | Los Valores deben estar comprendidos entre los valores máximo y mínimo predefinidos | Si el Rango de datos es 10-20, un valor de 30 fallaría la restricción y sería inválido |
| Obligatorio              | Los Valores no pueden dejarse en blanco o vacíos | Si la edad es obligatoria, ese valor debe rellenarse |
| Único                    | Los Valores no pueden tener un duplicado | Dos personas no pueden tener el mismo número de teléfono móvil dentro de la misma área de servicio |
| Patrones de expresión regular (regex) | Los Valores deben coincidir con un Patrón prescrito | Un número de teléfono debe coincidir con ###-##-#### (no se permiten otros caracteres) |
| Validación de campos cruzados | Deben cumplirse ciertas condiciones para múltiples campos | Los Valores son porcentajes y los valores de varios campos deben sumar 100% |
| Clave primaria           | (Sólo bases de datos) el valor debe ser único por columna | Una tabla de base de datos no puede tener dos filas con el mismo valor de clave primaria. Una clave primaria es un identificador en una base de datos que hace referencia a una columna en la que cada valor es único. Más adelante en el programa encontrará más información sobre claves primarias y foráneas.
| Establecer-membresía     | (Sólo bases de datos) los valores para una columna deben proceder de un conjunto de valores discretos  | Valores para una columna deben ser Sí, No o No aplicable |
| Clave foránea            | (Sólo bases de datos) los valores para una columna deben ser valores únicos procedentes de una columna de otra tabla | En una base de datos de contribuyentes de EE.UU., la columna Estado debe ser un estado o territorio válido con el conjunto de valores aceptables definido en una tabla de Estados independiente |
| Exactitud                | El grado en que los datos se ajustan a la entidad real que se está midiendo o describiendo | Si los valores de los códigos postales se validan por la ubicación de la calle, la exactitud de los datos aumenta. |
| Exhaustividad            | El grado en que los datos contienen todos los componentes o medidas deseados | Si los datos para los perfiles personales requieren el color del pelo y de los ojos, y se recogen ambos, los datos están completos. |
| Coherencia               | El grado en que los datos son repetibles desde diferentes puntos de entrada o recogida | Si un cliente tiene la misma dirección en las bases de datos de ventas y reparaciones, los datos son coherentes. |

---

## Equilibrio entre los objetivos y la integridad de los datos
- ​Hola, es bueno recordar comprobar la integridad de los datos.
- ​También es importante comprobar que los datos que utiliza se alinean con el ​objetivo empresarial.
- ​Esto añade otro nivel al mantenimiento de la integridad de los datos, ​ya que los datos que está utilizando pueden tener limitaciones con las que tendrá que lidiar.
- ​El proceso de hacer coincidir los datos con los objetivos empresariales puede ser bastante ​sencillo.
- ​He aquí un ejemplo rápido.
- Supongamos que es analista de ​una empresa que produce y vende autopartes.
- ​Si necesitas responder a una pregunta sobre los ingresos generados por la venta de ​una determinada pieza, puedes acceder a la tabla de ingresos del conjunto de datos.

- ​Si la pregunta se refiere a las opiniones de los clientes, ​abre la tabla de reseñas para analizar las valoraciones medias.
- ​Sin embargo, antes de profundizar en cualquier análisis, ​debe tener en cuenta algunas limitaciones que podrían afectarlo.
- ​Si los datos no se han limpiado correctamente, no podrás usarlos todavía.
- ​Tendrá que esperar hasta que se haya realizado una limpieza a fondo.
- ​Ahora, supongamos que estás intentando averiguar cuánto gasta un cliente promedio.
- ​Observa que los datos del mismo cliente aparecen en más de una fila.
- ​Esto se denomina datos duplicados.

- ​Para solucionar este problema, es posible que tenga ​que cambiar el formato de los datos o la forma de calcular el promedio.
- ​De lo contrario, parecerá que los datos corresponden a dos personas diferentes y ​se quedará atrapado en cálculos engañosos.
- ​También puede darse cuenta de que no hay datos suficientes para completar un análisis preciso.
- ​Tal vez solo tenga datos de ventas de un par de meses.
- ​Hay pocas posibilidades de que esperes a recibir más datos, pero ​es más probable que tengas que cambiar tu proceso o ​buscar fuentes de datos alternativas sin dejar de cumplir tu objetivo.
- ​Me gusta pensar en un conjunto de datos como una imagen.
- ​Toma esta foto.
- ¿Qué estamos viendo? 

- ​A menos que seas un viajero experto o conozcas la zona, ​puede ser difícil distinguir solo entre estas dos imágenes.
- ​Visualmente, es muy claro cuando no vemos la imagen completa.
- ​Cuando tienes la imagen completa, te das cuenta de que.
- ¡estás en Londres! ​Con datos incompletos, ​es difícil ver el panorama completo para tener una idea real de lo que está sucediendo.
- ​A veces confiamos en los datos porque, si nos llegan en filas y columnas, ​parece que todo lo que necesitamos está ahí si solo los consultamos.
- Pero eso simplemente no es cierto.
- ​Recuerdo un momento en el que descubrí que no tenía suficientes datos y ​que tenía que encontrar una solución.

- ​Trabajaba para una empresa minorista en línea y me ​pidieron que descubriera cómo reducir la compra de los clientes al tiempo de entrega.
- Los ​tiempos de entrega más rápidos suelen hacer que los clientes estén más satisfechos.
- ​Cuando comprobé el conjunto de datos, encontré información de seguimiento muy limitada.
- ​Nos faltaban algunos detalles bastante clave.
- ​Por eso, los ingenieros de datos y yo creamos nuevos procesos para rastrear información adicional, ​como la cantidad de paradas en un viaje.
- ​Con estos datos, redujimos el tiempo que pasaba desde la compra hasta la entrega y ​vimos una mejora en la satisfacción del cliente.
- ¡Eso se sintió muy bien! 
- ​Aprender a tratar los problemas de datos sin dejar de centrarse en su objetivo lo ​ayudará a prepararse para el éxito en su carrera como analista de datos.
- Y ​su ruta de acceso al éxito continúa.
- En el ​siguiente paso, obtendrá más información sobre cómo alinear los datos con los objetivos.
- ¡Sigan así! 

---

## Objetivos y Datos bien alineados
- Cuando los datos están bien alineados con los objetivos de la empresa, se puede obtener información muy valiosa y llegar a conclusiones precisas.
- COMO ANALISTA DE DATOS, la alineación es algo que tendrá que juzgar.
- Una buena alineación significa que los datos son relevantes y pueden ayudarle a resolver un problema empresarial o a determinar un curso de acción para alcanzar un objetivo empresarial determinado. 
- En esta lectura, revisará los objetivos empresariales asociados a tres escenarios.
- Explorará cómo unos datos limpios y unos objetivos empresariales bien alineados pueden ayudarle a llegar a conclusiones precisas.
- Además, aprenderá cómo las nuevas variables descubiertas durante el análisis de datos pueden hacer que establezca limitaciones de datos para que pueda mantener los datos alineados con un objetivo empresarial.

- Datos limpios + alineación con el objetivo empresarial = conclusiones precisas
   - Objetivo empresarial
      - Los gestores de cuentas de Impress Me, un servicio de suscripción a contenidos en línea, quieren saber cuánto tardan los usuarios en ver los contenidos una vez activadas sus suscripciones.
      - Para empezar, el analista de datos comprueba que los datos exportados a hojas de cálculo están limpios y confirma que los datos necesarios (cuándo acceden los usuarios al contenido) están disponibles.
      - Sabiendo esto, el analista decide que hay una buena alineación de los datos con el objetivo empresarial.
      - Lo único que falta es averiguar exactamente cuánto tarda cada usuario en ver el contenido una vez activada su suscripción.
      - Estos son los pasos de procesamiento de datos que sigue el analista para un usuario de una cuenta llamada V&L Consulting.
      - (Estos pasos se repetirían para cada cuenta suscriptora, y para cada usuario asociado a esa cuenta)
   - Paso 1
   
| Paso de procesamiento de datos | Fuente de datos |
| ------------------------------ | --------------- |
| Buscar la fecha de activación de V&L Consulting | Hoja de cálculo de la cuenta |

   - Datos relevantes en la hoja de cálculo:
      - Resultado: 21 de octubre de 2019

| Account Name | Activation Date |
| ------------ | --------------- |
| V&L Consulting | 10/21/2019    |
| Berg Associates | 11/29/2019   |
| Up Advertising  | 03/30/2020   |

   - Paso 2

| Etapa de tratamiento de datos | Fuente de datos |
| ----------------------------- | --------------- |
| Buscar el nombre de usuario perteneciente a la cuenta V&L Consulting | Hoja de cálculo de la cuenta (pestaña usuarios) |

   - Datos relevantes en la hoja de cálculo:
      - Maria Ballantyne

| Account Name   | Users            |
| -------------- | ---------------- |
| V&L Consulting | Maria Ballantyne |
| V&L Consulting | Carol Sander     |
| V&L Consulting | Sam Rubio        |

   - Paso 3

| Paso de procesamiento de datos | Fuente de datos |
| ----------------------------- | --------------- |
| Encontrar la primera fecha de acceso a los contenidos de Maria B. | Hoja de cálculo de uso de contenidos |

   - Datos relevantes en la hoja de cálculo:
      - 31 de octubre de 2019

| Users | Access Dates |
| ----- | ------------ |
| Maria Bellantyne | 10/31/2019 |
|                  | 11/1/2019  |
|                  | 11/5/2019  |

   - Paso 4
   
| Etapa de tratamiento de datos | Fuente de datos |
| ----------------------------- | --------------- |
| Calcular el tiempo transcurrido entre la activación y el primer uso de contenidos para María B. | Nuevo cálculo en hoja de cálculo |

   - Datos relevantes en la hoja de cálculo:
      - 10 días

| Account | Users | Activation Date | First Access Date | Number of Days |
| ------- | ----- | --------------- | ----------------- | -------------- |
| V&L Consulting | Maria Ballantyne | 10/21/2019 | 10/31/2019 | 10 |

   - Consejo profesional 1
      - En el proceso anterior, el analista podría utilizar VLOOKUP para buscar los datos en los pasos 1, 2 y 3 para rellenar los valores de la hoja de cálculo en el paso 4.
      - [VLOOKUP](https://support.microsoft.com/en-us/office/vlookup-function-0bbc8083-26fe-4963-8ab8-93a18ad188a1) es una función de hoja de cálculo que busca un determinado valor en una columna para devolver una información relacionada.
      - El uso de VLOOKUP puede ahorrar mucho tiempo; sin él, hay que buscar fechas y nombres manualmente.
   
   - Consejo profesional 2
      - En el paso 4 del proceso anterior, el analista podría utilizar la función DATEDIF para calcular automáticamente la diferencia entre las fechas de la columna C y la columna D.
      - La función puede calcular el número de días entre dos fechas.
      - Consulte la página [DATEDIF](https://support.microsoft.com/en-us/office/datedif-function-25dba1a4-2812-480b-84dd-8b32a451b35c) de Microsoft Support para saber cómo utilizar la función en Excel.
      - La función [DAYS360](https://support.microsoft.com/en-us/office/days360-function-b9a509fd-49ef-407e-94df-0cbda5718c2a) hace lo mismo en hojas de cálculo contables que utilizan un año de 360 días (doce meses de 30 días).
      - Consulta la página [DATEDIF](https://support.google.com/docs/answer/6055612?hl=en) del Centro de asistencia de Google para saber cómo utilizar la función en Google Sheets.

- Alineación con el objetivo empresarial + depuración adicional de datos = conclusiones precisas
   - Objetivo empresarial
      - Cloud Gate, una empresa de software, organizó recientemente una serie de seminarios web públicos como presentación gratuita de sus productos.
      - El Analista de datos y el Gerente del programa de seminarios web quieren identificar a las empresas en las que cinco o más personas asistieron a estas sesiones.
      - Quieren dar esta lista de empresas a los directores de ventas para que puedan hacer un seguimiento de las ventas potenciales.
      - Los datos de asistencia al seminario web incluyen los campos y datos que se muestran a continuación.

| Nombre       | <Nombre><Apellido>       | Esta información era obligatoria para los asistentes |
| ------------ | ------------------------ | ---------------------------------------------------- |
| Dirección de correo electrónico | xxxxx@company.com | Esta era la información obligatoria que los asistentes debían enviar |
| Empresa                         | <Nombre de laempresa> | Esta era la información opcional que los asistentes podían proporcionar |

   - Limpieza de datos
      - Los datos de asistencia al seminario web parecen ajustarse al objetivo empresarial.
      - Pero el Analista de datos y el Gerente del programa deciden que es necesario limpiar los datos antes del análisis.
      - Creen que la limpieza de datos es necesaria porque:
         - El nombre de la empresa no era un campo obligatorio.
            - Si el nombre de la empresa está en blanco, podría encontrarse a partir de la dirección de correo electrónico.
            - Por ejemplo, si la dirección de correo electrónico es username@google.com, el campo de la empresa podría rellenarse con Google para el análisis de datos.
            - Este paso de limpieza de datos supone que las personas con direcciones de correo electrónico asignadas por la empresa asistieron a un seminario web por motivos profesionales.
         - Los asistentes podían introducir cualquier nombre.
            - Dado que se está analizando la asistencia a una serie de seminarios web, es necesario validar los nombres con direcciones de correo electrónico únicas.
            - Por ejemplo, si Joe Cox asistiera a dos seminarios pero se registrara como Joe Cox en uno y como Joseph Cox en el otro, se contaría como dos personas diferentes.
            - Para evitarlo, es necesario comprobar su dirección de correo electrónico única para determinar que se trata de la misma persona.
            - Tras la validación, Joseph Cox podría cambiarse por Joe Cox para coincidir con la otra instancia.

- Alineación con el objetivo empresarial + variables recién descubiertas + restricciones = conclusiones precisas
   - Objetivo empresarial
      - Una empresa de clases particulares extraescolares, A+ Education, quiere saber si hay un número mínimo de horas de clase necesarias para que los alumnos mejoren al menos un 10% sus calificaciones. 
      - El analista de datos considera que existe una buena concordancia entre los datos disponibles y el objetivo empresarial porque:
         - Los estudiantes entran y salen del sistema para cada sesión de tutoría y se registra el número de horas
         - Los resultados de las evaluaciones se registran regularmente.
      - Limitaciones de datos para nuevas variables
            - Tras examinar los datos, el Analista de datos descubre que hay otras variables a tener en cuenta.
            - Algunos alumnos tenían sesiones semanales constantes, mientras que otros tenían sesiones programadas de forma más aleatoria, aunque su número total de horas de tutoría fuera el mismo.
            - Los datos no se alinean tan bien con el objetivo empresarial original como se pensó en un principio, por lo que el analista añade una restricción de datos para centrarse sólo en los alumnos con sesiones semanales constantes.
            - Esta modificación ayuda a obtener una imagen más precisa sobre el tiempo de matriculación necesario para lograr una mejora del 10% en las puntuaciones de las evaluaciones.

- Puntos clave
   - Esperamos que estos ejemplos le den una idea de lo que debe buscar para saber si sus datos se alinean con su objetivo de negocio.
   - Cuando hay datos limpios y una buena alineación, puede obtener información precisa y llegar a conclusiones que los datos respaldan.
   - Si la alineación es buena, pero los datos necesitan ser depurados, depure los datos antes de realizar el análisis.
   - Si los datos sólo se ajustan parcialmente a un objetivo, piense en cómo podría modificar el objetivo, o utilice limitaciones de datos para asegurarse de que el subconjunto de datos se ajusta mejor al objetivo empresarial.