# Infografía Interactiva: Top 5 Aprendizaje Activo STEM

Este proyecto es una infografía web interactiva y responsiva construida puramente con HTML5 y CSS3. Su objetivo principal es presentar información académica y educativa de manera dinámica, mejorando el *engagement* del usuario mediante microinteracciones y retroalimentación visual al interactuar con los elementos.

## 🚀 Características Principales

* **Diseño "Mobile First":** La estructura está optimizada para dispositivos móviles mediante una disposición en columna única, escalando fluidamente a un diseño de dos columnas en pantallas de tabletas y escritorio.
* **Cero JavaScript:** Todas las animaciones y lógicas de interacción visual están construidas exclusivamente con CSS moderno, garantizando un rendimiento óptimo y una carga ultra rápida.
* **Sistema de Temas por Clases:** Uso de variables CSS (`--item-color`, `--wave-svg`) que permiten cambiar el esquema de color de cada tarjeta simplemente aplicando clases específicas (`.theme-blue`, `.theme-orange`, `.theme-green`).
* **Microinteracciones Avanzadas:**
  * **Efecto de Rotación 3D (Iconos):** Al pasar el cursor, un semicírculo oculto rota sobre el eje Y (`transform: rotateY`) para envolver el emoji central, completando visualmente el ícono.
  * **Línea de Menú Ondulada:** Los títulos cuentan con un subrayado dinámico animado. Utiliza un SVG codificado en Base64 aplicado como fondo (`background-image`), el cual se desplaza horizontalmente mediante `@keyframes` para crear un efecto de onda continua al hacer *hover*.

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica (`<main>`, `<ol>`, `<li>`, `<footer>`).
* **CSS3:** * CSS Custom Properties (Variables)
  * Flexbox para alineación y distribución del espacio
  * Transiciones (`transition`) y Animaciones (`@keyframes`)
  * Transformaciones 2D/3D (`transform`, `transform-origin`)
  * SVG en Base64 para gráficos ligeros integrados en la hoja de estilos

## 📁 Estructura del Código CSS

El bloque `<style>` del documento está organizado modularmente para facilitar su escalabilidad o futuras modificaciones por parte de equipos de diseño o comunicación:

1. **Variables y Reinicio:** Definición de la paleta de colores corporativa y fuentes tipográficas del sistema para garantizar una legibilidad limpia.
2. **Estructura de la Lista:** Lógica Flexbox y *Media Queries* para la adaptabilidad responsiva.
3. **Efecto de Icono (Hover):** Configuración de los pseudoelementos `::before` y `::after` para lograr la rotación 3D y los cambios de opacidad.
4. **Efecto de Línea Ondulada:** Implementación del patrón de fondo dinámico sobre el texto del título.
5. **Asignación de Colores:** Clases utilitarias que inyectan el color hexadecimal y su respectivo SVG ondulado a cada tarjeta.

## 💡 Casos de Uso

Este componente web es ideal para entornos de comunicación digital, marketing educativo o plataformas de *e-learning*. Su diseño estructurado facilita la lectura (escaneabilidad) y retiene la atención del usuario en puntos clave sin abrumarlo con bloques de texto estáticos.

## ⚙️ Cómo visualizar el proyecto

Dado que es un archivo estático sin dependencias externas ni motor de plantillas, la ejecución es inmediata:

1. Clona o descarga el repositorio/archivo.
2. Abre el archivo `index.html` en cualquier navegador web moderno (Chrome, Firefox, Safari, Edge).

## 📄 Créditos y Fuentes

* **Fuente de Contenido:** *Creative Pragmatics for Active Learning in STEM Education* - DOI: /10.1007/978-3-031-78720-1_1
* **Diseño y Desarrollo UX/UI:** Erick Delgado Rojas
