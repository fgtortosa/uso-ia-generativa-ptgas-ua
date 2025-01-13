---
title: Usando chatgpt para transformar información en texto
author: Paco García Tortosa. Servicio de Informática
date: 2025-01-10
tags:
  - CharlaIA
marp: true
---

### Usando chatgpt para transformar información en texto

---

1. Registrarnos o loguearnos en chatgpt: [https://chatgpt.com]([https://chatgpt.com])
2. Descargar el documento de: [https://web.ua.es/es/estudios-geopolitica/paginas/seminarios/iii-seminario-2024.html](https://web.ua.es/es/estudios-geopolitica/paginas/seminarios/iii-seminario-2024.html)
3. Subir el documento en pdf

---

Acercamiento inicial al problema, estamos usando el modelo sin indicaciones

Prompt: *Transcribe el texto del documento adjunto*

---

Estamos usando el modelo con indicaciones, en este caso facilitando la **estructura del documento**, también podemos usar un ejemplo

Prompt: *El documento adjunto contiene en la primera pagina los datos generales del seminario: las personas que intervienen, quien lo organiza y las entidades colaboradoras. El nombre del seminario, titulo, fecha, lugar, información e inscripciones. En la segunda pagina el programa y finalmente el comite organizador. ¿Puedes transcribir la informacion en este orden teniendo en cuenta el contenido de las imagenes (que son los logos)?*

---

Queremos **recuperar solo una parte de la información**. Utilizamos las indicaciones para ello

Prompt: *Necesitamos la siguiente información del documento para realizar un resumen: tipo de evento, nombre, lugar donde se realizarán las charlas del evento, organización, coordinación y programa, incluyendo si es posible el nombre de la ponencia, la fecha y hora, y el nombre del ponente*

---

Deseamos crear una pagina web con el evento, pero no que nos escriba una pagina completa en html, sino solo el interior de ella, con párrafos, y con estilos básicos, como negrita, cursiva etc.

Prompt: *Tengo que preparar una pagina web con una charla, sobre la que tengo una imagen. ¿Podrías hablarme de la temática de la charla en función de los datos de la imagen?. Estructura los datos para que los pueda utilizar en una pagina web para notificar el evento, con su fecha y su temática en una pagina web. Produce solo el texto en html con párrafos, estilos básicos, como negrita, cursiva y si se da el caso con viñetas numéricas o no numéricas, pero no añadas estilos css*

----

5. Por favor, puedes hacer un resumen similar en texto plano
6. Por favor, incluye los siguientes apartados en el resumen: tipo del evento, nombre del evento, lugar don de realizarán las charlas, organización, coordinación y por último indica que ponencias van a tener lugar, la fecha y hora de cada ponencia, el ponente con su correspondiente cargo
7. Por favor, realiza un resumen de un párrafo del evento, indicando los temas de los que trata, a modo de resumen de la página
8. Ahora, por último, utilizando la información anterior que me has generado, estructura el interior de una página web (sin html, ni body, solo párrafos y estilos)
9. Pasalo a html para que lo pueda copiar

