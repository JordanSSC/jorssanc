# Mi sitio personal
Este es mi sitio personal. Aquí puedes encontrar información sobre mí, mis
proyectos y mis intereses.
## Contenido
* [Información personal](#información-personal)
* [Proyectos](#proyectos)
* [Intereses](#intereses)
* [Tecnologías](#tecnologías)
## Información personal
* Nombre: Jordan Sánchez
* Ocupación: Estudiante de Ingenieria en Computación en ESPOL
* Lugar de residencia: Guayaquil
## Proyectos

* ### 📘 Gestor de Tareas Académicas

[🔗 Ver repositorio en GitHub](https://github.com/JordanSSC/bases/tree/main)

Es una aplicación de escritorio desarrollada en **Python** con una interfaz gráfica intuitiva construida con **CustomTkinter**, que tiene como propósito ayudar a estudiantes a gestionar sus tareas académicas de forma organizada y visual.

#### 🧠 Descripción del Proyecto

Esta aplicación funciona como una **agenda digital para estudiantes**, permitiendo llevar un control completo sobre las tareas pendientes, en progreso y completadas. Está diseñada para mejorar la productividad y el seguimiento académico mediante una interfaz amigable y estadísticas visuales.

Las funcionalidades clave incluyen:

- ✅ **Agregar nuevas tareas** con detalles como nombre, descripción, estado y fecha de entrega.
- 📝 **Editar o eliminar tareas** existentes con facilidad.
- 📊 **Visualización de estadísticas** en el panel de inicio (Home), incluyendo el número total de tareas, tareas completadas, tareas en curso y tareas pendientes.
- 🗃️ **Persistencia de datos** usando **MySQL**, lo que permite almacenar toda la información en una base de datos estructurada y confiable.

#### 💻 Tecnologías Utilizadas

- **Python** – Lenguaje principal de desarrollo.
- **CustomTkinter** – Para la creación de una interfaz moderna y personalizable basada en Tkinter.
- **MySQL** – Sistema de gestión de bases de datos relacional utilizado para almacenar todas las tareas y su información asociada.
- **Arquitectura modular** – Separación de vistas, lógica y modelo para facilitar la mantenibilidad y escalabilidad del proyecto.

#### 🎯 Objetivo

El proyecto está orientado a brindar una herramienta práctica para estudiantes que desean mantenerse organizados y mejorar su gestión del tiempo. Combina simplicidad de uso con funcionalidades potentes para el manejo diario de tareas.

*El proyecto sigue en desarrollo*

* ### 🏛️ Sistema de Gestión de Ferias

[🔗 Ver repositorio en GitHub](https://github.com/JordanSSC/POO-P3-G11)

Este proyecto es una aplicación de escritorio desarrollada en **Java**, utilizando el paradigma de **Programación Orientada a Objetos (POO)** y una interfaz gráfica construida con **JavaFX** y **SceneBuilder**. Está diseñado para ayudar a los municipios en la **planificación, organización y gestión de ferias locales**.

#### 🧠 Descripción del Proyecto

El sistema permite a los municipios crear y administrar ferias que están organizadas en **secciones**, y dentro de cada sección, se pueden registrar múltiples **stands**. Estos stands pueden encontrarse en diferentes estados (disponibles u ocupados) y ser gestionados tanto por el municipio como por emprendedores.

Además, el sistema permite el registro y visualización de **auspiciantes**, ya sea a nivel general para toda la feria, o de forma específica para un stand individual.

Entre sus principales funcionalidades se incluyen:

- 🏗️ **Creación de ferias** con múltiples secciones y stands.
- 🧩 **Gestión de estados de los stands** (disponibles / ocupados).
- 🧑‍💼 **Registro de emprendedores**, quienes pueden reservar un stand en ferias activas.
- 🤝 **Manejo de auspiciantes**, tanto generales como específicos para stands individuales.
- 🎛️ **Interfaz visual amigable** creada con SceneBuilder y JavaFX, que facilita la interacción para usuarios administrativos y emprendedores.

#### 💻 Tecnologías Utilizadas

- **Java** – Lenguaje de programación principal.
- **JavaFX** – Para el desarrollo de interfaces gráficas ricas y modernas.
- **SceneBuilder** – Herramienta visual para diseñar las interfaces en JavaFX.
- **Paradigma POO** – Aplicación sólida de conceptos como clases, herencia, composición y encapsulamiento.

#### 🎯 Objetivo

Este proyecto busca digitalizar el proceso de organización de ferias municipales, facilitando tanto la labor de los organizadores como la experiencia de los emprendedores. Gracias a su diseño modular y enfoque orientado a objetos, es fácilmente extensible y adaptable a distintos escenarios de ferias o eventos.

* ### 🧩 Taller de Patrones de Diseño

[🔗 Ver repositorio en GitHub](https://github.com/JordanSSC/taller04)

Este proyecto es una implementación sencilla pero clara de algunos de los **patrones de diseño más utilizados** en el desarrollo de software, específicamente **Factory Method** y **Adapter**, aplicados con **Java**.

#### 🧠 Descripción del Proyecto

El propósito del proyecto es demostrar la aplicación práctica de patrones de diseño en un contexto realista. La lógica principal gira en torno a un **gestor de reportes (`ReportManager`)**, que es capaz de generar diferentes tipos de reportes a través de una interfaz común (`Report`). Esta interfaz es implementada por clases concretas como:

- 📄 `ExcelReport`
- 📃 `WordReport`
- 📑 `PDFReport`

Cada uno de estos reportes puede generarse dinámicamente utilizando el patrón **Factory Method**, lo cual permite una fácil extensión a nuevos formatos sin modificar el código existente.

Por otro lado, el proyecto también demuestra el uso del patrón **Adapter**, para adaptar diferentes métodos de notificación de reportes:

- ✉️ Notificación por **Email**
- 📱 Notificación por **Telegram**
- 💬 Notificación por **WhatsApp**

Cada canal de notificación tiene su propia lógica, pero gracias al patrón Adapter, todos pueden usarse de forma uniforme a través de una interfaz común.

#### 💻 Tecnologías Utilizadas

- **Java** – Lenguaje principal del proyecto.
- **Patrón Factory Method** – Para la creación flexible de objetos de tipo `Report`.
- **Patrón Adapter** – Para unificar distintas implementaciones de servicios de notificación.

#### 🎯 Objetivo

El objetivo principal de este proyecto es aplicar y entender cómo los patrones de diseño pueden mejorar la **escalabilidad**, **flexibilidad** y **mantenibilidad** del código. Aunque pequeño, el proyecto es un ejemplo conciso y efectivo de cómo usar principios de diseño orientado a objetos en el desarrollo de software limpio y extensible.

## Intereses
* Interesado en creación de videojuegos con Unity
* Aprendizaje en diversos lenguajes de programación
* Trabajo colaborativo
* Nuevas tecnologías e Inteligencia Artificial
  
## Tecnologías

En mis proyectos he trabajado con una variedad de tecnologías enfocadas tanto al desarrollo de aplicaciones de escritorio como a la organización de sistemas escalables. A continuación se detallan las herramientas y lenguajes utilizados:

---

### 🐍 **Python**
Lenguaje de programación de alto nivel utilizado principalmente para el desarrollo de aplicaciones de escritorio. Su sintaxis clara y concisa permite un desarrollo rápido y eficiente. En mis proyectos ha sido clave para manejar lógica de negocio, conexión con bases de datos y construcción de interfaces gráficas.

### 🖼️ **CustomTkinter**
Es una librería basada en `tkinter` que permite construir interfaces modernas en Python con un diseño más estilizado y personalizable (modo oscuro, widgets mejorados, etc.). Fue utilizada para construir la interfaz de usuario del gestor de tareas.

### 🐬 **MySQL**
Sistema de gestión de bases de datos relacional. Utilizado para persistir información estructurada (tareas, usuarios, estados) en el gestor de tareas. A través de consultas SQL se maneja el almacenamiento y recuperación de datos.

### ☕ **Java**
Lenguaje de programación orientado a objetos ampliamente utilizado en entornos empresariales y académicos. Todos mis proyectos en Java aplican conceptos sólidos de OOP como encapsulamiento, herencia, polimorfismo y composición.

### 🎨 **JavaFX**
Framework para el desarrollo de interfaces gráficas en Java. Permite crear GUIs interactivas y fáciles.

### 🧱 **SceneBuilder**
Herramienta visual para diseñar interfaces gráficas en JavaFX sin necesidad de escribir manualmente el código XML. Permite construir pantallas de forma intuitiva mediante drag-and-drop.

### 🌐 **HTML**
Lenguaje estándar para estructurar contenido web. Aunque no ha sido el centro de los proyectos actuales, tengo conocimientos para construir interfaces estáticas y estructurar contenido en páginas web.

### 🎨 **CSS**
Lenguaje de hojas de estilo utilizado para dar presentación y diseño a interfaces web. Permite definir estilos visuales, layouts responsivos, colores, tipografía y más.

---


