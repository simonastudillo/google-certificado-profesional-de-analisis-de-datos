# Pruebe sus datos

## Uso del poder estadístico
- Hola, ahí.
- ​Probablemente todos hemos soñado con tener una superpotencia al menos una vez en la vida.
- ​Sé que lo he hecho.
- Me encantaría poder volar.
- ​Pero hay otra superpotencia de la que quizás no hayas oído hablar: el poder estadístico.
- El ​poder estadístico es la probabilidad de obtener resultados significativos de una prueba.
- ​Supongo que no es un superpoder con el que ninguno de ustedes haya soñado.

- ​Aun así, es una superpotencia de datos bastante buena.
- ​Para los analistas de datos, sus proyectos pueden comenzar con la prueba o el estudio.
- El ​testeo de hipótesis es una forma de comprobar si una encuesta ​o un experimento arroja resultados significativos.
- ​He aquí un ejemplo.
- ​Supongamos que trabajas para una cadena de restaurantes que está planificando una campaña de marketing para ​sus nuevos batidos.
- ​Debes probar el anuncio en un grupo de clientes antes de convertirlo en una ​campaña publicitaria nacional.
- ​En la prueba, quieres comprobar si a los clientes les gusta o no la campaña.

- ​También debes descartar cualquier factor ajeno al anuncio que pueda ​llevarlos a decir que no les gusta.
- ​Utilizar a todos sus clientes llevaría demasiado tiempo y sería demasiado caro.
- ​Por lo tanto, tendrás que averiguar cuántos clientes necesitarás para demostrar que el anuncio ​es efectivo.
- ​Cincuenta probablemente no serían suficientes.
- ​Incluso si eliges 50 clientes al azar, ​podrías terminar con clientes a los que no les gusten los batidos en absoluto.
- ​Y si eso ocurre, no podrás medir la eficacia de tu anuncio a la hora de ​recibir más pedidos de batidos, ya que nadie del tamaño de la muestra los pediría.
- ​Es por eso que necesita un tamaño de muestra más grande: ​para asegurarse de obtener un buen número de personas de todo tipo para su prueba.

- ​Por lo general, cuanto mayor sea el tamaño de la muestra, mayores serán las probabilidades de ​obtener resultados estadísticamente significativos con la prueba.
- ​Y eso es poder estadístico.
- ​En este caso, usar tantos clientes como sea posible mostrará las diferencias reales ​entre los grupos a los que les gusta o no ​les gusta el anuncio y las personas cuya decisión no se basó en absoluto en el anuncio.
- ​Hay formas de calcular con precisión el poder estadístico, pero ​no las analizaremos aquí.
- ​Es posible que deba calcularlo por su cuenta como analista de datos.
- ​Por ahora, debes saber que la potencia estadística normalmente se muestra como un valor ​de uno.
- ​Por lo tanto, si tu poder estadístico es 0.6, es lo mismo que decir 60%.

- ​En la prueba de anuncios de batidos de leche, ​si encontraste una potencia estadística del 60%, significa que hay un 60% ​de probabilidades de que obtengas un resultado estadísticamente significativo en cuanto a la eficacia del anuncio.
- ​«Estadísticamente significativo» es un término que se usa en estadística.
- ​Si desea obtener más información sobre el significado técnico, puede buscar en línea.
- ​Pero en términos básicos, si una prueba es estadísticamente significativa, ​significa que los resultados de la prueba son reales y no un error causado por una casualidad aleatoria.
- ​Por lo tanto, hay un 60% de probabilidades de que los resultados de la ​prueba publicitaria del batido sean fiables y reales, ​y un 40% de probabilidades de que el resultado de la prueba sea incorrecto.
- ​Por lo general, se necesita una potencia estadística de al menos 0,8 u ​80% para considerar que los resultados son estadísticamente significativos.
- ​Vamos a ver un escenario más.

- ​Nos quedaremos con los batidos porque, bueno, porque me gustan los batidos.
- ​Imagina que trabajas para una cadena de restaurantes que quiere lanzar un nuevo batido ​con sabor a tarta de cumpleaños.
- ​Este batido será más caro de producir que los otros batidos.
- ​Su empresa espera que el rumor en torno al nuevo sabor atraiga más ​clientes y dinero para compensar este costo.
- ​Primero quieren probar esto en algunos restaurantes.
- ​Así que averigüemos cuántas ubicaciones tendrías que usar para tener confianza en tus ​resultados.
- ​En primer lugar, tendrá que pensar en lo que podría impedir que obtenga ​resultados estadísticamente significativos.

- ​¿Hay restaurantes que ofrezcan otras promociones que puedan atraer ​nuevos clientes? ​¿Algunos restaurantes tienen clientes que siempre compran el artículo más nuevo, ​sin importar lo que sea? ​¿Alguna ubicación tiene obras que hayan comenzado recientemente y ​que impidan que los clientes vayan al restaurante? ​Para obtener un mayor poder estadístico, tendrá que considerar todos estos factores ​antes de decidir cuántas ubicaciones incluir en el tamaño de la muestra para ​su estudio.
- ​Debes asegurarte de que cualquier efecto se deba probablemente al nuevo sabor del batido, ​no a otro factor.
- ​Los efectos medibles serían un aumento en las ventas o en ​la cantidad de clientes en las ubicaciones del tamaño de la muestra.
- ​Eso es todo por ahora.

- ​Próximamente, analizaremos los tamaños de las muestras con más detalle para ​que puedas hacerte una mejor idea de cómo afectan a tus pruebas y estudios.
- ​Mientras tanto, has aprendido un poco más sobre los batidos y los superpoderes.
- ​Y, por supuesto, poder estadístico.
- ​Lamentablemente, solo el poder estadístico puede ser realmente útil para los analistas de datos.
- ​Aunque ponerme la capa y ​volar para tomar un batido ahora mismo suena bastante bien.
- [A Gentle Introduction to Statistical Power and Power Análisis in Python](https://machinelearningmastery.com/statistical-power-and-power-analysis-in-python/) lo resume muy bien: 
   - "El Poderestadístico puede calcularse e informarse para un experimento terminado con el fin de comentar la confianza que se puede tener en las conclusiones extraídas de los resultados del estudio. También puede utilizarse como herramienta para estimar el número de observaciones o el tamaño de la muestra necesarios para detectar un efecto en un experimento."
   - Opcional: Si desea una explicación más detallada de la potencia estadística y el análisis de potencia, el enlace anterior es un tutorial que también incluye una lista de referencias adicionales.

---

## Cuando los Datos no están fácilmente disponibles
- Anteriormente, aprendió cómo puede hacer un análisis utilizando datos proxy si no tiene datos.
- Es posible que tenga algunas preguntas sobre los datos proxy, por lo que esta lectura le dará algunos ejemplos más de los tipos de conjuntos de datos que pueden servir como fuentes de datos alternativas.

- Ejemplos de datos proxy
   - A veces, los datos que respaldan un objetivo empresarial no están fácilmente disponibles.
   - Es entonces cuando resultan útiles los datos proxy.
   - Eche un vistazo a los siguientes escenarios y al lugar que ocupan los datos proxy en cada ejemplo:

| Escenario Negocio a negocio (Business-to-Business) | Cómo pueden utilizarse los datos proxy |
| -------------------------------------------------- | -------------------------------------- |
| Un nuevo modelo de coche acaba de lanzarse hace unos días y el concesionario de automóviles no puede esperar hasta final de mes a que lleguen los datos de ventas. Quieren proyecciones de ventas ahora. | El analista toma como proxy el número de clics a las especificaciones del coche en la página web del concesionario como estimación de las ventas potenciales en el concesionario. |
| Un nuevo producto cárnico de origen vegetal se ha almacenado recientemente en las tiendas de comestibles y el proveedor necesita estimar la demanda en los próximos cuatro años. | El analista toma como proxy los datos de ventas de un sustituto del pavo hecho de tofu que lleva varios años en el mercado. |
| La Cámara de Comercio quiere saber cómo va a repercutir una campaña turística en los viajes a su ciudad, pero los resultados de la campaña aún no están a disposición del público. | El analista proxy los datos históricos de reservas aéreas a la ciudad entre uno y tres meses después de que se realizara una campaña similar seis meses antes. |

- Conjuntos de datos abiertos (públicos)
   - Si forma parte de una gran organización, es posible que tenga acceso a muchas fuentes de datos.
   - Pero si busca algo específico o un poco fuera de su línea de negocio, también puede recurrir a conjuntos de datos abiertos o públicos.
   - (Puede consultar [este artículo de Medium](https://medium.com/thinkdata/is-there-a-difference-between-open-data-and-public-data-2b8d5608b2f1) para obtener una breve explicación de la diferencia entre datos abiertos y públicos)

   - He aquí un ejemplo.
   - Recientemente se ha puesto a disposición del público una versión nasal de una vacuna.
   - Una clínica quiere saber qué puede esperar de las contraindicaciones, pero acaba de empezar a recopilar Datos de primera fuente de sus pacientes.
   - Una contraindicación es una condición que puede hacer que un paciente no tome una vacuna debido al daño que le causaría si la tomara.
   - Para estimar el número de posibles contraindicaciones, un analista de datos toma como proxy un conjunto de datos abiertos de un ensayo de la versión inyectable de la vacuna.
   - El analista selecciona un subconjunto de los datos con los perfiles de pacientes que más se aproximan a la composición de los pacientes de la clínica.

   - Hay muchas formas de compartir y colaborar en torno a los Datos dentro de una comunidad.
   - Kaggle (kaggle.com), que ya presentamos anteriormente, dispone de conjuntos de datos en una gran variedad de formatos, incluido el tipo más básico, los Archivos CSV (Valores separados por coma).

- Conjuntos de datos CSV, JSON, SQLite y BigQuery
   - CSV: Eche un vistazo a esto [Clientes de tarjetas de crédito](https://www.kaggle.com/sakshigoyal7/credit-card-customers) conjunto de datos que contiene información de 10.000 clientes, incluida la edad, el salario, el estado civil, el límite de la tarjeta de crédito, la categoría de la tarjeta de crédito, etc. (CC0: Dominio público, Sakshi Goyal). 
   - JSON: Eche un vistazo a este Conjunto de datos JSON de [vídeos trending de YouTube](https://www.kaggle.com/datasnaek/youtube-new) (CC0: dominio público, Mitchell J).
   - SQLite: Eche un vistazo a este Conjunto de datos SQLite para 24 años de [Datos sobre incendios forestales en EE.UU](https://www.kaggle.com/rtatman/188-million-us-wildfires) (CC0: dominio público, Rachael Tatman).
   - BigQuery: Eche un vistazo a este[ Google Analytics 360](https://www.kaggle.com/bigquery/google-analytics-sample) conjunto de datos de muestra de la tienda Google Merchandise (CC0 Dominio público, Google BigQuery).

   - Consulte la documentación de Kaggle [documentación sobre conjuntos de datos](https://www.kaggle.com/docs/datasets) para obtener más información y busque y explore conjuntos de datos por su cuenta en [kaggle.com/datasets](https://www.kaggle.com/datasets).
   - ASÍ COMO CON CUALQUIER OTRO TIPO DE CONJUNTO DE DATOS, esté atento a los datos duplicados y a los "Nulos" en los conjuntos de datos abiertos.
      - Nulo suele significar que un campo de datos no se asignó (se dejó vacío), pero a veces Nulo puede interpretarse como el valor, 0.
      - Es importante entender cómo se utilizó Nulo antes de empezar a analizar un conjunto de datos con datos Nulos. 

- Puntos clave
   - Mientras trabaja en proyectos de análisis de datos, a menudo pueden utilizarse datos proxy para estimar o predecir resultados cuando no se dispone de datos reales.
   - Los conjuntos de datos abiertos o públicos pueden utilizarse como fuentes de datos proxy, y hay muchos repositorios en línea disponibles para encontrar conjuntos de datos relevantes.
   - Pero sea prudente al utilizar datos proxy y asegúrese de que se adaptan bien al propósito previsto.
   - Por último, compruebe si hay Datos duplicados y valores Nulos en los conjuntos de datos abiertos antes de utilizarlos para el análisis.