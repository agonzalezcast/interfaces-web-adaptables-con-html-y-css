# Interfaces Web Adaptables con HTML y CSS
 
Tarea 1 del curso SOFT-12 — Desarrollo Web Avanzada.
 
**Estudiante:** Alexander Gonzalez Castillo
**Sección:** SCV2    **Periodo:** III cuatrimestre 2026
**Docente:** Álvaro Cordero Peña
 
## Descripción
 
Aplicación web que muestra como organizar una pagina web adaptable
utilizando solamente html y css mediante flexbox y CSS grid.
 
## Estructura del repositorio
 
- `caso1/` — prototipo del caso 1 con HTML y CSS
  - `css/`     — hoja de estilos compilada
  - `log/`     — 
- `caso2/` — prototipo del caso 2 con HTML y CSS
  - `css/`     — hoja de estilos compilada
  - `log/`     — 

## Cómo ejecutar
 
Abrir `caso1/index.html` y `caso2/index.html` en el navegador. No requiere instalación.
 
## Decisiones de diseño
 
### Decisiones de diseño

* **Etiquetas semánticas:** Se utilizaron `header`, `nav`, `main`, `section`, `article` y `time` para organizar el contenido según su función.
* **Encabezados:** Se utilizó un `h1` para el título principal, `h2` para las secciones y `h3` para sus elementos internos.
* **Accesibilidad:** Se incluyó `lang="es"`, textos descriptivos, `aria-hidden` para símbolos decorativos y estados identificables mediante texto y símbolos, no solo colores.
* **Modelo de caja:** Se utilizó `box-sizing: border-box` para incluir padding y bordes dentro del tamaño de los elementos.
* **Posicionamiento:** `sticky` mantiene el encabezado visible y `relative` + `absolute` permite colocar las etiquetas de prioridad dentro de las tarjetas.
* **Cascada:** Los estilos base son para móvil y las `media queries` sobrescriben propiedades cuando aumenta el ancho de pantalla.
* **Flexbox:** Se utilizó en el encabezado, navegación, indicadores, alertas y agenda para alinear y distribuir elementos en una dimensión.
* **CSS Grid:** Se utilizó en el panel principal y las cuadrículas de misiones, equipos e indicadores para organizar filas y columnas.
* **Responsive:** En móvil se utiliza una columna, en tableta dos y en escritorio se distribuyen las secciones en varias zonas.
* **Media queries:** `48rem`, `64rem` y `80rem` permiten adaptar progresivamente el diseño según el espacio disponible.
* **Unidades relativas:** Se utilizaron principalmente `rem`, `%` y `fr` para crear un diseño flexible.
* **Variables CSS:** Las variables de `:root` centralizan colores y espaciados para mantener consistencia y facilitar cambios.

 
## Resumen de commits
 
| # | Fecha      | Hash    |                         Mensaje                       | Zona   | Cambio        |
|---|------------|---------|-------------------------------------------------------|--------|---------------|
| 1 | 2026-09-18 | 8da13ac | Crear estructura de la tarea y documentacion inicial | Global | Carpetas |
| 2 | 2026-09-19 | 16324d6 | Estructura HTML del header y la navegacion del caso 1 | Caso 1 | Header y Navegacion HTML |
| 3 | 2026-09-19 | ae26f00 | Estructura HTML de las tarjetas de misiones | Caso 1 | Tarjetas de misiones |
| 4 | 2026-09-20 | 3444994 | Estructura HTML del Resumen de Operaciones y ajuste de Misiones y header | Caso 1 | Resumen de Operaciones |
| 5 | 2026-09-20 | b11dbe7 | Correccion del ultimo commit (no habia guardado los cambios) | Caso 1 | Resumen de Operaciones |
| 6 | 2026-09-20 | 1a16a7a | Estructura HTML de Equipos, Alertas y Agenda | Caso 1 | Equipos, Alertas y Agenda HTML |
| 7 | 2026-09-20 | 64c87f2 | Estilo CSS general y especifico de header, nav y resumen | Caso 1 | Header, Nav y Resumen CSS |
| 8 | 2026-09-20 | 5b3b3d3 | Estilo CSS de Misiones, Equipos, Alertas, Agenda y Media queries para los diferentes tamanos de pantalla | Caso 1 | Misiones, Equipos, Alertas, Agenda y Media Queries CSS|
| 9 | 2026-09-20 | 974eb57 | Estructura HTML del caso 2: header, nav, ahora y actividades proximas | Caso 2 | Header, nav, ahora y proximas HTML |
| 10 | 2026-09-20 | 935d081 | Estructura HTML de cambios, escenarios, servicios y el footer | Caso 2 | Cambios, Escenarios, servicios y footer HTML |



