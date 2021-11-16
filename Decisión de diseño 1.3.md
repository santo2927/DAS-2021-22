# Estilo Pizarra para manejar las distintas funcionalidades de la aplicación

* Estado: Rechazada
* Decisores: Alejandro Fernandez, Gabriel Villasevil
* Fecha: 2021-10-27

## Motivos de la decisión

Motivación 1: [Requisito 3.1](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.1%20Almacenar%20Preferencias.txt) (Seria parte de la pizarra)
Motivacion 2: [Requisito 3.2](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.2%20Almacenar%20Datos%20de%20Compra.txt) (Seria parte de la pizarra)
Motivacion 3: [Requisito 3.4](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.4%20Almacenar%20Lolalización%20de%20Microservicios.txt) (Seria parte de la pizarra)
Motivacion 4: [Requisito 3.5](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.5%20Comunicación%20Cliente-Microservicio.txt) (Seria parte de la pizarra)
Motivación 5: Resto de requisitos (Estos se cumplirían obteniendo los datos de la pizarra ya sea para por ejemplo mostrar la interfaz, o para obtener datos de la base de datos)

## Opciones Consideradas

* Opción 1: [Modelo Vista Controlador](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.1.txt)
* Opción 2: [Cliente-servidor](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.2.txt)
* Opción 3: [Pizarra](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.3.txt)
* Opción 4: [Capas](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.4.txt)

## Decisión Final

Chosen option: "[Opción 4](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.4.txt)", Debido a las distintas motivaciones enumeradas anteriormente seleccionamos como estilo principal el estilo de capas.

### Consecuencias Positivas 

* El diseño en pizarra todos los requisitos de la aplicación.

### Consecuencias Negativas

* Aunque cubra todos los requisitos lo hace desde un punto de vista de muy alto nivel, es decir, el nivel de detalle en cómo cumple los requisitos el modelo en pizarra sería demasiado bajo para un problema tan complejo como el que estamos trabajando.
