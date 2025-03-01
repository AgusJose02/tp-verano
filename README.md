# QuickesTicket

## Grupo

### Integrantes

- 49740 - José, Agustín

### Repositorios

- [front-end](https://github.com/AgusJose02/quickesticket-fe)
- [back-end](https://github.com/AgusJose02/quickesticket-be)

## Tema

### Descripción

Ticketera en la que se podrá llevar registro de la cantidad de horas realizadas en tareas asignadas. Se podrá crear proyectos, crear tickets pertenecientes a un proyecto, actualizar el estado de los mismos y cargar las horas dedicadas.

### Modelo

![imagen del modelo](https://raw.githubusercontent.com/AgusJose02/quickesticket/refs/heads/main/quickesticket_final.png)

| Req                     | Detalle                                                                                                         |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------- |
| CRUD simple             | 1. CRUD Proyecto <br>2. CRUD Usuario<br>                                                                        |
| CRUD dependiente        | 1. CRUD Ticket {depende de} CRUD Proyecto<br>2. CRUD Horas {depende de} CRUD Ticket                             |
| Listado<br>+<br>detalle | 1. Listado de tickets pendientes => detalle ticket<br> 2. Listado de horas en la última semana => detalle horas |
| CUU/Epic                | 1. Crear un Ticket<br>2. Cargarle horas a un ticket                                                             |
