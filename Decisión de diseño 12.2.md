# Estilo por capas para manejar las distintas funcionalidades de la aplicación
* Estado: Aceptada
* Decisores: Alejandro Fernandez, Gabriel Villasevil
* Fecha: 2021-11-16

## Motivos de la decisión

* Motivación 1: Añadir una capa enteramente dedicada a la seguridad haría un sistema realmente muy seguro.
* Motivación 2: Al dividir por capas es más fácil cumplir con los requisitos capturados.
* Motivación 3: El sistema estaba anteriormente basado en una arquitectura Web de tres capas.
* Motivación 4: [Capa de Usuario](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.4.1.md)
* Motivación 5: [Capa de Negocio](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.4.2.md)
* Motivación 6: [Capa de Seguriad](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.4.3.md)
* Motivación 7: [Capa de Bases de Datos](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.4.4.md)

## Opciones Consideradas

* Opción 1: [Modelo Vista Controlador](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%2012.1.md)
* Opción 2: [Capas](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%2012.2.md)

## Decisión Final

Chosen option: "[Opción 2](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%2012.2.md)", Debido a las distintas motivaciones enumeradas anteriormente seleccionamos como estilo principal el estilo de capas.

### Consecuencias Positivas 

* El diseño a alto nivel es compartimentado en capas fáciles de entender y abstraer su funcionalidad.
* A la hora de la implementación, una buena modularización hará que los programadores tengan facilidades para trabajar en grupo dividiendose de manera óptima el trabajo.
* La mayoría de los requisitos del cliente están recogidos bajo este estilo.

### Consecuencias Negativas

* Hay que cambiar trabajo ya realizado sobre el estilo MVC.
