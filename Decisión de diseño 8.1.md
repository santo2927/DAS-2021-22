# Patrón mediator para el sistema de gestión de solicitudes.

* Estado: Aceptada.
* Decisores: Alejandro Fernández, Gabriel Villasevil.
* Fecha: 09/11/2021

## Es necesario un sistema que gestione las solicitudes de los usuarios al sistema.

## Motivos de la decisión.

* Motivación 1: [Requisito 3.3](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.3%20Gestionar%20Solicitudes.txt)

## Opciones consideradas.

* [Opción 1](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%208.1.md): patrón mediator para mediar entre los usuarios y el sistema mientras se realizan las solicitudes.
* [Opción 2](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%208.2.md): gestionar las solicitudes en el propio sistema.

## Decisión resultante.

Opción escogida: "[Opción 1](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%208.1.md)", Porque a la hora de gestionar las solicitudes tener un mediador aumenta la escalabilidad de la funcionalidad de las solicitudes.

### Consecuencias positivas

* Se podrá escalar la funcionabilidad del sistema de solicitudes de forma más eficiente.

### Consecuencias negativas

* Añadir un paso entre el usuario y el sistema para controlar las solicitudes de manera eficiente podría ralentizar el proceso levemente.
