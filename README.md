# Curso de Análisis de Textos con técnicas de Aprendizaje Automático

¡Bienvenido a mi curso sobre análisis de textos con aprendizaje automático! Se trata de un curso basado en mi experiencia como profesor de esta asignatura, así como en varios proyectos de tratamiento del lenguaje natural en los que he participado. Incluye material teórico y práctico para aprender, de manera autoguiada, desde las técnicas clásicas de análisis de textos hasta las más actuales basadas en redes neuronales profundas (Deep Learning).

## Preliminares

Los conocimientos mínimos para poder sacar partido de este curso son:

* Experiencia de programación en **Python**, y uso de **Jupyter Notebooks**.
* Uso de **git**.
* Conocimientos básicos de **aprendizaje automático**.

Cada tema se constituye de una serie de diapositivas teóricas que te recomiendo leer en primer lugar para entender los conceptos esenciales. A continuación deberás ponerte manos a la obra y resolver un ejercicio práctico relacionado con los conceptos cubiertos. Puedes visualizar estos ejercicios en Github, pero para interactuar con ellos deberás **clonar este repositorio** y utilizar **Jupyter notebook** para trabajar con los cuadernos que hay en él. Se incluyen también las soluciones a los ejercicios, pero solo es aconsejable recurrir a ellas para compararlas contra tu propia solución. ¡Intenta resolver los ejercicios por tu cuenta!

Respecto a los paquetes Python necesarios, te recomiendo que hagas uso de una distribución Anaconda 3 e instales los entornos de Text Mining y Deep Learning de [este repositorio](https://github.com/albarji/teaching-environments). Cada ejercicio te indicará qué entorno concreto debes utilizar.

## Tema 1 - Introducción

Comenzamos con unas nociones básicas sobre el análisis del lenguaje escrito.

* [Teoría](An%C3%A1lisis%20de%20Textos%20-%201%20-%20Introducci%C3%B3n.pdf)

En este tema no hay ejercicios prácticos.

## Tema 2 - Análisis de caracteres

Aprenderemos cómo poder realizar aplicaciones basadas únicamente en el análisis de los caracteres del texto.

* [Teoría](An%C3%A1lisis%20de%20Textos%20-%202%20-%20An%C3%A1lisis%20de%20caracteres.pdf)
* [Ejercicio práctico: creando un detector de idiomas](labs/lab0_lang_detect/langdetect_student.ipynb)
* [Solución al ejercicio](labs/lab0_lang_detect/langdetect_solution.ipynb)

## Tema 3 - Análisis de tokens

Veremos cómo partir el texto en palabras (tokens) y hacer uso de esto para mejorar nuestros modelos.

* [Teoría](An%C3%A1lisis%20de%20Textos%20-%203%20-%20An%C3%A1lisis%20de%20tokens.pdf)
* [Ejercicio práctico: detector de spam basado en palabras](labs/lab1_spam_words/practicaSpamStudent.ipynb)
* [Solución al ejercicio](labs/lab1_spam_words/practicaSpamSolution.ipynb)

## Tema 4 - Análisis morfosintáctico clásico

Revisamos las técnicas del campon de la lingüística computacional para extraer información léxica y sintática del texto.

* [Teoría](An%C3%A1lisis%20de%20Textos%20-%204%20-%20An%C3%A1lisis%20morfosint%C3%A1ctico%20cl%C3%A1sico.pdf)
* [Ejercicio práctico: análisis morfosintáctico con spaCy, y detector de la opinión](labs/lab2_imdb_morpho/practicaPeliculasStudent.ipynb)
* [Solución al ejercicio](labs/lab2_imdb_morpho/practicaPeliculasSolution.ipynb)

## Tema 5 - Análisis semántico

Estudiaremos como extraer el significado de las palabras o de los documentos.

* [Teoría](An%C3%A1lisis%20de%20Textos%20-%205%20-%20An%C3%A1lisis%20sem%C3%A1ntico.pdf)
* [Ejercicio práctico: detección de temas con LDA y otros métodos](labs/lab3_lda/lda_student.ipynb)
* [Solución al ejercicio](labs/lab3_lda/lda_solution.ipynb)

## Tema 6 - Métodos estadísticos avanzados

Utilizaremos algunas de las últimas técnicas de Deep Learning para mejorar nuestros modelos de texto.

* [Teoría](An%C3%A1lisis%20de%20Textos%20-%206%20-%20M%C3%A9todos%20estad%C3%ADsticos%20avanzados.pdf)
* [Ejercicio práctico 1: álgebra semántico con word2vec](labs/lab4_word2vec_math/word2vec_math_student.ipynb)
* [Solución al ejercicio 1](labs/lab4_word2vec_math/word2vec_math_solution.ipynb)
* [Ejercicio práctico 2: detección de comentarios tóxicos con Deep Learning](labs/lab5_toxic/toxic_student.ipynb)
* [Solución al ejercicio 2](labs/lab5_toxic/toxic_solution.ipynb)

## Cierre

¡Espero que este curso te haya podido servir para aprender algo más sobre el análisis de textos! Si tienes comentarios o sugerencias de mejora puedes contectarme a través de [Twitter](https://twitter.com/albarjip).

Todo el material teórico de este curso está cubierto por una [licencia Creative Commons BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es), lo que significa que puedes distribuirlo libremente sujeto a que referencies al autor original, no modifiques el contenido, y no lo emplees con fines comerciales. El código de los ejercicios prácticos está sujeto a una licencia MIT, por lo que puedes usarlo libremente.
