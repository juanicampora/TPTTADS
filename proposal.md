# Propuesta TP DSW

## Grupo

### Integrantes

- 46959 - Cámpora, Juan Ignacio
- 46799 - Casesi, Valentino

### Repositorios

- [Frontend](https://github.com/juanicampora/TTADS-FRONTEND)
- [Backend](https://github.com/ValenCasesi/TTADSBACKEND)
## Tema

### Descripción

Aplicación web para mejorar la experiencia de los clientes en la noche de un Boliche.

El boliche carga sus DJ's, accesos y canciones.

El dj carga sus propias canciones que pueden coincidir con las del boliche.

Los clientes pueden votar canciones de la noche y opinar sobre el DJ.

Se puede obtener información del top de canciones por fechas.

### Modelo

![Modelo de Dominio](/Modelo%20Dominio.png)

## Alcance Funcional

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD DJs<br>2. CRUD Canciones|
|CRUD dependiente|1. CRUD Canciones por DJ {depende de} CRUD Canciones y CRUD DJs|
|Listado<br>+<br>detalle| 1. Listado del Top Canciones con opcion de fecha o historico + detalle cantidad votos obtenidos|
|CUU/Epic|1. Votar canciones|

Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD DJs<br>2. CRUD Canciones<br>3. CRUD Canciones por DJ {depende de} CRUD Canciones <br>4. CRUD Accesos DJ|
|CUU/Epic|1. Votar canciones<br>2. Opinar sobre el DJ|

### Alcance Adicional Voluntario

_Nota_: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

| Req      | Detalle           |
| :------- | :---------------- |
| Listados | 1. Opiniones del Dj |
| CUU/Epic | 1.                |
| Otros    | 1.                |
