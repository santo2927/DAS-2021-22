# Base de datos para almacenar los recursos activos conectado a un servidor WEB.

* Estado: Aceptada.
* Decisores: Alejandro Fernández, Gabriel Villasevil.
* Fecha: 02/11/2021

## Es necesaria una base de datos que almacene los distintos tipos de recursos activos.

## Motivos de la decisión.

* Motivación 1: [Decisión 3.1.1](https://github.com/santo2927/DAS-2021-22/edit/master/Decisión%20de%20diseño%203.1.1.md).
* Motivación 2: Los microservicios deberán usar el protocolo REST.
* Motivación 3: [Decisión 5.1](https://github.com/santo2927/DAS-2021-22/edit/master/Decisión%20de%20diseño%205.1.txt)


## Opciones consideradas.

* Opción 1: Base de datos para almacenar los recursos activos conectado a un servidor WEB.

## Decisión resultante.

Opción escogida: "Opción 1", porque nos permite realizar una correcta gestión de los diferentes tipos de recursos activos.

### Consecuencias positivas

* Se cumplen los requisitos del sistema.
* Disponemos de un acceso común para la gestión de todos los recursos activos.
* A través de la conexión BBDD-Web podemos acceder con facilidad a los distintos recursos

### Consecuencias negativas

* Es complejo de implementar.
