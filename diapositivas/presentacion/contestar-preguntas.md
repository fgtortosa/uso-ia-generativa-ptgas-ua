---
title: Uso de la inteligencia artificial generativa para el PTGAS de la Universidad de Alicante - Contestar preguntas
author: Paco García Tortosa. Servicio de Informática
date: 2024-12-02
marp: true
tags:
  - CharlaIA
---

## Consideraciones iniciales

- La IA generativa es buena generando contenidos, pero no tan buena contestando a preguntas
- Problemas:
    - Se inventa respuestas (alucina)
    - Siempre da la razón (miente si se lo pides)

---

## Solución

- Chats personalizados que utilizan únicamente la información que les hemos suministrado anteriormente
- Ejemplos: ChatGPT (de pago) y Notebook ML

---

### NotebookMl de Google

- Puede incorporar información desde distintos lugares: documentos propios, paginas web, videos, etc
- No es necesaria subscripción de pago para utilizar
- Como perfiles de usuario (editor, solo consultas)
- Se puede usar con una cuenta *gcloud*. Para acceder: [https://notebooklm.google.com/](https://notebooklm.google.com/)
- Permite crear cuadernos personalizados

---

#### Caracteristicas

- Resume documentos: 
  Extrae la información clave de cualquier texto, ya sea un artículo científico, un informe o un correo electrónico.
- Crea resúmenes personalizados: 
  Genera resúmenes adaptados a tus necesidades específicas, como un resumen ejecutivo o un resumen para estudiantes.
- Crear preguntas frecuentes: 
  Identifica las preguntas más comunes sobre un tema y proporciona respuestas concisas.

---

#### Caracteristicas

- Crea cronologías:
  Desarrolla materiales de estudio claros y concisos a partir de información compleja.
- Crea resumenes en audio:
  Permite a los alumnos informarse de temas administrativos sin tener que leer

---

#### Beneficios

¿Cómo puede beneficiar a tu trabajo administrativo?

- Ahorra tiempo: 
  Automatiza tareas repetitivas como la creación de informes y la búsqueda de información.
- Mejora la eficiencia: 
  Organiza y analiza grandes cantidades de información de manera rápida y sencilla.
- Facilita la colaboración: 
  Comparte tus notebooks con otros miembros del equipo y trabaja en conjunto. 
  Diferentes roles (administrador, lector)

---

#### Casos de uso para el PTGAS

- Creación de guías: 
  Desarrolla guías concisas y fáciles de entender para estudiantes sobre trámites administrativos.
- Gestión de documentación: 
  Organiza y clasifica la documentación de manera eficiente, facilitando su búsqueda.
- Atención al estudiante: 
  Responde a las preguntas de los estudiantes de forma rápida y precisa, utilizando las preguntas frecuentes generadas por NotebookML.

---

#### Ejemplo

- Creación de un notebook personalizado sobre la convocatoria Erasmus para su uso por parte de los estudiantes
- Permitira la consulta interactiva tanto de las gestiones necesarias para formalizar la solicitud como para conocer las plazas disponibles, los requisitos a cumplir por los solicitantes
- Crearemos cronologias con los hitos mas importantes 
- Crearemos un resumen de audio con una conversación entre dos personas para su distribución entre los alumnos mas perezosos 
- Permite crear resumenes en cualquier idioma y que los alumnos que no conocen bien el idioma puedan hacer consultas 

---

#### Creación de un notebook de la convocatoria Erasmus 25-26

- Materiales:
  https://sri.ua.es/es/movilidad/erasmus-ka131/2025-26/primer-plazo-de-solicitud.html

- Añadiremos como fuente:
  Bases: https://www.boua.ua.es/es/acuerdo/54461
  Listado de plazas: https://www.boua.ua.es/Acuerdos/DescargarAnexoxId?idanexo=1050865&idacuerdo=54623&idioma=es
  Baremo: https://www.boua.ua.es/Acuerdos/DescargarAnexoxId?idanexo=1042431&idacuerdo=54461&idioma=es


---

- Preguntas:
  Puedes convertir el calendario en ingles?
  Plazas de GRAU EN ENGINYERIA MULTIMÈDIA en Alemania?
  Y las plazas de GRAU EN ENGINYERIA MULTIMÈDIA en disponibles para los estudiantes que dispongan de un nivel B2 Alemán? 
  En Alemania solo no, en cualquier pais
  Si dispongo del titulo obligatorio de idioma para la plaza que solicito pero tambien de un nivel superior se me tiene en cuenta en el baremo?
  Pero se tiene en cuenta todos los idiomas o solo uno ?
  Puedo renunciar a la plaza que me asignan?
 