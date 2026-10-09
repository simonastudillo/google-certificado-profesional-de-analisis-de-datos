# Trabajar con bases de datos

## Todo sobre bases de datos
- Hola de nuevo.
- ​Hasta ahora, ha visto cómo se pueden recopilar y ​analizar datos para resolver todo tipo de problemas.
- ​En el siguiente paso, aprenderemos todo sobre las bases de datos.
- Como recordatorio, una ​base de datos es una colección de datos almacenados en un sistema de computadora, pero el ​almacenamiento es solo el comienzo.
- ​Descubrirá cómo las bases de datos permiten ​encontrar la información exacta que necesita para su análisis.
- ​También aprenderá a ordenar los datos para ampliar lo que necesita para ​generar informes detallados y mucho más.
- ​Luego profundizaremos aún más, y quiero decir muy, muy profundo.

- ​Me refiero a los metadatos.
- ​Probablemente hayas escuchado a alguien decir: «Vaya, eso es tan genial».
- ​Por lo general, hablan de algo que hace referencia a sí mismo o de que ​son completamente conscientes de sí mismos.
- ​Por ejemplo, si un personaje de un libro sabe que está en un libro, eso es meta.
- ​Si haces un documental sobre cómo hacer documentales, eso también es meta.
- Y ​aquí en Google, analizo constantemente cómo analizo los datos.
- ​Eso es definitivamente meta.

- ​Lo hago para comprobar la calidad de mi trabajo y asegurarme de que mis métodos son justos.
- ​Y para asegurarme de que estoy prestando atención a cualquier sesgo que pueda ​afectar el resultado.
- ​Como analista, tú también deberías hacer esto.
- ​A veces nos acercamos demasiado a nuestros datos.
- ​Por lo tanto, dar un paso atrás y preguntarnos si nuestros procesos tienen sentido es clave.
- ​Pero hagamos un poco de respaldo y definamos los metadatos.
- ​Los metadatos son datos sobre datos.

- ​Como dije: profundo.
- ​Los metadatos son extremadamente importantes cuando se trabaja con bases de datos.
- ​Piense en ello como una guía de referencia.
- ​Sin la guía, ​todo lo que tiene es un montón de datos sin contexto que explique lo que significa.
- ​Los metadatos indican de dónde provienen los datos, cuándo y cómo se crearon y ​de qué se tratan.
- ​A continuación, aprenderás cómo tomar datos de una base de datos u otra fuente y ​llevarlos a una hoja de cálculo.
- ​Para ello, puede importarlo directamente o ​utilizar SQL para generar la solicitud.

- ​Y una vez que tienes los datos en una hoja de cálculo, las posibilidades son infinitas.
- ​Todo lo que vamos a cubrir es una parte muy importante de la fase de preparación ​del proceso de análisis de datos.
- ​Es la forma en que los analistas de datos determinan qué tipo de datos ​les serán más útiles.
- ​Si tiene los datos correctos, es ​mucho más probable que pueda resolver sus problemas empresariales con éxito.
- ​Entonces, ¿estás listo para aprovechar el increíble poder de las bases de datos? ​¡Vamos! 

---

## Características y componentes de la base de datos
- Las bases de datos son herramientas esenciales para los analistas de datos.
- Los uso constantemente.
- ​Casi todos los datos a los que accedo se almacenan en bases de datos.
- ​Las bases de datos almacenan y organizan los datos, lo que facilita mucho a ​los analistas de datos la administración y el acceso a la información.
- ​Nos ayudan a obtener información más rápido, a tomar decisiones basadas en datos y a resolver problemas.
- ​Ya ha escuchado un poco sobre qué son las bases de datos y ​cómo las utilizan los analistas de datos.
- ​Ahora aprendamos más sobre las características y los componentes de las bases de datos.

- ​Esta es una estructura de base de datos sencilla.
- ​Contiene tablas con información de un fabricante de automóviles.
- ​El nivel superior incluye concesionarios de automóviles, detalles del producto y piezas de reparación.
- ​Luego, si profundizas en el siguiente nivel seleccionando una de esas tablas, ​encontrarás detalles más específicos sobre cada elemento.
- ​Esto se denomina base de datos relacional.
- ​Una base de datos relacional es una base de datos que contiene una serie de tablas relacionadas ​que se pueden conectar a través de sus relaciones.
- ​Para que dos tablas tengan una relación, ​deben existir uno o más campos iguales en ambas tablas.

- ​Por ejemplo, aquí, el ID de sucursal existe en esta tabla y en esta.
- ​Si existe un campo en ambas tablas, podemos usarlo para conectar las tablas.
- ​El campo ID de sucursal es la clave para conectar estas tablas.
- ​Hay dos tipos de llaves.
- ​Una clave principal es un identificador que hace referencia a una columna en la que cada valor ​es único.
- Puede considerarlo como un identificador único para cada fila de una tabla.
- ​Para nuestra tabla de concesionarios con información sobre las diferentes sucursales de concesionarios, la ​clave principal es el identificador de sucursal.

- ​Del mismo modo, para la tabla de detalles del producto de cada automóvil, el VIN es nuestra clave principal.
- ​Como analista, es posible que necesite crear tablas.
- ​Si decides incluir una clave principal, debe ser única, lo que ​significa que no hay dos filas que puedan tener la misma clave principal.
- ​Además, no puede ser nulo ni estar en blanco.
- ​También hay claves foráneas.
- ​Una clave externa es un campo de una tabla que es una clave principal de otra tabla.
- ​En otras palabras, una clave externa es la forma en que una tabla se puede conectar a otra.

- ​Como nuestra tabla de piezas de reparación contiene información sobre cada pieza del automóvil, ​la clave principal es la identificación de la pieza.
- ​Cada fila de nuestra tabla de piezas de reparación representa una pieza única.
- ​Todas las demás claves de esta tabla, como el VIN, son las claves externas que permiten ​conectar la tabla de piezas de reparación a las demás tablas.
- ​Como puede ver, una tabla solo puede tener una clave principal, ​pero puede tener varias claves externas.
- ​Entender las claves principales y foráneas puede ser complicado, por lo ​que tendrás más oportunidades de practicar próximamente.
- ​Sin embargo, como resumen general, ​se usa una clave principal para garantizar que los datos de una columna específica sean únicos.
- ​Identifica de forma exclusiva un registro en una tabla de base de datos relacional.

- ​Solo se permite una clave principal en una tabla y ​no pueden contener valores nulos o en blanco.
- ​Y una clave externa es una columna o grupo de columnas de una tabla de base de datos relacional ​que proporciona un enlace entre los datos y dos tablas.
- ​Hace referencia al campo de una tabla que es la clave principal de otra tabla.
- ​Por último, es importante tener en cuenta que se permite que haya más de una clave ​externa en una tabla.
- ​No dudes en volver a ver este vídeo para asegurarte de que entiendes con ​claridad las claves principales y foráneas.
- ​Y próximamente, empezará a practicar cómo acceder y ​analizar datos de bases de datos reales.
- ​Será una gran oportunidad para mejorar su comprensión de ​las claves principales y externas, la organización de las bases de datos y la ​forma en que podría utilizar las bases de datos en su futura carrera de análisis.