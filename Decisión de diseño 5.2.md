# Base de datos MongoDB para almacenar los microservicios con tectología de mensajería RabbitMQ.

* Estado: Rechazada.
* Decisores: Alejandro Fernandez, Gabriel Villasevil.
* Fecha: 02/11/2021.

## Contexto y problema

Es necesaria una base de datos que almacene la localización de los distintos microservicios.

## Motivos de la decisión.

* Motivación 1: [Requisito 3.4](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.4%20Almacenar%20Lolalización%20de%20Microservicios.txt)

## Opciones consideradas.

* [Opción 1](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%205.1.md): Base de datos MongoDB para almacenar los microservicios con bus dedicado Azure Service Bus.
* [Opción 2](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%205.2.md): Base de datos MongoDB para almacenar los microservicios con tectología de mensajería RabbitMQ.

## Decisión resultante.

Opción escogida: "[Opción 1](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%205.1.md)", Por la escalabilidad y la persistencia de Azure.

### Consecuencias positivas

* Integrado junto con Docker y Kubernetes es el sistema más portable para diferentes infraestructuras.

### Consecuencias negativas

* Existen reportes de fallos de persistencia y escalabilidad en relación con Azure.
