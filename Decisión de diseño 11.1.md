# Decisión final de bases de datos

* Estado: Aceptada.
* Decisores: Alejandro Fernández, Gabriel Villasevil.
* Fecha: 15/11/2021

## Es necesario un sistema que gestione las solicitudes de los usuarios al sistema.

## Motivos de la decisión.

* Motivación 1: [Decisión 3.1](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%203.1.md)
* Motivación 2: [Decisión 5.1](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%205.1.md)
* Motivacion 3: [Requisito 3.1](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.1%20Almacenar%20Preferencias.txt)

## Opciones consideradas.

* Opción 1: Dos bases de datos, una SQL MongoDB para los usuarios, los productos y los microservicios y, una base de datos NoSQL Azure que almacene las preferencias de los clientes

## Decisión resultante.

Opción escogida: "Opción 1", Para cumplir con el patrón ya establecido por el anterior diseño.

### Consecuencias positivas

* Cumple con precisión los requisitos del proyecto.

### Consecuencias negativas

* Interconexión entre las BBDD puede desembocar en datos repetidos.
