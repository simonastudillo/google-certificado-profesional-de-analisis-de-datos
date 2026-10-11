- Si crea una tabla de base de datos e incluye una clave primaria, ¿qué puntos deben ser ciertos sobre la clave primaria? Seleccione todo lo que corresponda.
   - [x] Su valor no es nulo ni está en blanco
   - [ ] Tiene un valor numérico
   - [ ] No es una clave foránea en otra tabla
   - [x] Es Único
> Si crea una tabla de base de datos con una clave primaria, ésta debe ser única y su valor no debe ser nulo ni estar en blanco.

- En una base de datos de empresa existente, la tabla Clientes contiene las siguientes columnas: CustomerId, FirstName, LastName, Company, Address, City, State, Country, PostalCode, Phone, Fax, Email y SupportRepId.
- Cree una consulta que devuelva todas las columnas de la tabla de clientes sólo para los clientes de Alemania.
```sql
SELECT *
FROM customers
WHERE Country = 'Germany'
```
```sql
+------------+-----------+------------+---------+-------------------------+-----------+-------+---------+------------+------------------+------+---------------------------+--------------+
| CustomerId | FirstName | LastName   | Company | Address                 | City      | State | Country | PostalCode | Phone            |  Fax | Email                     | SupportRepId |
+------------+-----------+------------+---------+-------------------------+-----------+-------+---------+------------+------------------+------+---------------------------+--------------+
|          2 | Leonie    | Köhler     |    None | Theodor-Heuss-Straße 34 | Stuttgart |  None | Germany | 70174      | +49 0711 2842222 | None | leonekohler@surfeu.de     |            5 |
|         36 | Hannah    | Schneider  |    None | Tauentzienstraße 8      | Berlin    |  None | Germany | 10789      | +49 030 26550280 | None | hannah.schneider@yahoo.de |            5 |
|         37 | Fynn      | Zimmermann |    None | Berger Straße 10        | Frankfurt |  None | Germany | 60316      | +49 069 40598889 | None | fzimmermann@yahoo.de      |            3 |
|         38 | Niklas    | Schröder   |    None | Barbarossastraße 19     | Berlin    |  None | Germany | 10779      | +49 030 2141444  | None | nschroder@surfeu.de       |            3 |
+------------+-----------+------------+---------+-------------------------+-----------+-------+---------+------------+------------------+------+---------------------------+--------------+
```
- What is the last name of the customer in the second row of the results returned from the query? 
   - Schneider
> Great job. Schneider is the last name of the customer in the second row returned when making the following query:
> SELECT * FROM customers WHERE Country = 'Germany'