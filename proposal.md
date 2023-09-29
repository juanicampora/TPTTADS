# Propuesta TP DSW

## Grupo

### Integrantes

- 46959 - Cámpora, Juan Ignacio
- 46799 - Casesi, Valentino

### Repositorios

- [fullstack app](https://github.com/juanicampora/TPTTADS)

## Tema

### Descripción

Aplicación web para mejorar la experiencia de los clientes en la noche de un Boliche.

El boliche carga sus administradores, eventos, DJ's, canciones.

Los clientes pueden votar canciones, opinar sobre el DJ y solicitar canciones previo al evento.

Se puede obtener información tanto del ranking de DJs como del ranking por noche o por mes de canciones.

### Modelo

![Modelo de Dominio](/Modelo%20de%20Dominio.png)

## Alcance Funcional

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD DJs<br>2. CRUD Canciones|
|CRUD dependiente|1. CRUD Canciones por DJ {depende de} CRUD Canciones y CRUD DJs|
|Listado<br>+<br>detalle| 1. Listado del Top Canciones con opcion entre fechas o historico + detalle cantidad votos obtenidos|
|CUU/Epic|1. Votar canciones|

Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD DJs<br>2. CRUD Canciones<br>3. CRUD Canciones por DJ {depende de} CRUD Canciones <br>4. CRUD Usuarios<br>5. CRUD Tipos de Usuarios|
|CUU/Epic|1. Votar canciones<br>2. Opinar sobre el DJ|

### Alcance Adicional Voluntario

_Nota_: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

| Req      | Detalle           |
| :------- | :---------------- |
| Listados | 1. Ranking de DJs |
| CUU/Epic | 1.                |
| Otros    | 1.                |
