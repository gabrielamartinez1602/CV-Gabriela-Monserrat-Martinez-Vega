---
version: alpha
name: Gabriela Martínez Vega — Editorial Portfolio
description: Sistema de diseño editorial para el portafolio de Gabriela Martínez Vega. Estética clásica, editorial y elegante con gesto contemporáneo, rebelde y artístico.
colors:
  primary: "#83232D"
  secondary: "#282867"
  neutral: "#000000"
  surface: "#FFFFFF"
  on-surface: "#000000"
  on-primary: "#FFFFFF"
  on-secondary: "#FFFFFF"
  on-neutral: "#FFFFFF"
typography:
  headline-display:
    fontFamily: "CoFo Raffine"
    fontSize: 88px
    fontWeight: 400
    lineHeight: 0.95
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: "CoFo Raffine"
    fontSize: 48px
    fontWeight: 400
    lineHeight: 1
    letterSpacing: -0.01em
  headline-md:
    fontFamily: "CoFo Raffine"
    fontSize: 36px
    fontWeight: 400
    lineHeight: 1.1
  headline-sm:
    fontFamily: "CoFo Raffine"
    fontSize: 24px
    fontWeight: 400
    lineHeight: 1.2
  body-lg:
    fontFamily: "Serenity"
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.6
  body-md:
    fontFamily: "Serenity"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: "Serenity"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
  caption:
    fontFamily: "Serenity"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.4
  label-lg:
    fontFamily: "Serenity"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.2
  label-md:
    fontFamily: "Serenity"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.2
rounded:
  none: 0px
  sm: 2px
  md: 4px
spacing:
  base: 8px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 48px
  2xl: 64px
  3xl: 96px
  4xl: 128px
  gutter-desktop: 24px
  gutter-mobile: 16px
  margin-desktop: 48px
  margin-desktop-wide: 72px
  margin-tablet: 32px
  margin-mobile: 16px
  max-width: 1440px
  touch-target: 44px
  grid-columns-desktop: 12
  grid-columns-tablet: 8
  grid-columns-mobile: 4
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.md}"
    padding: 16px
    typography: "{typography.label-lg}"
  button-primary-hover:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    rounded: "{rounded.md}"
    padding: 16px
    typography: "{typography.label-lg}"
  button-secondary:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.on-secondary}"
    rounded: "{rounded.md}"
    padding: 16px
    typography: "{typography.label-lg}"
  button-secondary-hover:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.secondary}"
    rounded: "{rounded.md}"
    padding: 16px
    typography: "{typography.label-lg}"
  button-ghost:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    rounded: "{rounded.none}"
    padding: 8px
    typography: "{typography.label-lg}"
  card-project:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.none}"
    padding: "{spacing.md}"
    typography: "{typography.body-md}"
  band-neutral:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-neutral}"
    rounded: "{rounded.none}"
    padding: "{spacing.2xl}"
    typography: "{typography.body-md}"
  nav-link:
    textColor: "{colors.secondary}"
    typography: "{typography.label-lg}"
    padding: 8px
  nav-link-active:
    textColor: "{colors.primary}"
    typography: "{typography.label-lg}"
    padding: 8px
  text-link:
    textColor: "{colors.secondary}"
    typography: "{typography.body-md}"
  text-link-hover:
    textColor: "{colors.primary}"
    typography: "{typography.body-md}"
  icon:
    textColor: "{colors.secondary}"
    size: 20px
  icon-hover:
    textColor: "{colors.primary}"
    size: 20px
  project-fiche:
    textColor: "{colors.secondary}"
    typography: "{typography.caption}"
---

> **REVISAR:** Los valores marcados con **REVISAR** fueron completados con supuestos razonables porque no están especificados en el documento fuente. Confírmalos o ajústalos.

## Overview

La marca personal combina una estética clásica, editorial y elegante con una actitud rebelde, artística y contemporánea. Comunica a una diseñadora estratégica y creativa capaz de construir identidades con concepto, estructura y sensibilidad visual, dirigida a marcas, empresas, organizaciones y emprendimientos jóvenes que necesitan comunicación con personalidad sin perder claridad ni profesionalismo.

- **Atributos de marca:** creativa, estratégica, artística, cercana, confiable, estructurada y expresiva.
- **Sensación visual:** editorial, sofisticada, contrastante, narrativa y ligeramente experimental.
- **Principio rector:** lo clásico funciona como base; la composición, la escala y los detalles aportan el gesto contemporáneo.

## Colors

La paleta se construye sobre dos tonos protagonistas ligeramente opacos acompañados de negro y blanco. {colors.primary} (Winery Red) aporta fuerza, autoría y carácter editorial; {colors.secondary} (Sodalite Blue) introduce confianza, contraste y una sensación intelectual. {colors.neutral} y {colors.surface} equilibran el sistema y permiten que la tipografía y las imágenes sean protagonistas.

| Token | Valor | Rol |
| --- | --- | --- |
| {colors.primary} | `#83232D` Winery Red | Color principal: monograma, títulos, fondos de impacto, números editoriales y acentos. |
| {colors.secondary} | `#282867` Sodalite Blue | Color secundario: títulos alternos, información, enlaces, líneas y bloques de contraste. |
| {colors.neutral} | `#000000` Black | Fondos dramáticos, texto y recursos gráficos de alto contraste. |
| {colors.surface} | `#FFFFFF` White | Fondo principal, respiración visual y texto invertido. |

Reglas de uso:

- {colors.primary} y {colors.secondary} son acentos protagonistas que pueden alternar protagonismo entre secciones; blanco y negro dan descanso y contraste.
- Texto sobre {colors.primary} o {colors.secondary} siempre en {colors.on-primary} / {colors.on-secondary}.
- Texto sobre {colors.surface} siempre en {colors.on-surface}.
- No introducir naranjas, verdes u otros colores de interfaz como acentos permanentes fuera de la paleta.

## Typography

Se usan dos familias con roles claros:

- **CoFo Raffine** es la tipografía de identidad: logotipo, nombre, portadas, títulos principales y frases de gran escala.
- **Serenity** es la tipografía secundaria: cuerpo de texto, navegación, fichas de proyecto, datos, botones y pies de imagen.

La jerarquía se construye principalmente mediante contraste de escala, peso y espacio, no mediante demasiadas fuentes. Escala sugerida:

- Títulos hero: 48–88 px → `headline-lg` y `headline-display`. Pueden ocupar varias líneas o convivir con imagen y collage.
- Subtítulos: 24–36 px → `headline-sm` y `headline-md`.
- Cuerpo: 16–20 px → `body-md` y `body-lg`.
- Datos y captions: 12–14 px → `caption` y `body-sm`.
- Navegación y botones: 16–18 px → `label-lg` y `label-md`.

Se permiten palabras en vertical, números sobredimensionados y cortes tipográficos como recurso editorial, siempre que la lectura principal permanezca clara. **REVISAR:** pesos (`fontWeight`), interlineados (`lineHeight`) y `letterSpacing` no están especificados en el documento; se propusieron valores coherentes con una estética editorial.

## Layout

El sistema se inspira en portafolios editoriales: alterna composiciones limpias con páginas de mayor tensión visual. Retícula de 12 columnas en escritorio, 8 en tableta y 4 en móvil (`grid-columns-*`), con un ancho máximo de `1440px` ({spacing.max-width}). La retícula puede romperse de forma controlada con títulos grandes, imágenes recortadas o elementos que crucen columnas.

- Unidad base de espaciado: {spacing.base}. Escala: 8, 16, 24, 32, 48, 64, 96 y 128 px ({spacing.xs} a {spacing.4xl}).
- Márgenes amplios y zonas de vacío intencional para equilibrar composiciones densas.
- En proyectos se permiten layouts asimétricos, superposiciones y collage; en información funcional se prioriza alineación y lectura.

Responsive:

- **Móvil 320–599 px:** 1 columna, márgenes de {spacing.margin-mobile} (16–20 px), cuerpo mínimo de 16 px y áreas táctiles de al menos {spacing.touch-target}. Las superposiciones complejas pasan a lectura vertical; los títulos reducen escala sin perder jerarquía.
- **Tableta 600–1023 px:** 4–8 columnas, márgenes de {spacing.margin-tablet} (32–48 px), simplificación de collages complejos y composiciones de 2–3 columnas.
- **Escritorio 1024–1439 px:** retícula de 12 columnas, márgenes de {spacing.margin-desktop} a {spacing.margin-desktop-wide} (48–72 px) y mayor libertad compositiva.
- **Escritorio amplio 1440 px+:** contenido centrado con ancho máximo de {spacing.max-width} y espacios de {spacing.3xl}–{spacing.4xl} (96–128 px) entre secciones principales.

## Elevation & Depth

La profundidad no depende de sombras de interfaz, sino de capas editoriales: recortes fotográficos, texto sobre imagen, marcos, líneas, bloques de color y superposición controlada. El contraste entre planos debe sentirse gráfico antes que tridimensional. **REVISAR:** no se especifica un valor de sombra; se propone una sombra muy discreta (p. ej. `0 1px 2px rgba(0,0,0,0.08)` para elevación baja y `0 4px 8px rgba(0,0,0,0.10)` para hover) reservada únicamente a elementos interactivos. No usar sombras profundas, degradados decorativos ni texturas.

## Shapes

Predominan las formas geométricas simples, marcos rectos, líneas finas (**REVISAR:** se propone un peso de línea de 1 px) y bloques sólidos. Como contrapunto se incorporan curvas provenientes del monograma GM y de los remates tipográficos. Se evita una estética excesivamente redondeada o "app-like": la sensación debe acercarse a una publicación, cartel o dossier de diseño. Esquinas rectas o con radio mínimo de {rounded.none}–{rounded.md} (0–4 px); no se usan radios superiores a 4 px ni formas píldora.

- **Monograma GM:** recurso principal de firma; puede usarse completo, ampliado, recortado o como marca de agua. No deformarlo, estirarlo ni reconstruirlo.
- **Fotografía:** retratos, detalles de proceso y mockups con encuadres editoriales; blanco y negro o tratamiento limitado a la paleta.
- **Collage:** recortes, imágenes superpuestas, trazos o ilustraciones lineales para presentar concepto y proceso, sin saturar todas las páginas.
- **Detalles:** estrellas de cuatro puntas, líneas, marcos y numeración con moderación como acentos.

## Components

**Botones**

Construcción simple y editorial. Esquinas {rounded.md} (0–4 px). En hover se permite inversión de color, desplazamiento sutil de 1–2 px o aparición de una línea. **REVISAR:** el padding de 16 px se propone por convención; ajústalo si tienes un valor definido.

- Primario: fondo {colors.primary}, texto {colors.on-primary} (`button-primary`). Hover: inversión a {colors.surface} con texto {colors.primary} (`button-primary-hover`).
- Secundario: fondo {colors.secondary}, texto {colors.on-secondary} (`button-secondary`). Hover: inversión a {colors.surface} (`button-secondary-hover`).
- Fantasma: texto {colors.primary} con línea inferior (`button-ghost`).

**Tarjetas y proyectos**

Priorizan la imagen y el título. Modulares y limpias, o como pequeñas composiciones editoriales con número, categoría, año y frase breve. Bordes finos y esquinas rectas ({rounded.none}). El hover puede revelar datos adicionales, cambiar el contraste o desplazar la imagen ligeramente (`card-project`). **REVISAR:** el color y grosor del borde no están especificados; se propone 1 px en {colors.neutral} a baja opacidad.

**Franjas editoriales**

Para secciones de alto contraste (portadas dramáticas, citas, pie de página), se usa una franja con fondo {colors.neutral} y texto {colors.on-neutral}, esquinas rectas y padding amplio (`band-neutral`).

**Navegación y enlaces**

Discreta para no competir con el contenido: `label-lg` (16–18 px) con estados activos indicados por subrayado, cambio a {colors.primary} o azul (`nav-link` / `nav-link-active`). Los enlaces dentro del texto conservan el mismo criterio (`text-link` / `text-link-hover`). En móvil se permite menú compacto, pero las secciones Proyectos, Sobre mí y Contacto deben permanecer fáciles de localizar.

**Contacto e íconos**

Alineación limpia, íconos lineales y tipografía secundaria. Los íconos se usan sin contenedores decorativos innecesarios; pueden cambiar a {colors.primary} en hover (`icon` / `icon-hover`). **REVISAR:** se propone un tamaño de ícono de 20 px.

**Fichas de proyecto**

Cada caso de estudio combina narrativa e información: portada visual, contexto, problema, concepto, proceso, decisiones de diseño, aplicaciones y resultado. Se intercalan páginas tipográficas con otras dominadas por imágenes, manteniendo una estructura reconocible mediante numeración, títulos y márgenes constantes (`project-fiche`).

## Do's and Don'ts

**Sí**

- Usar {colors.primary} y {colors.secondary} como acentos protagonistas, dejando que blanco y negro den descanso y contraste.
- Dar protagonismo a la tipografía mediante cambios fuertes de escala y composiciones editoriales.
- Combinar orden y experimentación: una retícula clara puede romperse de manera intencional.
- Usar el monograma GM como firma, sello, recorte o elemento de gran escala.
- Presentar los proyectos de forma narrativa, mostrando tanto el resultado como el razonamiento y el proceso.
- Mantener imágenes de buena calidad y tratamientos coherentes con la paleta.

**No**

- No introducir naranja, verdes u otros colores de interfaz como acentos permanentes fuera de la paleta definida.
- No sustituir CoFo Raffine y Serenity por Raleway, PT Sans u otras tipografías dentro del sistema principal.
- No usar botones tipo píldora, exceso de esquinas redondeadas o componentes que hagan sentir el portafolio como una plantilla genérica de app.
- No saturar todas las páginas con collage: alternar intensidad y respiración visual.
- No usar sombras profundas, degradados decorativos o texturas que resten protagonismo a la tipografía y a los proyectos.
- No deformar, estirar ni reconstruir el monograma de forma que pierda sus proporciones.
