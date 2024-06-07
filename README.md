En el Sprint 1 trabajaremos lo basico de python con diferentes tipos de datos, incluidos los básicos como int, float y bool, además de tipos más complejos como strings (cadenas) y lists (listas).

- Convertir un tipo de datos a otro y realizar operaciones aritméticas con valores numéricos.
- Implementación del bloque try-except para evitar bloqueos.
- El formateo de cadenas se vuelve con el método format() o con f-strings. Además de cambiar las mayúsculas y minúsculas de cualquier string utilizando los métodos upper() o lower().
- Si hay espacios innecesarios, el método strip() puede eliminarlos y tambien reemplazar una parte de una cadena utilizando el método replace().
  
Las listas son una excelente forma de almacenar una colección de valores dentro de una sola estructura de datos. Los elementos de una lista se pueden segmentar pasando los índices deseados a los corchetes.
Los bucles pueden ahorrarnos mucho tiempo a la hora de iterar sobre elementos en una lista mediante el bucle for. 
Por otra parte, el bucle while es útil cuando queremos continuar la iteración hasta que se cumpla una condición particular por lo que usaremos de declaraciones condicionales para crear ramas en el código.
Con eso en mente.



En el contexto del Sprint 2 se probara una hipótesis relacionada con las preferencias musicales de dos ciudades. Esto se hará mediante el análisis de datos reales de transmisión de música online para probar la hipótesis a continuación y comparar el comportamiento de los usuarios y las usuarias de estas dos ciudades.

Esto implicará analizar los datos reales de transmisión de música online para comparar el comportamiento de los usuarios y las usuarias en Springfield y Shelbyville. El proyecto se divide en tres etapas, cada una con objetivos específicos.

En la etapa 1 se proporcionara una descripción general de los datos y anotarás tus observaciones. 
En la etapa 2, se preprocesara los datos al limpiarlos. 
En la etapa 3, se pondra a prueba la hipótesis si se rechaza o no, siguiendo los pasos de programación necesarios para probar cada declaración y comentando tus resultados en los bloques apropiados.

La actividad de los usuarios y las usuarias difiere según el día de la semana y dependiendo de la ciudad.

Los datos se almacenan en el archivo /datasets/music_project_en.csv

Descripción de las columnas:

'userID': identifica de forma exclusiva a cada usuario o usuaria;
'Track': título de la canción;
'artist': nombre del artista;
'genre': género musical;
'City': ciudad del usuario o la usuaria;
'time': hora del día en la que se reprodujo la pista (HH:MM:SS);
'Day': día de la semana.
