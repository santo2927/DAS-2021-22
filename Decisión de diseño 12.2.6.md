# Tener una capa de Microservicios.

* Estado: Aceptada.
* Decisores: Alejandro Fernández, Gabriel Villasevil.
* Fecha: 2021-11-16.

## Contexto y problema.

Es necesario una capa para gestionar los distintos microservicios.

## Motivos de la decisión.

* Motivación 1: Modelar los distitos microservicios que son gestionados por la aplicación.

## Opciones consideradas.

* Opción 1: Tener una capa dedicada a los distintos microservicios que son usados por el sistema.

## Decisión resultante.

Opción escogida: "Opción 1", Al decidir el estilo principal como capas podemos implementar una capa dedicada a los distintos microservicios usados por la capa de Negocio.

### Consecuencias positivas.

* Añadir una capa enteramente dedicada a los microservicios y la comunicación con ellos.

### Consecuencias negativas.

* Rehacer el estilo principal de la practica para poder implementarlo.
