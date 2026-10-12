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

---

## Determinar el mejor tamaño de la Muestra
- ​Me alegro de volver a verte.
- ​En este vídeo, profundizaremos en el ​tamaño de las muestras y la integridad de los datos.
- ​Si alguna vez has estado en una tienda que ​reparte muestras, sabes que es uno de los pequeños placeres de la vida.
- ¡ ​Para mí, de todos modos! ​esas pequeñas muestras también son una forma muy inteligente para que ​las empresas obtengan más información sobre sus productos de la mano de ​los clientes sin tener que darles a todos una muestra gratuita.
- ​Muchas organizaciones utilizan el tamaño de la muestra de manera similar.
- ​Toman una parte de algo más grande.

- ​En este caso, una muestra de una población.
- ​En ocasiones, realizan pruebas complejas con ​sus datos para comprobar si cumplen sus objetivos empresariales.
- ​No vamos a analizar todos los cálculos ​necesarios para hacerlo de forma eficaz.
- ​En su lugar, nos centraremos en una «visión general» ​del proceso y de lo que implica.
- ​Como recordatorio rápido, el ​tamaño de la muestra es una parte de ​una población que es representativa de la población.
- ​Para las empresas, es una herramienta muy importante.
- ​Analizar una población completa de datos puede resultar caro y llevar mucho tiempo.

- ​Usar el tamaño de ​la muestra suele ser lo más lógico y aún puede ​conducir a hallazgos válidos y útiles.
- ​Hay calculadoras útiles ​en línea que pueden ayudarlo a encontrar el tamaño de la muestra.
- ​Debe introducir el nivel de confianza, el ​tamaño de la población y el margen de error.
- ​Ya hemos hablado del tamaño de la población.
- ​Para basarnos en eso, aprenderemos sobre el ​nivel de confianza y el margen de error.
- ​Conocer estos conceptos le ayudará a ​entender por qué los necesita para calcular el tamaño de la muestra.
- ​El nivel de confianza es la probabilidad de que la ​muestra refleje con precisión la población en general.

- ​Puedes considerarlo de la ​misma manera que la confianza en cualquier otra cosa.
- ​Es la fuerza con la que sientes que ​puedes confiar en algo o en alguien.
- ​Tener un nivel de confianza del 99 por ciento es ideal.
- ​Sin embargo, la mayoría de las industrias esperan un ​nivel de confianza de al menos un 90 o 95 por ciento.
- ​Las industrias como la farmacéutica ​suelen querer un nivel ​de confianza lo más alto posible cuando ​utilizan un tamaño de muestra.
- ​Esto tiene sentido porque ​están probando medicamentos y necesitan ​asegurarse de que funcionan y son seguros para todos.
- ​Para otros estudios, ​es posible que las organizaciones solo necesiten saber que ​los resultados de las pruebas o encuestas ​indican que van en la dirección correcta.

- ​Por ejemplo, si una empresa de pinturas ​está probando nuevos colores, ​un nivel de confianza más bajo está bien.
- ​También debes tener en cuenta ​el margen de error de tu estudio.
- ​Pronto aprenderá más sobre esto, ​pero básicamente le indica qué tan ​cerca están los resultados del tamaño de la muestra de lo que ​serían sus resultados si utilizara ​toda la población que representa el tamaño de la muestra.
- ​Piénsalo así.
- ​Supongamos que el director de ​una escuela secundaria se acerca a ti ​con un estudio sobre las preferencias de los estudiantes en cuanto a caramelos.
- ​Necesitan conocer el ​tamaño de muestra apropiado y lo necesitan ahora.
- ​La escuela tiene una población estudiantil de 500 ​y piden un nivel de confianza del ​95 por ciento y un margen de error del 5 por ciento.

- ​Hemos configurado una calculadora en una hoja de cálculo, ​pero también puedes encontrar fácilmente este tipo de calculadora ​buscando «calculadora de tamaño de muestra» en Internet.
- ​Al igual que esas calculadoras, ​nuestra calculadora de hojas de cálculo no muestra ninguno de ​los cálculos más complejos ​para calcular el tamaño de la muestra.
- ​Todo lo que necesitamos hacer es introducir ​los números de nuestra población, el ​nivel de confianza y el margen de error.
- ​Y cuando escribimos 500 para el tamaño de nuestra población, ​95 para nuestro porcentaje de nivel de confianza y ​5 para nuestro porcentaje de margen de error, ​el resultado es aproximadamente 218.
- ​Eso significa que para este estudio, ​un tamaño de muestra apropiado sería 218.
- ​Si encuestamos a 218 estudiantes y ​descubrimos que el 55 por ciento de ellos prefiere el chocolate, ​entonces podríamos estar bastante seguros ​de que eso sería cierto para los 500 estudiantes.
- ​218 es el número mínimo ​de personas que necesitamos encuestar según ​nuestros criterios de un nivel de confianza del 95 por ciento ​y un margen de error del 5 por ciento.
- ​En caso de que se lo pregunte, ​el nivel de confianza y el margen de error ​no tienen por qué sumar el 100 por ciento.

- ​Son independientes el uno del otro.
- ​Supongamos que cambiamos nuestro margen de error ​del 5 por ciento al 3 por ciento.
- ​Luego descubrimos que el tamaño de nuestra muestra ​tendría que ser mayor, ​alrededor de 341 en lugar de 218, ​para que los resultados del estudio fueran ​más representativos de la población.
- ​Siéntete libre de practicar con una calculadora en línea.
- ​Conocer el tamaño de la muestra y cómo ​encontrarla le ayudará cuando trabaje con datos.
- ​Estamos a punto de recibir más información útil, ​incluida la información sobre el margen de error.
- ¡Nos vemos pronto! 
- [Sample-Size-Calculator.xlsx](./resources/modulo-01/Sample-Size-Calculator.xlsx)

---

## Calculadora del tamaño de la Muestra
- En esta lectura aprenderá los conceptos básicos de las calculadoras del tamaño de la muestra, cómo utilizarlas y cómo entender los resultados.
- Una calculadora del tamaño de la muestra le indica a cuántas personas debe entrevistar (o qué cosas debe probar) para obtener resultados que representen a la población objetivo.
- Repasemos algunos términos con los que se encontrará al utilizar una calculadora del tamaño de la muestra:
   - Nivel de confianza: La probabilidad de que el tamaño de su muestra refleje con exactitud la población mayor.
   - Margen de error: La cantidad máxima que se espera que difieran los resultados de la muestra de los de la población real.
   - Población: Es el número total del que espera extraer su muestra.
   - Muestra: Parte de una población que es representativa de la misma.
   - Tasa de respuesta estimada: Si está realizando una encuesta a individuos, es el porcentaje de personas que espera que completen su encuesta de las que la recibieron.

- Cómo utilizar una calculadora del tamaño de la muestra
   - Para utilizar una calculadora del tamaño de la muestra, debe tener ya decididos el tamaño de la población, el nivel de confianza y el margen de error aceptable para poder introducirlos en la herramienta.
   - Si esta información está lista, consulte estas calculadoras del tamaño de la muestra a continuación:
      - [Calculadora del tamaño de la muestra de surveymonkey.com](https://www.surveymonkey.com/mp/sample-size-calculator/)
      - [Calculadora del tamaño de la muestra de raosoft.com](http://www.raosoft.com/samplesize.html)

- Qué hacer con los resultados
   - Una vez que haya introducido su información en una de estas calculadoras, ésta le dará un tamaño de muestra recomendado.
   - Tenga en cuenta que el tamaño de muestra calculado es el número mínimo para alcanzar lo que ha introducido para el nivel de confianza y el Margen de error.
   - Si está trabajando con una Encuesta, también tendrá que pensar en la tasa de respuesta estimada para calcular cuántas encuestas tendrá que enviar.
   - Por ejemplo, si necesita un tamaño de muestra de 100 individuos y su tasa de respuesta estimada es del 10%, tendrá que enviar su encuesta a 1.000 individuos para obtener las 100 respuestas que necesita para su análisis.
   - Ahora que ya tiene las nociones básicas, pruebe a hacer algunos cálculos con las calculadoras del tamaño de la muestra y vuelva a consultar esta lectura si necesita refrescar las definiciones.

---

## Ponga a prueba sus Conocimientos sobre la comprobación de sus Datos

1. Rellene el espacio en blanco: El Testeo de hipótesis es una forma de ver si una Encuesta o experimento tiene _____ resultados.
   - [x] significativo
   - [ ] insuficiente
   - [ ] al azar
   - [ ] probable
> Testeo de hipótesis es una forma de ver si una Encuesta o experimento tiene resultados significativos.

2. Un Equipo de investigación lleva a cabo un experimento para determinar si una nueva herramienta de ciberseguridad es más eficaz que la versión anterior. ¿Qué tipo de resultados se requieren para que el experimento sea estadísticamente significativo?
   - [ ] Resultados que son inexactos y deben ignorarse
   - [ ] Resultados que son hipotéticos y necesitan más pruebas
   - [x] Resultados reales y no causados por el azar 
   - [ ] Resultados que es poco probable que se repitan
> Para que un experimento sea estadísticamente significativo, los resultados deben ser reales y no debidos al azar.

3. Para tener un alto nivel de confianza en una Encuesta a clientes, ¿qué debe reflejar con exactitud el tamaño de la muestra?
   - [ ] Los miembros más valiosos de la población
   - [x] Toda la población
   - [ ] Predicciones de las partes interesadas
   - [ ] Las tendencias de anteriores encuestas a clientes
> Para tener un alto nivel de confianza en una Encuesta de clientes, el tamaño de la muestra debe reflejar con exactitud toda la población.

4. Rellene el espacio en blanco: Normalmente, un profesional de los Datos pretende alcanzar un Poder estadístico de al menos _____ para considerar sus resultados estadísticamente significativos.
   - [x] 0.8, o el 80
   - [ ] 0.1, o 10%
   - [ ] 1, o 100%
   - [ ] 0.6, o 60%
> Normalmente, un profesional de los datos pretende alcanzar una potencia estadística de al menos 0,8, es decir, un 80% para considerar sus resultados estadísticamente significativos.