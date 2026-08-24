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
