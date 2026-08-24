# Especificación de Requerimientos

## 1. Descripción del sistema

## 2. Integrantes

- Nombre:
- Nombre:
- Nombre:
- Nombre:
- Nombre:

## 3. Requerimientos Funcionales

### RF-01 - [Nombre del requerimiento]

#### Resumen

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|

#### Reglas o condiciones

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|

#### Resultado esperado


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
