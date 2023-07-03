## Proyecto - Currency Beacon
Este proyecto consiste en cargar información relacionada con tipos de cambio de monedas desde la API de Currency Beacon y realizar diversas tareas con ella. A continuación, se describen las consignas a seguir:

- Crear una base de datos en Snowflake.
  
 - Origen: Utilizar la API de Currency Beacon para obtener la información necesaria. Consultar la documentación en https://currencybeacon.com/api-documentation.

- Cargar en Snowflake: Cargar los siguientes datos en la base de datos Snowflake:

- Catálogo de tipo de monedas. 
- Tipos de cambio del mes de junio.
- Carga en tiempo real: Realizar 5 cargas en tiempo real de la información y distinguir cada carga para poder identificar diferencias a lo largo del tiempo. Realizar una carga cada hora.

- Enviar correo de notificación: Enviar un correo electrónico al finalizar cada carga en tiempo real.

- Generar reporte: Generar un reporte que incluya un archivo adjunto con la información sobre el día con la tasa de cambio más alta para cada una de las monedas.

- Procedimiento y vista histórica: Crear un procedimiento que genere una vista con el histórico de las tasas de cambio y las descripciones de cada tipo de moneda disponible.

- Cargar en MySQL: Cargar la vista generada anteriormente en un servidor de MySQL.

- Notificar carga en MySQL: Enviar una notificación por correo electrónico para informar sobre la carga exitosa en la base de datos MySQL.

Plus:

- Enviar notificación vía API WhatsApp: Enviar una notificación vía API de WhatsApp para informar sobre la carga exitosa en la base de datos MySQL.

## Adjunto se encuentran:

- En imagenes estan las tablas creadas y la base de datos en Snowflake.
- max_tasas_cambio.csv es el archivo que se envia por mail.
- proyecto_28_6 es el codigo creado.
