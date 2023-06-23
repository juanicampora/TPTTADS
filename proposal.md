# Propuesta TP DSW

## Grupo
### Integrantes
* 46959 - Cámpora, Juan Ignacio
* 46799 - Casesi, Valentino

### Repositorios
* [fullstack app](https://github.com/juanicampora/TPTTADS)

## Tema
### Descripción
Aplicación web para mejorar la experiencia de los clientes en la noche de un Boliche.

El boliche carga sus administradores, eventos, DJ's, canciones. 

Los clientes pueden votar canciones, opinar sobre el DJ y solicitar canciones previo al evento.

Se puede obtener información tanto del ranking de DJs como del ranking por noche o por mes de canciones.

### Modelo
![imagen del modelo]()

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD DJs<br>2. CRUD Canciones<br>3. CRUD Evento|
|CRUD dependiente|1. CRUD Canciones por DJ {depende de} CRUD Canciones<br>2. CRUD Opiniones sobre los DJs {depende de} CRUD DJs|
|Listado<br>+<br>detalle| 1. Listado del Top Canciones en Tiempo Real, filtrado por Evento, muestra nombre y posicion en el ranking <br> 2. Listado del Top Canciones filtrado por Mes, muestra nombre y posicion en el ranking|
|CUU/Epic|1. Votar canciones<br>2. Opinar sobre el DJ|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD DJs<br>2. CRUD Canciones<br>3. CRUD Evento<br>4. CRUD Canciones por DJ {depende de} CRUD Canciones<br>5. CRUD Opiniones sobre los DJs {depende de} CRUD DJs<br>6. CRUD Canciones Solicitadas<br>7. CRUD Usuarios<br>8. CRUD Tipos de Usuarios|
|CUU/Epic|1. Votar canciones<br>2. Opinar sobre el DJ<br>3. Solicitar Canción <br>4. Login|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Ranking de DJs|
|CUU/Epic|1. |
|Otros|1. |

