# Tener una capa de Bases de Datos

* Estado: Aceptada.
* Decisores: Alejandro Fernández, Gabriel Villasevil.
* Fecha: 16/11/2021

## Es necesario una capa para gestionar los microservicios

## Motivos de la decisión.

* Motivación 1: [Requisito 3.1](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.1%20Almacenar%20Preferencias.txt)
* Motivación 2: [Requisito 3.2](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.2%20Almacenar%20Datos%20de%20Compra.txt)
* Motivación 3: [Requisito 3.4](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.4%20Almacenar%20Lolalización%20de%20Microservicios.txt)
* Motivación 4: [Requisito 7](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R7%20Acceso%20a%20Bases%20de%20Datos.txt)
* Motivación 5: [Decisión 1.4](https://github.com/santo2927/DAS-2021-22-/blob/master/Decisión%20de%20diseño%201.4.md)

## Opciones consideradas.

* Opción 1: Tener una capa dedicada a la comunicación con las dos bases de datos SQL(MongoDB) y NoSQL(Azure)

## Decisión resultante.

Opción escogida: "Opción 1", Al decidir el estilo principal como capas podemos implementar una capa dedicada a las bases de datos para que se conecten con el negocio, dando como resultado dos bases de datos, una SQL MongoDB para los usuarios, los productos y los microservicios y, una base de datos NoSQL Azure que almacene las preferencias de los clientes.

### Consecuencias positivas

* Añadir una capa enteramente dedicada a las bases de datos y la comunicación con las mimsamas.

### Consecuencias negativas

* Rehacer el estilo principal de la practica para poder implementarlo.
