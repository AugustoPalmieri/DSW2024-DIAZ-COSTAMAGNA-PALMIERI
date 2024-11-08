# Propuesta TP DSW

## Grupo
### Integrantes
* 48944- DIAZ, IÑAKI (com 301)
* 50735- COSTAMAGNA, RENZO (com 301)
* 51705- PALMIERI, AUGUSTO (com 304)

### Repositorios
*
* [frontend app](https://github.com/RenCostamagna/DSW-frontend)
* [backend app](https://github.com/RenCostamagna/DSW-backend)


## Tema
### Descripción
Sistema de atención y gestión para una hamburguesería con el objetivo de  facilitar el manejo de los recursos ya sean empleados, ingredientes, infraestructura, contemplando pedidos  takeaway o vía delivery.

### Modelo
![](https://github.com/AugustoPalmieri/DSW2024-DIAZ-COSTAMAGNA-PALMIERI/blob/main/DERDSW.drawio.png)

## Reglas de Negocio(provisorias)

* EL REGISTRO DE LOS CLIENTES ES UN NUMERO INCREMENTAL.

* TAKE AWAY NO HAY LIMITE.

 
* LOS PRECIOS NO CAMBIAN DE LAS HAMBURGUESAS AUNQUE SE QUITEN INGREDIENTES DE LA MISMA.


## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Hamburguesa(primer CRUD propuesta)<br>2. CRUD Servicio<br>3. CRUD Localidad|
|CRUD dependiente|1. CRUD Habitación {depende de} CRUD Tipo Habitacion<br>2. CRUD Cliente {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de habitaciones filtrado por tipo de habitación, muestra nro y tipo de habitación => detalle CRUD Habitacion<br> 2. Listado de reservas filtrado por rango de fecha, muestra nro de habitación, fecha inicio y fin estadía, estado y nombre del cliente => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|

