# Desafío del módulo 3

## Glosario de términos del módulo 3
- El glosario completo se encuentra [aquí](./README.md#glosario)

---

## Desafío del módulo 3

1. Rellene el espacio en blanco: Los profesionales de los datos utilizan _____ para gestionar los problemas relacionados con los flujos de datos internos y externos, al tiempo que garantizan la gestión formal de los recursos de datos.
   - [ ] cartografía
   - [x] gobierno
   - [ ] estrategia
   - [ ] integridad
> Buen trabajo

2. ¿Cuál de los siguientes es el mejor ejemplo de metadatos para una columna denominada order_quantity en una tabla de base de datos de ventas?
   - [ ] El valor específico 15 registrado en la columna order_quantity para un pedido concreto.
   - [ ] El nombre del cliente que realizó el pedido más grande el mes pasado.
   - [x] La definición que indica que order_quantity representa 'El número de unidades pedidas' y su tipo de datos es 'Entero'.
   - [ ] El número total de pedidos realizados ayer en todos los productos
> Buen trabajo

3. ¿Cuál de las siguientes afirmaciones describe con exactitud las claves primaria y foránea en una base de datos relacional? Seleccione todas las que correspondan.
   - [x] Las claves foráneas se utilizan para conectar una tabla con otra.
   - [x] Una tabla sólo puede tener una clave primaria, pero puede tener varias claves externas.
   - [ ] Una clave foránea Identifica de forma única un registro en la tabla en la que se encuentra. 
   - [x] Una clave primaria hace referencia a una columna en la que cada valor es único. 
> Buen trabajo

4. Un Analista de datos ejecuta la siguiente consulta. ¿Qué quiere recuperar de la base de datos?
```sql
SELECT *
FROM VideoGames 
WHERE Creator = 'Maddox';
```
   - [ ] Todos los campos de los creadores de videojuegos
   - [ ] Todos los Campos de los videojuegos
   - [x] Todos los Campos de los videojuegos creados por Maddox
   - [ ] Todos los Campos de los videojuegos no creados por Maddox
> Buen trabajo

5. ¿Cuáles son algunos de los beneficios de utilizar datos internos para un proyecto de análisis? Seleccione todas las que correspondan.
   - [x] Los Datos internos son de libre accesibilidad porque son propiedad de la empresa. 
   - [x] Es probable que los Datos internos sean fiables
   - [ ] Datos internos representa plenamente un tema universal.
   - [ ] Datos internos que representan a toda la industria.
> Buen trabajo

6. Un analista de datos junior de un centro de convenciones está enviando un correo electrónico a todos los expositores que tienen más de 100 exposiciones al año. ¿Qué herramienta de hoja de cálculo les permitirá mostrar sólo los expositores que cumplan esa condición? 
   - [x] Filtrado de datos para mostrar sólo los expositores con más de 100 exposiciones anuales
   - [ ] Ordenar los expositores en orden descendente
   - [ ] Filtrado de datos para mostrar sólo los expositores con menos de 100 exposiciones anuales
   - [ ] Ordenar los expositores en orden ascendente
> Buen trabajo

7. Un analista de datos junior de un proveedor de servicios dentales utiliza una herramienta para explorar los datos de su base de datos de pacientes. Están creando un informe sobre el número de veces que los pacientes se limpian los dientes con hilo dental cada semana. Esta información se almacena en el campo floss_per_week de la tabla CustomerSurvey  . ¿Qué consulta deberían escribir para devolver sólo esta columna de información? 
   - [ ] `SELECT * FROM CustomerSurvey;`
   - [ ] `SELECT * FROM CustomerSurvey WHERE field = "floss_per_week";`
   - [x] `SELECT floss_per_week FROM CustomerSurvey;`
   - [ ] `SELECT floss_per_week FROM *;`
> Buen trabajo

8. ¿Qué sentencia SQL devolverá sólo los coches verdes de la columna Color de la tabla de base de datos Coches?
   - [ ] `SELECT * WHERE 'Green';`
   - [ ] `SELECT * FROM Color = 'Green';`
   - [ ] `SELECT * FROM Cars WHERE 'Green';`
   - [x] `SELECT * FROM Cars WHERE Color = 'Green';`
> Buen trabajo

9. ¿Cuáles son algunos de los efectos positivos de que las personas tengan acceso a Datos abiertos? Seleccione todas las opciones que corresponda.
   - [ ] Los Datos abiertos limitan la participación pública en la planificación del Gobierno.
   - [x] Datos abiertos permiten a los ciudadanos participar en la Planificación Pública y aportar comentarios.
   - [x] Datos abiertos hacen más transparentes las actividades del Gobierno.
   - [x] Datos abiertos permiten a la gente entender mejor sus mercados, lo que conduce al crecimiento económico.
> Buen trabajo

10. Usted es administrador de bases de datos de una peluquería especializada en tratamientos capilares y estilismo. La empresa está creciendo y ha aumentado el número de clientes a los que debe seguir la pista. Las limitaciones del diseño actual de la base de datos son cada vez más evidentes. Hay muchos más datos repetidos, como nombres de clientes, números de teléfono y direcciones de correo electrónico. Esta redundancia está causando problemas con la integridad de los datos y ralentizando las consultas. ¿Cuáles son las claves primarias de las siguientes tablas?

| Tabla Clientes  |
| --------------- |
| id_cliente      |
| nombre          |
| apellido        |
| número_teléfono |
| dirección_email |

| Tabla de servicios |
| ------------------ |
| services_id        |
| nombre_servicio    |
| precio_servicio    |
| descripción        |

   - [x] customer_id y services_id
   - [ ] first_name y service_name
   - [ ] first_name y service_id
   - [ ] apellido y descripción
> Buen trabajo