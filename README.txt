# RETO TAPPX INDIVIDUAL - SERSANCH (SERGIO SANCHEZ ZAHINOS)
## Pasos seguidos para la clasificación de mensajes:
1. Lectura de CSV
2. Transformación de CSV a dataframe (DF, utilizando pandas)
3. Extracción en un nuevo DF con los mensajes de spam ya clasificados.
4. Creamos un string nuevo cuyo contenido sea la concatenación de cada mensaje
de spam, eliminando los dígitos.
5. Tokenizamos las palabras que nos interesan (quitando stop words) utilizando
la librería spacy
6. Creamos una lista de palabras comunes en los mensajes de spam
7. Creamos una función para clasificar un texto en spam o safe. Si un texto
contiene al menos un 25% de palabras comunes en mensajes spam, se clasificará como
spam. Si no, se clasificará como safe.
8. Creamos la tabla final con los mensajes filtrados utilizando la función descrita
en el anterior punto.
9. Convertimos esta tabla a CSV.