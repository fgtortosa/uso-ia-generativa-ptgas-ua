---
title: Uso de la inteligencia artificial generativa para el PTGAS de la Universidad de Alicante - Generar contenido
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
3. mistral
4. gemini
5. bing (copilot)

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

### Mistral.ai
- Modelo de Mistral (único modelo europeo)
- Funciona bastante bien en multimodalidad. Buena capacidad para realizar traducciones entre idiomas europeos
- Hay que registrarse en [https://mistral.ai](https://chatgpt.com)

---

### Google Gemini
- Genera texto e imágenes
- Se puede usar sin registrarse desde una cuenta de *gcloud*. Para acceder: [https://gemini.google.com/](https://gemini.google.com/)
- Posiblemente el menos potente de los cuatro

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

----

1. Registrarnos o loguearnos en chatgpt: [https://chatgpt.com]([https://chatgpt.com])
2. Descargar el documento de: [https://web.ua.es/es/estudios-geopolitica/documentos/programa-iii-geopolitica-2024.pdf](https://web.ua.es/es/estudios-geopolitica/documentos/programa-iii-geopolitica-2024.pdf)
3. Subir el documento en pdf a la herramienta (utilizando el icono del clip)

---

Acercamiento inicial al problema, estamos usando el modelo sin indicaciones

Prompt: *Transcribe el contenido del documento*

---

Queremos **recuperar solo una parte de la información**. Utilizamos las indicaciones para ello

Prompt: *Necesitamos la siguiente información del documento para realizar un resumen: tipo de evento, nombre, lugar donde se realizarán las charlas del evento, organización, coordinación y programa, incluyendo si es posible el nombre de la ponencia, la fecha y hora, y el nombre del ponente*

---

Queremos **realizar un resumen del evento** que incorporaremos en la propia página web

Prompt: *Por favor, realiza un resumen de un párrafo del evento, indicando los temas de los que trata, a modo de resumen de la página*

---

Vamos a **convertir toda la información anterior en html** para poder insertarla en nuestra página de vuala

Prompt: *Ahora, utilizando la información anterior que me has generado crea un documento html  (incluye la información estructurada del evento y el resumen del mismo que has elaborado anteriormente). Deseamos crear una pagina web con el evento, pero no que nos escriba una pagina completa en html, sino solo el interior de ella, con párrafos, y con estilos básicos, como negrita, cursiva etc.*

---

Vamos a utilizar la **herramienta de búsqueda** de ChatGPT para buscar información de los ponentes

Prompt: *Por favor, busca la información de los ponentes para añadir a la pagina web*

----

Revisamos la información y le pedimos que la transforme a html para incorporarla en la página web

Prompt: *Convierte esta información en html e incorporala en el contenido anterior de la pagina html en un apartado final llamado ponentes*

-----

Ponemos intentar **obtener alguna imagen de los ponentes**, vamos a buscarla

Prompt: *Existe alguna imagen pública de los ponentes para incorporarla a la página web?*

----

Esta operativa es idéntica tanto para chatgpt, como para mistral y gemini, que poseen acceso a internet

---

## Ejemplo práctico 

Creación de una imagen a partir de indicaciones

---

Microsoft Bing: https://www.bing.com/images/create 

1. Registrarnos o loguearnos en Microsoft Bing: [https://www.bing.com/images/create]([https://www.bing.com/images/create])
2. Necesitamos un usuario de microsoft

---

#### Pregunta (prompt)

Necesito una imagen para una página web. Esta imagen debe de ser de una ciudad mediterránea, con una avenida con palmeras, el mar al lado y la parte trasera una pequeña montaña. La imagen por favor en blanco y negro y la ciudad de los años 60 del siglo pasado

----

#### Pregunta (prompt)

Afino: Necesito una imagen que debe corresponder a una ciudad mediterránea, con una avenida con palmeras, el mar al lado y la parte trasera una pequeña montaña. La imagen por favor en blanco y negro y la ciudad de los años 60 del siglo pasado. La ciudad a la izquierda con los edificios monumentales, a la derecha la playa y al fondo a la izquierda, también junto a la playa, la pequeña montaña con una fortificación de tipo castillo (mediterráneo). La imagen en formato fotográfico, del tipo polaroit, con los bordes un poco blanquecinos por el paso del tipo, de tipo postal. En formato alargado para usar en una web

---

![Ciudad mediterránea](imagen-bing.jpg)

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

