# Estilo Modelo Vista Controlador para manejar las distintas funcionalidades de la aplicación

* Estado: Aceptada
* Decisores: Alejandro Fernandez, Gabriel Villasevil
* Fecha: 27/10/2021
## Contexto y problema

Necesitamos un estilo principal para diseñar el proyecto

## Motivos de la decisión

* Motivación 1: [Requisito 1 (MODELO)](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R1%20Realizar%20Pedido.txt)
* Motivacion 2: [Requisito 2 (MODELO)](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R2%20Realizar%20Devolución.txt)
* Motivación 3: [Requisito 8 (VISTA)](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R8%20Control%20de%20Interfaz.txt)
* Motivación 4: [Requisitos 3.3 (CONTROLADOR)](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.3%20Gestionar%20Solicitudes.txt)

## Opciones Consideradas

* Opción 1: [Modelo Vista Controlador](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.1.md)
* Opción 2: [Cliente-servidor](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.2.md)
* Opción 3: [Pizarra](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.3.md)

## Decisión Final

Chosen option: "[Opción 1](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.1.md)", porque lo modemos modelar integramente como modelos, vistas y controladores cubriendo todo.

### Consecuencias Positivas 

* El diseño a alto nivel es compartimentado en tres grandes bloques fáciles de entender y abstraer su funcionalidad
* A la hora de la implementación, una buena modularización hará que los programadores tengan facilidades para trabajar en grupo dividiendose de manera óptima el trabajo
* La mayoría de los requisitos del cliente están recogidos bajo este estilo.

### Consecuencias Negativas

* Aún quedan requisitos que tendrán que estar fuera de este estilo, al no ser amparados por este.
