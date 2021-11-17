# Gestionar las solicitudes directamente desde el sistema.

* Estado: Rechazada.
* Decisores: Alejandro Fernández, Gabriel Villasevil.
* Fecha: 09/11/2021

## Contexto y problema

Es necesario un sistema que gestione las solicitudes de los usuarios al sistema.

## Motivos de la decisión.

* Motivación 1: [Requisito 3.3](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.3%20Gestionar%20Solicitudes.txt)

## Opciones consideradas.

* [Opción 1](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%202.1.md): patrón mediator para mediar entre el usuario y el sistema mientras se realizan las solicitudes.
* [Opción 2](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%202.2.md): gestionar las solicitudes en el propio sistema (sin patrón mediator).

## Decisión resultante.

Opción escogida: "[Opción 1](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%202.1.md)", Porque a la hora de gestionar las solicitudes tener un mediador aumenta la escalabilidad de la funcionalidad de las solicitudes.

### Consecuencias positivas

* Gestionar las solicitudes desde el sistema sin mediar podría acelerar levemente el proceso.

### Consecuencias negativas

* La escalabilidad es reducida, ya que para añadir funcionalidades al sistema de gestión de solicitudes habría que modificar al mismo tiempo los campos de la base de datos y las funcionalidades del sistema.
