# Estilo Cliente-Servidor para manejar las distintas funcionalidades de la aplicación

* Estado: Rechazada
* Decisores: Alejandro Fernandez, Gabriel Villasevil
* Fecha: 2021-10-27

## Motivos de la decisión

* Motivación 1: [Requisitos 1](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R1%20Realizar%20Pedido.txt)
* Motivación 2: [Requisito 2](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R2%20Realizar%20Devolución.txt)
* Motivación 3: [Requisito 4](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R4%20Conectar%20con%20el%20Sistema%20de%20pago.txt)

## Opciones Consideradas

* Opción 1: [Modelo Vista Controlador](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.1.txt)
* Opción 2: [Cliente-servidor](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.2.txt)
* Opción 3: [Pizarra](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.3.txt)
* Opción 4: [Capas](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.4.txt)

## Decisión Final

Chosen option: "[Opción 4](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.4.txt)", Debido a las distintas motivaciones enumeradas anteriormente seleccionamos como estilo principal el estilo de capas.

### Consecuencias Positivas 

* En el modelo Cliente-servidor toda la funcionalidad referente a las interacciones entre el cliente y el sistema sería recogidas de manera mucho más eficaz. Cómo el sistema de mensajería.
* Los pedidos y las devoluciones podrían gestionarse eficientemente siguiendo este estilo.

### Consecuencias Negativas

* Aunque en interacciones entre el cliente y el sistema este modelo es muy bueno, una vez fuera de éstas queda poco representativo para el problema que estamos tratando de resolver.
