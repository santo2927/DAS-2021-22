# Patrón circuit breaker para limitar de manera segura el límite de intentos de compra.

* Estado: Aceptada.
* Decisores: Alejandro Fernández, Gabriel Villasevil.
* Fecha: 12/11/2021

## Es necesario un sistema que gestione las solicitudes de los usuarios al sistema.

## Motivos de la decisión.

* Motivación 1: [Requisito 9](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R9%20Limite%20de%20intentos%20de%20compras.txt)

## Opciones consideradas.

* Opción 1: Patrón circuit breaker.

## Decisión resultante.

Opción escogida: "Opción 1", Porque el patrón circuit breaker cumple de manera muy eficiente con nuestro objetivo, limitar en un microservicio el número de compras del usuario.

### Consecuencias positivas

* Cumple con precisión uno de los requisitos de nuestro proyecto.

### Consecuencias negativas

* Su implementación y diseño son algo complejos.
