# Modelar las comunicaciones cliente-microsesrvicio dentro del estilo MVC

* Estado: rechazada.
* Decisores: Alejandro Fernández, Gabriel Villasevil.
* Fecha: 09/11/2021

## Es necesario que exista comunicación entre el sistema (los clientes) y los microservicios.

## Motivos de la decisión.

* Motivación 1: [Requisito 3.4](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.4%20Almacenar%20Lolalización%20de%20Microservicios.txt)
* Motivación 2: [Requisito 3.5](https://github.com/santo2927/DAS-2021-22-/blob/master/Requisitos/R3.5%20Comunicación%20Cliente-Microservicio.txt)

## Opciones consideradas.

* [Opción 1](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%207.1.md): Estilo Cliente-Servidor.
* [Opción 2](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%207.2.md): Integrar los microservicios dentro del MVC.
* [Opción 3](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%207.3.md): Estilo Rest.

## Decisión resultante.

Opción escogida: "[Opción 1](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%207.1.md)", Porque a la hora de gestionar las solicitudes tener un mediador aumenta la escalabilidad de la funcionalidad de las solicitudes.

### Consecuencias positivas

* Mayor divisibilidad de elementos entre controlador-vista-modelo.

### Consecuencias negativas

* Implementar las comunicaciones cliente-microservicio dentro del estilo MVC sería romper con su idea modelo-vista-controlador.
