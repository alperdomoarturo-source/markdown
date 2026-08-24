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


### RF-04 - Cancelación de inscripción

#### Resumen
Permite a un estudiante cancelar su participación en una tutoría en la que se encuentra inscrito, liberando el cupo correspondiente siempre que la tutoría no haya comenzado.

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|
| codigoEstudiantil | String | Código identificador del estudiante |
| identificadorTutoria | Integer | Identificador único de la tutoría |

#### Reglas o condiciones

- Debe existir una inscripción previa del estudiante en la tutoría.
- La tutoría aún no debe haber comenzado (fecha y hora actual debe ser anterior a la fecha y hora de la tutoría).

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|
| mensajeConfirmacion | String | Mensaje que confirma la cancelación exitosa |
| mensajeError | String | Mensaje que indica el motivo si la cancelación no fue posible |

#### Resultado esperado
Cuando la cancelación es exitosa, el sistema elimina la inscripción del estudiante en la tutoría, libera nuevamente el cupo correspondiente incrementando la cantidad de cupos disponibles, e informa al estudiante que la operación fue exitosa. Si no es posible realizar la cancelación, se muestra un mensaje indicando el motivo específico.


## 4. Gestión de Versiones

### Ramas utilizadas

### Proceso de integración

### Conflictos encontrados
