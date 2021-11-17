# Tener una capa de Negocio

* Estado: Aceptada.
* Decisores: Alejandro Fernández, Gabriel Villasevil.
* Fecha: 16/11/2021

## Contexto y problema

Es necesario una capa para gestionar los microservicios

## Motivos de la decisión.

* Motivación 1: [Decision 12.2](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%2012.2.md)
* Motivacion 2: [Requisito 3](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3%20Integrar%20Microservicios.txt)
* Motivacion 3: [Requisito 4](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R4%20Conectar%20con%20el%20Sistema%20de%20pago.txt)
* Motivacion 4: [Requisito 5](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R5%20Sistema%20de%20Mensajería.txt)

## Opciones consideradas.

* Opción 1: Tener una capa de Negocio para poder integrar los microservicos, conectar con el sistema de pago y tener implementado el sistema de mensajería

## Decisión resultante.

Opción escogida: "Opción 1", Al decidir el estilo principal como capas podemos implementar una capa dedicada al negocio para que se conecte con el usuario y las BBDD.

### Consecuencias positivas

* Añadir una capa enteramente dedicada al negocio.

### Consecuencias negativas

* Rehacer el estilo principal de la practica para poder implementarlo.
