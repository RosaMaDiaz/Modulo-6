# Guía de Laboratorio #3: Propiedades y Técnicas de Diseño en CSS

¡Bienvenido/a al repositorio de la práctica de laboratorio sobre **Propiedades y técnicas de diseño en CSS**! Este proyecto está diseñado para adquirir habilidades avanzadas en la estructuración de layouts modernos, flexibles y adaptables (responsive) mediante el uso de CSS3, Flexbox y CSS Grid.

## 📌 Información General

- **Materia:** Introducción al CSS
- **Módulo:** Módulo 6 (Resultado de Aprendizaje RA3)
- **Maestro:** Lic. Ramón Morillo Ullola
- **Tiempo Estimado:** 4 horas
- **Modalidad:** Virtual
- **Estudiante:** Rosa María Díaz de Montero

## 🎯 Resultado de Aprendizaje (RA3)

El objetivo principal de esta guía es aprender a **utilizar propiedades y técnicas de diseño en CSS para organizar contenidos en columnas, estructurar interfaces de usuario y desarrollar páginas web adaptables (responsive)** utilizando metodologías modernas.

### Desglose Didáctico

Al finalizar las actividades, serás capaz de:

- Aplicar propiedades de estilo para mejorar la presentación, tamaño, tipografía y alineación del texto.
- Integrar múltiples estilos arquitectónicos en un mismo elemento semántico.
- Diseñar páginas web con una presentación visual limpia, clara y organizada.

---

## 🗂️ Estructura del Contenido Académico

La guía se divide de forma modular en las siguientes unidades temáticas:

1.  **Unidad 1: Introducción al layout y organización en columnas**
    - Fundamentos del layout web y distribución lógica de elementos.
    - Métodos tradicionales y modernos de columnas con CSS3.
2.  **Unidad 2: Flexbox (Diseño flexible)**
    - Uso del eje unidimensional (`flex-direction`, `justify-content`, `align-items`).
    - Control de espaciados mediante la propiedad `gap`.
3.  **Unidad 3: CSS Grid (Estructuración avanzada)**
    - Estructuras bidimensionales avanzadas.
    - Uso de `grid-template-columns`, `grid-template-rows` y `grid-template-areas`.
4.  **Unidad 4: Diseño Responsive (Interfaces adaptables)**
    - Configuración esencial del Viewport en HTML.
    - Definición y aplicación estratégica de Media Queries (`@media`) y _Breakpoints_.
5.  **Unidad 5: Integración de interfaces**
    - Construcción de maquetas completas combinando de manera híbrida CSS Grid y Flexbox.
6.  **Unidad 6: Mejora visual y efectos (Estética de interfaces)**
    - Uso estético de `border-radius`, `box-shadow` e interactividad profesional mediante transiciones suaves (`:hover` y `transition`).

---

## 💻 Código de Ejemplo Base: Layout Moderno (HTML5 + CSS Grid)

Como punto de partida para las asignaciones, la guía provee un ejemplo práctico para construir un layout global usando CSS Grid.

### 1. Estructura Semántica (`index.html`)

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Layout Moderno - CSS Grid</title>
    <link rel="stylesheet" href="css/estilos.css" />
  </head>
  <body>
    <div class="contenedor">
      <header class="header">
        <h1>Mi Sitio Web</h1>
      </header>

      <nav class="menu">
        <a href="#">Inicio</a>
        <a href="#">Servicios</a>
        <a href="#">Contacto</a>
      </nav>

      <main class="contenido">
        <h2>Contenido Principal</h2>
        <p>
          Este es el contenido principal de la página estructurado con Grid.
        </p>
      </main>

      <aside class="sidebar">
        <h3>Sidebar</h3>
        <p>Información adicional o paneles secundarios.</p>
      </aside>

      <footer class="footer">
        <p>© 2026 - Mi Sitio Web Profesional</p>
      </footer>
    </div>
  </body>
</html>
```
