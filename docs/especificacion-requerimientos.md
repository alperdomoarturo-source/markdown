# Especificación de Requerimientos

## 1. Descripción del sistema

## 2. Integrantes

- Nombre:
- Nombre:
- Nombre:
- Nombre:
- Nombre:

## 3. Requerimientos Funcionales

### RF-01 - Registro de tutoría

#### Resumen
Permite a un profesor registrar una nueva tutoría académica en el sistema, proporcionando la información necesaria para que los estudiantes puedan encontrarla y inscribirse posteriormente.

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|
| codigoProfesor | String | Código identificador del profesor |
| tema | String | Tema de la tutoría |
| fecha | Date | Fecha en la que se realizará la tutoría |
| horaInicio | Time | Hora de inicio de la tutoría |
| cantidadMaxima | Integer | Cantidad máxima de estudiantes que pueden asistir |

#### Reglas o condiciones

- La fecha de la tutoría debe ser igual o posterior a la fecha actual.
- La cantidad máxima de participantes debe estar entre 1 y 10 estudiantes.
- El código de profesor debe ser válido y existir en el sistema.

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|
| identificadorTutoria | Integer | Identificador único asignado a la tutoría |
| mensajeConfirmacion | String | Mensaje que confirma la creación exitosa de la tutoría |

#### Resultado esperado
El sistema crea un nuevo registro de tutoría con un identificador único, almacena toda la información proporcionada por el profesor y notifica que la tutoría fue creada correctamente.


### RF-02 - Consulta de tutorías disponibles

#### Resumen
Permite a los estudiantes buscar y consultar las tutorías académicas que se encuentran disponibles según una fecha específica y, opcionalmente, filtrar por asignatura o tema de interés.

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|
| fecha | Date | Fecha que se desea consultar para buscar tutorías |
| asignatura | String | Asignatura de interés (opcional) |
| tema | String | Tema específico de interés (opcional) |

#### Reglas o condiciones

- La fecha es un parámetro obligatorio para la búsqueda.
- La asignatura y el tema son parámetros opcionales.
- El sistema debe buscar tutorías que coincidan con la fecha proporcionada.
- Si se proporciona asignatura o tema, debe filtrar adicionalmente por estos criterios.

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|
| listaTutorias | Array | Lista de tutorías encontradas con sus detalles |
| mensajeInformacion | String | Mensaje informativo si no se encuentran tutorías |

Para cada tutoría en la lista se muestra:
- identificadorTutoria: Integer
- tema: String
- profesorResponsable: String
- fecha: Date
- hora: Time
- cuposDisponibles: Integer

#### Resultado esperado
El sistema muestra al estudiante todas las tutorías disponibles que coinciden con los criterios de búsqueda, incluyendo el identificador, tema, profesor, fecha, hora y cupos disponibles. Si no se encuentran tutorías, se muestra un mensaje informativo indicando que no hay resultados.


### RF-03 - Inscripción a tutoría

#### Resumen
Permite a un estudiante solicitarse inscrito en una tutoría específica, verificando que cumpla con todas las condiciones necesarias para poder participar en ella.

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|
| codigoEstudiantil | String | Código identificador del estudiante |
| identificadorTutoria | Integer | Identificador único de la tutoría |

#### Reglas o condiciones

- El estudiante debe encontrarse activo en la Universidad.
- La tutoría debe existir en el sistema.
- La tutoría debe tener al menos un cupo disponible.
- El estudiante no debe encontrarse previamente inscrito en la tutoría.

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|
| mensajeConfirmacion | String | Mensaje que confirma la inscripción exitosa |
| mensajeError | String | Mensaje que indica el motivo si la inscripción no fue posible |

#### Resultado esperado
Cuando la inscripción es exitosa, el sistema registra la inscripción del estudiante en la tutoría, actualiza la cantidad de cupos disponibles restando uno, y muestra un mensaje de confirmación. Si alguna condición no se cumple, la inscripción no se realiza y el sistema informa el motivo específico.


### RF-04 - [Nombre del requerimiento]

#### Resumen

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|

#### Reglas o condiciones

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|

#### Resultado esperado


## 4. Gestión de Versiones

### Ramas utilizadas

### Proceso de integración

### Conflictos encontrados
