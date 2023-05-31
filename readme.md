# Web scraping in the poemas from Cesar Vallejo

 - Uso de python
 - Uso de librerias como: re, regex, spacy, nltk, string, requests

1. Visite la página https://www.literatura.us/vallejo/completa.html que contiene la obra
poética completa de César Vallejo.
2. Recupere la información de la página web (web scraping).
3. Elimine de los textos todo el contenido que no pertenezca a la obra (ruido como links,
información sobre la página, índices, caracteres de adorno, líneas en blanco, imágenes,
etc.) El resultado debe ser un texto limpio (textoRAW).
4. Crear los módulos necesarios para:
a. Recuperar un poema por su título.
b. Segmentar el texto en poemas.
c. Segmentar el texto en párrafos.
d. Segmentar el texto en oraciones.
e. Tokenizar el texto en palabras.
Realice las pruebas pertinentes de cada módulo
5. Crear los siguientes módulos independientes para normalizar un texto:
a. Quitar signos de puntuación
b. Convertir a minúsculas
c. Quitar stop-words
d. Quitar palabras con extensión mínima (valor por defecto del parámetro: 2)
e. Lematizar
f. Eliminar duplicados
Probar diferentes secuencias de los módulos, por ejemplo:
Secuencia 1:
a. Quitar signos de puntuación
b. Convertir a minúsculas
c. Quitar stop-words
d. Quitar palabras con extensión mínima
e. Lematizar
f. Eliminar duplicados
Secuencia 2:
a. Quitar signos de puntuación
b. Convertir a minúsculas
c. Quitar palabras con extensión mínima
d. Quitar stop-words
e. Lematizar
f. Eliminar duplicados
Secuencia 3:
a. Lematizar
b. Quitar signos de puntuación
c. Convertir a minúsculas
d. Quitar stop-words
e. Quitar palabras con extensión mínima
f. Eliminar duplicados
Definir dos secuencias adicionales.
Realizar un cuadro comparativo de las 5 secuencias (número de tokens) y analizar las
diferencias de los resultados alcanzados ¿Qué conclusiones se pueden extraer del
experimento?
6. Convertir los textos planos (textoRAW) a un corpus propiamente dicho, mediante el uso de
librerías como PlaintextCorpusReader. Comparar los resultados obtenidos con los implementados en los puntos 4 y 5 (realizar las pruebas necesarias para la comparación,
explicando adecuadamente la secuencia).
7. Normalizar textoRAW con la secuencia que permita obtener el vocabulario más pequeño
(de acuerdo con los resultados del punto 5) y luego escribir módulos para poder generar:
a. Vocabulario etiquetado (PoS).
b. Lista de adjetivos, verbos, sustantivos y adverbios más comunes (mostrar los 5
resultados de cada categoría gramatical que se repitan con más frecuencia).
c. Lista de nombres de entidades (NER).
Realice la prueba con el poema “Los heraldos negros”.
8. Escriba los módulos necesarios para listar los poemas del texto considerando para cada uno
de ellos: número de párrafos, oraciones y palabras. Muestre el resultado en una tabla.
9. Implemente algún módulo que considere interesante, ponga un ejemplo de su
funcionalidad y explique el resultado.