# mongo-queries-4

1. Insertar los documentos de la colección media.json en una base de datos llamada «media» en una única
operación.
2. Actualizar el documento que hace referencia a la película «Matrix», de manera que se cambia su estructura a:
{“tipo”: “DVD”,
“Titulo”: “Matrix”,
“estreno”: 1999,
“genero”:”accion”
}
3. Considerar un nuevo documento para la colección media:
{“tipo”: “Libro”,
“Titulo”: “Constantinopla”,
“capitulos”:12,
“leidos”:3
}
Añadir el documento a la colección media y a continuación incrementar en 5 unidades el valor de la clave
«leídos».
EJERCICIO 4(CONT)
Actualización de Documentos
4. Actualizar el documento referido a la película «Matrix» cambiando el valor de la clave «género» a «ciencia
ficción».
5. Actualizar el documento referido al libro «Java para todos» de manera que se elimine la clave «editorial».
6. Actualizar el documento referido al libro «Java para todos» añadiendo el autor «María Sancho» al array de
autores.
7. Actualizar el documento referido a la película «Matrix» añadiendo al array «actores» los valores de
«Antonio Banderas» y «Brad Pitt» en una única operación.
8. Actualizar el documento referido a la película «Matrix» añadiendo al array «actores» los valores «Joe
Pantoliano», «Brad Pitt» y «Natalie Portman» en caso de que no se encuentren, y si se encuentran no se
hace nada.
9. Actualizar el documento referido a la película «Matrix» eliminando del array el primer y último actor.
10. Actualizar el documento referido a la película «Matrix» añadiendo al array actores los valores «Joe
Pantoliano» y «Antonio Banderas».
EJERCICIO 4(CONT)
Actualización de Documentos
11. Actualizar el documento referido a la película «Matrix» eliminado todas las apariciones en el array
«actores» de los valores «Joe Pantoliano» y «Antonio Banderas».
12. Actualizar el documento referido al disco «Recuerdos» y añadir una nueva canción al array «canciones»:
{“cancion”:5,
“titulo”: “El atardecer”,
“longitud”: “6:50”
}
13. Actualizar el documento referido al disco «Recuerdos» de manera que la canción «El atardecer» tenga
asignado el número 3 en vez de 5.
14. Actualizar el documento referido al disco «Recuerdos» de manera que en una sola operación se cambia el
nombre del artista a «Los piratillas» y se muestre el documento resultante.
15. Renombrar el nombre de la colección «media» a «multimedia».
