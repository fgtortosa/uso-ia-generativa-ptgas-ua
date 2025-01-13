---
title: Uso de la inteligencia artificial generativa para el PTGAS de la Universidad de Alicante
author: Paco García Tortosa. Servicio de Informática
date: 2024-12-02
marp: true
tags:
  - CharlaIA
---

## Consideraciones iniciales
- La IA generativa puede ser una ayuda para las tareas del día a día del colectivo PTGAS de la Universidad de Alicante
- Es una herramienta de apoyo, necesita ser supervisada
- Como se usa en la nube hay que evitar el uso de datos personales
- Es buena en tareas lingüísticas, no en razonamiento ni matemáticas

---

## Conceptos
**Prompt**:  Texto con el que inicia la conversación. 

---

## Conceptos

**Prompt**

1. Hay que detallar el tipo de salida que se desee y toda aquella información que sea relevante (contexto). 
2. Si la salida que se desea es compleja comenzar con una aproximación al problema para a continuación ir añadiendo la complejidad. 
3. En algunos casos puede ser interesante utilizar ChatGpt con su chat de razonamiento por pasos

---

## Conceptos

**Contexto**

La información inicial y la recibida durante la conversación. Normalmente el contexto es temporal, la herramienta lo almacena durante algún tiempo y luego lo pierde

---

## Conceptos

**Multimodalidad**

El modelo permite el uso de texto, imágenes, audio, etc. No funciona igual de bien con todos los tipos de datos, normalmente con texto y con imágenes si se quiere obtener información de ellas (como OCR)

---

## Modelos que podemos usar
1. claude
2. chatgpt
3. gemini
4. bing (copilot)

---

### Claude.ai
- Modelo de Anthropic
- En es el mejor modelo para tareas de programación, incluyendo por supuesto las formulas de excel
- Hay que registrarse para usarlo, en [https://claude.ai](https://claude.ai)

---

### Chatgpt.com
- Modelo de OpenAI
- Es un buen modelo para tareas de razonamiento
- Hay que registrarse en [https://chatgpt.com](https://chatgpt.com)

---

### Google Gemini
- Genera texto e imágenes
- Se puede usar sin registrarse desde una cuenta de *gcloud*. Para acceder: [https://gemini.google.com/](https://gemini.google.com/)
- Posiblemente el menos potente de los tres

---

### Microsoft Bing
- Vamos a utilizar el generador de imagenes
- Necesitamos una cuenta mscloud o registrarnos (igual que Gemini). Para acceder: [https://www.bing.com/images/create](https://www.bing.com/images/create)

---
## Ejemplo práctico

Creación de una página web con la noticia de un evento que va a tener lugar en la Universidad

---

1. La información que nos proporcionan está en un cartel del propio evento
2. Vamos a utilizar distintos modelos, los mas conocidos, pero con un mismo prompt y vamos a afinar la salida
3. Todos los modelos nos van a obligar a registrarnos
4. Cada modelo puede dar una respuesta distinta
5. Cada vez que se le pregunta al modelo también puede dar una respuesta distinta (*esta inteligencia artificial es generativa*)

---
### Pregunta (prompt)

Tengo que preparar una pagina web con una charla, sobre la que tengo una imagen. ¿Podrías hablarme de la temática de la charla en función de los datos de la imagen?. 
Estructura los datos para que los pueda utilizar en una pagina web que usaré para notificar el evento, con el organizador, las fechas y su temática en una pagina web.

La imagen se encuentra en: https://dagrygf.ua.es/de/documentos/2024-seminario-ot-la-region-y-la-ciudad/la-region-y-la-ciudad-seminario-ot-2024.jpg

----

### Ejemplo práctico

Creación de la imagen que vamos a utilizar en la página web del evento

---

#### Pregunta (prompt)

Necesito una imagen para una página web. Esta imagen debe de ser de una ciudad mediterránea, con una avenida con palmeras, el mar al lado y la parte trasera una pequeña montaña. La imagen por favor en blanco y negro y la ciudad de los años 60 del siglo pasado

----

#### Pregunta (prompt)

Afino: Necesito una imagen para una página web. Esta imagen debe de ser de una ciudad mediterránea, con una avenida con palmeras, el mar al lado y la parte trasera una pequeña montaña. La imagen por favor en blanco y negro y la ciudad de los años 60 del siglo pasado. Por favor, pon la ciudad a la izquierda con los edificios monumentales, a la derecha la playa y al fondo a la izquierda, también junto a la playa la pequeña montaña con una fortificación de tipo castillo (mediterráneo)

---

![Ciudad mediterránea](/imagenes/imagen-ciudad.jpg "San Juan Mountains")

---

### Ejemplo práctico : 

Uso de Perplexity.ai para hacer búsquedas
[https://perplexity.ai](https://perplexity.ai)

#### Prompt:

Por favor, necesito información sobre Nacho Díez Torrijos, del Departamento de Urbanismo de la Universitat Politècnica de València

---

#### Resultado:

Ignacio Díez Torrijos, también conocido como Nacho Díez Torrijos, es un destacado profesional en el campo del urbanismo y la arquitectura del paisaje, vinculado a la Universitat Politècnica de València (UPV)

---

### Otros usos 

### Ejemplos Adicionales de Uso Administrativo

---

#### Gestión de Correspondencia y Comunicaciones

- Redacción de comunicados oficiales
- Generación de respuestas tipo para consultas frecuentes
- Traducción de documentos
- Corrección y mejora de textos administrativos

----

#### Procesamiento de Documentos

- Extracción de información de formularios
- Resumen de documentos extensos
- Clasificación y etiquetado de documentación
- Generación de índices y metadatos

---

#### Planificación y Organización

- Creación de calendarios de eventos
- Generación de informes de actividades
- Borradores de actas de reuniones
- Planificación de tareas y gestión de proyectos

---

#### Atención al Público

- Generación de guiones para atención de consultas
- Creación de FAQ personalizadas
- Apoyo en la redacción de respuestas a solicitudes
