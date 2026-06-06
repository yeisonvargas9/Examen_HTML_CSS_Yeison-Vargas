# 📊 Examen Práctico: Sección Nuestro Impacto - Patitas Felices

Este repositorio contiene el desarrollo del examen práctico para la página **Patitas Felices**. Consiste en una maqueta estática y responsiva de la sección **"Nuestro Impacto"** (`impacto.html`), diseñada exclusivamente con **HTML5** y **CSS3** nativo, sin usar JavaScript ni imágenes para los gráficos.

---

## 🎯 Requerimientos Cumplidos

* **Encabezado:** Título principal “Nuestro Impacto” y subtítulo explicativo de dos líneas.
* **Panel de Métricas (Grid):** 4 tarjetas grandes maquetadas con la etiqueta semántica `<article>` que muestran:
  * Animales rescatados (590)
  * Animales adoptados (1545)
  * Voluntarios activos (15)
  * Eventos organizados (35)
  * *Cada tarjeta incluye: número gigante, label descriptivo y una nota al pie (footnote).*
* **Gráfico Visual Simulado:** Barras de progreso horizontales hechas con CSS para comparar los valores. Las proporciones se calcularon en el CSS con la fórmula: `/* bar width: (valor / valor_maximo) * 100% */`.
* **Narrativa y CTA:** Un párrafo explicativo sobre el significado de las cifras y un botón centrado con el texto **"Contribuye"**.
* **Diseño Responsivo:** El panel de tarjetas se adapta automáticamente según la pantalla:
  * **Desktop:** 4 columnas.
  * **Tablet:** 2 columnas.
  * **Móvil:** 1 columna.

---

## 🛠️ Detalles Técnicos de Código

* **Estructura Semántica:** Uso correcto de `<main>`, `<section>` y `<article>` para una maquetación limpia.
* **Alineación con Flexbox:** El bloque de texto y el botón "Contribuye" están centrados horizontalmente usando `display: flex` y `flex-direction: column`.
* **Solución Sticky Footer:** Se aplicó `min-height: 100vh` en el `body` y `flex-grow: 1` en el `<main>` para obligar al footer a quedarse pegado al fondo de la pantalla, eliminando el espacio en blanco residual.
* **Rutas Relativas:** Uso de `../css/estilos.css` para enlazar correctamente la hoja de estilos desde la carpeta de páginas internas.

---

## ✒️ Autor

* **Estudiante:** Yeison Vargas M4
* **Proyecto:** Plataforma Patitas Felices
* **Tecnologías:** HTML5 | CSS3 (Flexbox, Grid Layout, Media Queries)
