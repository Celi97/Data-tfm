
En este repositorio se encuentran los datos con los que se ha desarrollado la parte práctica del trabajo de fin de máster de Celina López García, tutorizado por Ana García Serrano (UNED).


# Dataset

Encontramos un primer archivo **corpus_inicial.xslx** que contiene las frases obtenidas del proceso de simplificación. 

1. Frase original
2. Frase propuesta por GPT
3. Frase validada por el usuario/a
4. Pregunta creada por un usuario/a

Las frases de los puntos 2. y 3. pueden ser la misma si el usuario/a no ha considerado necesario hacer ninguna modificación.
Adicionalmente se ha creado una pregunta para cada frase. En las carpetas podemos encontrar las preguntas generadas para cada una de las frases.

 - MISTRAL: En esta carpeta se encuentran las frases generadas por el modelo _mistralai/Mixtral-8x7B-Instruct-v0.1_
 - GPT3.5-turbo: En esta carpeta se encuentran las frases generadas por el modelo de Open AI _GPT3.5-turbo_
 - GPT-4o-mini: En esta carpeta se encuentran las frases generadas por el modelo de Open AI _GPT-4o-mini_

# Evaluación

Dentro de la carpeta asociada a cada modelo se puede encontrar otra con el nombre 'Score'. Dentro de esa carpeta se pueden encontrar los valores obtenidos para cada evaluador.

# Códigos

Los códigos se dividen en dos, los relacionados a la creación de las preguntas y las respuestas y los códigos usados para las métricas de evaluación.