# Patron creacional de la aplicación basado en el patrón Builder.

* Estado: Rechazada
* Decisores: Alejandro Fernandez, Gabriel Villasevil
* Fecha: 2021-10-31.

# Contexto y problema.

La aplicación ha de tener una entidad centralizada por lo que necesitamos gestionar bien las instancias que se tengan de la aplicación.

## Opciones Consideradas.

* [Opción 1](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%202.1.md): Singleton.
* [Opción 2](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%202.2.md): Builder.

## Decisión Final.

Chosen option: "[Opción 1](https://github.com/santo2927/DAS-2021-22-/edit/master/Decisión%20de%20diseño%202.1.md)", porque su implementación es simple y clara sobre como mantener una unica instancia del sistema, lo cual es suficiente para la gestión total del mismo.

### Consecuencias positivas.

* Se podría abstraer la creación de instancias y manejarlo con más versatilidad.
* La implementación del diseño es más amigable para su uso y manipulación.

### Consecuencias Negativas.

* Su diseño es más complejo y no asegura la existencia de una unica instancia.
