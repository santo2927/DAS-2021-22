# Sistema de roles sin patrón establecido para acceder a los distintos recursos.

* Estado: Rechazada.
* Decisores: Alejandro Fernández, Gabriel Villasevil.
* Fecha: 2021-11-17.

## Contexto y problema.

Es necesario controlar los permisos de los usuarios en la aplicación.

## Motivos de la decisión.

* Motivación 1: [Requisito 6](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.3%20Gestionar%20Solicitudes.txt).
* Motivacion 2: [Decision 12.2.4](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%2012.2.4.md).

## Opciones consideradas.

* [Opción 1](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%2016.1.md): Patrón autenticator para la gestión de seguridad del sistema.
* [Opción 2](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%2016.2.md): Sistema de roles sin patrón establecido para acceder a los distintos recursos.

## Decisión resultante.

Opción escogida: "[Opción 1](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%2016.1.md)", porque tenemos una mayor seguridad a la hora de asegurarnos que el usuario accede solo a los recursos tiene permitidos.

### Consecuencias positivas.

* Cada clase maneja sus roles y sus accesos.

### Consecuencias negativas.

* Demasiada descentralización y mayor probabilidad de fallo ante que un usuario acceda a algún recurso que no queremos que acceda.
