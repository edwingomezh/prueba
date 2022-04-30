# prueba

1. Un punto final para proporcionar una búsqueda dentro de las pistas (al menos por nombre, pero es abierto a cualquier sugerencia)

Se crea un punto final para búsqueda por nombre mediante método GET, llamado getTracksName

Debe ser invocado de la siguiente manera, (al final agregar el nombre del artista a búscar
'''
http://localhost:8000/api/getTracksName/?name=NAMESEARCH
'''

- Y le resultado es en formato json.
---

---


2. Un punto final que permitiría obtener las 50 mejores pistas de popularidad.

Como no existe un variable para saber el ranking  de popularidad de las pistas, se desarrollo un endpoint que ordenara en orden ascendente lo artistas por su identificado y el resultado fuera el identificador y el nombre del artista. Se desarrollo el servicio getTopTracks

Debe ser invocado de la siguiente manera, 
'''
http://localhost:8000/api/getTopTracks/
'''

- Y le resultado es en formato json.
---

---

