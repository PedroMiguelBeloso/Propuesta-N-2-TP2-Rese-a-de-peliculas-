# Propuesta-N-2-TP2-Rese-a-de-peliculas-

plataforma para que usuarios dejen reseñas y puntuaciones a peliculas, podria contener un raking actualizado por cada opinion y puntuacion de las peliculas utilizando mysql y node.js

## Entidades/Modelos principales
Usuario (id, nombre, email, password)

Pelicula (id, titulo, categoría, descripcion)

Review (IdReviewidPelicula, usuarioId, itemId, estrellas/calificacion (1-5), texto, fecha)

Comentario (id, IdReview, usuarioId, texto)

## Endpoints
Get/Usuario /id (obtener ambos get, la lista de usuarios y el usuario x id) GET/Pelicula, GET /pelicula/id POST /Pelicula/id/reviews

##complejidad alta/moderada
Exportar reseñas de cada pelicula.
actualizador de calificacion/estrellas en tiempo real, tipo que si una peli tiene 4,5,4 te de un promedio de todos los puntajes
validacion del mail a la hora de registrarse,tanto a nivel sql como por ejemplo mandar un mail chequeandolo y confirmandolo

(Chequear si se puede usar alguna api)
