# Tener una capa de Datos

* Estado: Aceptada.
* Decisores: Alejandro Fernández, Gabriel Villasevil.
* Fecha: 16/11/2021

## Es necesario una capa para gestionar los microservicios

## Motivos de la decisión.

* Motivación 1: Modelar los distitos datos que son gestionados por la aplicación.

## Opciones consideradas.

* Opción 1: Tener una capa dedicada a los distintos datos que son usados por el sistema.

## Decisión resultante.

Opción escogida: "Opción 1", Al decidir el estilo principal como capas podemos implementar una capa dedicada a los distintos datos que va a utilizar el sitema intermediando entre la capa de Negocio y la capa de Bases de Datos.

### Consecuencias positivas

* Añadir una capa enteramente dedicada a las bases de datos y la comunicación con las mimsamas.

### Consecuencias negativas

* Rehacer el estilo principal de la practica para poder implementarlo.
