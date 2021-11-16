# Tener capa de seguridad.

* Estado: Aceptada.
* Decisores: Alejandro Fernández, Gabriel Villasevil.
* Fecha: 16/11/2021

## Es necesario una capa de seguridad para nuestro sistema.

## Motivos de la decisión.

* Motivación 1: [Requisito 6](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R6%20Sistema%20de%20Seguridad.txt)
* Motivación 2: [Decision 1.4](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.4.md)

## Opciones consideradas.

* [Opción 1](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%201.4.3.md): Capa de seguridad mediante el estilo principal
* [Opción 2](): Gestionar el sistema de seguridad mediante hasheo de contraseñas en la base de datos.

## Decisión resultante.

Opción escogida: "[Opción 1](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%201.4.3.md)", Al decidir el estilo principal como capas podemos implementar la seguridad como una capa entre Usuario y Negocio.

### Consecuencias positivas

* Añadir una capa enteramente dedicada a la seguridad haría un sistema realmente muy seguro.

### Consecuencias negativas

* Rehacer el estilo principal de la practica para poder implementarlo.
