# Interfaces Web Adaptables con HTML y CSS
 
Tarea 1 del curso SOFT-12 — Desarrollo Web Avanzada.
 
**Estudiante:** Alexander Gonzalez Castillo
**Sección:** SCV2    **Periodo:** III cuatrimestre 2026
**Docente:** Álvaro Cordero Peña
**Fecha de Entrega:** 20/09/2026
 
## Descripción
 
### Caso 1 — Centro de control de una expedición científica

Panel web para visualizar y organizar la información de una expedición científica en el Parque Nacional Corcovado. Permite consultar el estado de las misiones, equipos científicos, alertas y próximas actividades.

**Problema que resuelve:** Centraliza la información de la expedición para facilitar el seguimiento de las operaciones y permitir consultar rápidamente su estado.

### Caso 2 — Panel público de información de un festival

Sitio web informativo para consultar las actividades de un festival cultural, incluyendo eventos actuales y próximos, escenarios, cambios importantes y servicios disponibles.

**Problema que resuelve:** Facilita a los asistentes encontrar rápidamente qué actividades están ocurriendo, cuáles siguen después, dónde se realizan y si existen cambios en la programación.
 
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
 


- **Etiquetas semánticas:** Se utilizaron `header`, `nav`, `main`, `section`, `article`, `aside`, `time` y `footer` según la función de cada contenido.
- **Encabezados:** Se utilizó un `h1` para el título principal, `h2` para las secciones y `h3` para sus elementos internos.
- **Accesibilidad:** Se incluyó `lang="es"`, textos descriptivos, estados identificables mediante texto y colores, navegación mediante enlaces y suficiente contraste.
- **Modelo de caja:** Se utilizó `box-sizing: border-box` para incluir padding y bordes dentro del tamaño de los elementos.
- **Posicionamiento:** `sticky` mantiene el encabezado visible y `relative` + `absolute` permite colocar la etiqueta «En este momento» dentro de las actividades.
- **Cascada:** Los estilos iniciales corresponden a móvil y las `media queries` sobrescriben propiedades para reorganizar el contenido en pantallas mayores.
- **Flexbox:** Se utilizó en el encabezado, navegación, actividades actuales, próximas actividades y servicios para alinear y distribuir elementos.
- **CSS Grid:** Se utilizó en el contenedor principal, las actividades actuales, escenarios y servicios para organizar el contenido en filas y columnas.
- **Responsive:** En móvil se priorizan las actividades actuales y se utiliza una columna. En tablet se agregan dos columnas y en escritorio se distribuyen varias zonas simultáneamente.
- **Media queries:** Se utilizaron `38rem` y `64rem` para adaptar la interfaz según el espacio disponible y cambiar realmente su distribución.
- **Unidades relativas:** Se utilizaron principalmente `rem`, `%` y `fr` para mantener un diseño flexible.
- **Variables CSS:** Las variables de `:root` centralizan colores y espaciados para mantener consistencia y facilitar cambios.

 
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
| 11 | 2026-09-20 | db639a8 | Creacion del :root, estilo CSS general, encabezado y navegacion | Caso 2 | Encabezado, Nav y estilo general CSS |
| 12 | 2026-09-20 | 47b7fb7 | Estilos CSS de ahora, listas, cambios, escenarios, servicios, footer y media queries | Caso 2 | Ahora, Listas, cambios, escenarios, servicios footer y media queries CSS |




