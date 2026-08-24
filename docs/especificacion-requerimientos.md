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


### RF-02 - [Nombre del requerimiento]

#### Resumen

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|

#### Reglas o condiciones

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|

#### Resultado esperado


### RF-03 - [Nombre del requerimiento]

#### Resumen

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|

#### Reglas o condiciones

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|

#### Resultado esperado


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
