---
title: Diseño y diagrama de clases
---

# Diseño del sistema

La aplicación se organiza en clases que representan las tareas y la gestión de estas.

## Clase Tarea

Atributos:

- id: identificador de la tarea.
- titulo: nombre de la tarea.
- descripcion: información adicional.
- completada: indica si la tarea está terminada.

## Clase GestorTareas

Responsabilidades:

- Crear tareas.
- Mostrar las tareas guardadas.
- Actualizar el estado de una tarea.
- Eliminar tareas.

## Relación entre clases

La clase GestorTareas administra una colección de objetos de la clase Tarea.
