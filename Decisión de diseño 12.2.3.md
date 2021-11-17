# Tener capa de seguridad.

* Estado: Aceptada.
* Decisores: Alejandro Fernández, Gabriel Villasevil.
* Fecha: 2021-11-16.

## Contexto y problema

Es necesario una capa de seguridad para nuestro sistema.

## Motivos de la decisión.

* Motivación 1: [Requisito 6](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R6%20Sistema%20de%20Seguridad.txt).
* Motivación 2: [Decision 12.2](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%2012.2.md).

## Opciones consideradas.

* Opción 1: Capa de seguridad mediante el estilo principal.

## Decisión resultante.

Opción escogida: "Opción 1", Al decidir el estilo principal como capas podemos implementar la seguridad como una capa entre Usuario y Negocio.

### Consecuencias positivas.

* Añadir una capa enteramente dedicada a la seguridad haría un sistema realmente muy seguro.

### Consecuencias negativas.

* Rehacer el estilo principal de la practica para poder implementarlo.
