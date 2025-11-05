<<<<<<< HEAD
# Proyecto Sprint 5
Trabajas como analista para el operador de telecomunicaciones Megaline. La empresa ofrece a sus clientes dos tarifas de prepago, Surf y Ultimate. El departamento comercial quiere saber cuál de los planes genera más ingresos para poder ajustar el presupuesto de publicidad.
##
Vas a realizar un análisis preliminar de las tarifas basado en una selección de clientes relativamente pequeña. Tendrás los datos de 500 clientes de Megaline: quiénes son los clientes, de dónde son, qué tarifa usan, así como la cantidad de llamadas que hicieron y los mensajes de texto que enviaron en 2018. Tu trabajo es analizar el comportamiento de los clientes y determinar qué tarifa de prepago genera más ingresos. Más adelante, encontrarás en las instrucciones del proyecto cuáles son exactamente los aspectos del comportamiento de los clientes que debes analizar. Determinar qué plan, en promedio, aporta más ingresos es una cuestión que se abordará mediante pruebas estadísticas. Más adelante encontrarás más información al respecto en la sección de instrucciones del proyecto.
##
## Descripción de las tarifas
Nota: Megaline redondea los segundos a minutos y los megabytes a gigabytes. Para las llamadas, cada llamada individual se redondea: incluso si la llamada duró solo un segundo, se contará como un minuto. Para el tráfico web, las sesiones web individuales no se redondean. En vez de esto, el total del mes se redondea hacia arriba. Si alguien usa 1025 megabytes este mes, se le cobrarán 2 gigabytes.
##
A continuación la descripción de las tarifas:
#
### Surf
1. Pago mensual: $20.
2. 500 minutos al mes, 50 SMS y 15 GB de datos.
3. Si se exceden los límites del paquete:
- 1 minuto: 3 centavos.
- 1 SMS: 3 centavos.
- 1 GB de datos: $10.
#
### Ultimate
1. Pago mensual: $70.
2. 3000 minutos al mes, 1000 SMS y 30 GB de datos.
3. Si se exceden los límites del paquete:
- 1 minuto: 1 centavo.
- 1 SMS: 1 centavo.
- 1 GB de datos: $7.
###
## Diccionario de datos
En este proyecto, se trabajará con cinco tablas diferentes.
#
1. La tabla **users** (datos sobre los usuarios):
- 'user_id': identificador único del usuario.
- 'first_name': nombre del usuario.
- 'last_name': apellido del usuario.
- 'age': edad del usuario (en años).
- 'reg_date': fecha de suscripción (dd, mm, aa).
- 'churn_date': la fecha en la que el usuario dejó de usar el servicio (si el valor es ausente, la tarifa se estaba usando cuando fue extraída esta base de datos).
- 'city': ciudad de residencia del usuario.
- 'plan': nombre de la tarifa.
=======
# Project-Sprint-5
>>>>>>> 06b01f09ca75b28631bd332c6bca4295