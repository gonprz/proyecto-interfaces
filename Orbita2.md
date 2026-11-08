# Órbita 2: sistema visual de **OUTIFY**

## Enlaces

| Qué | Enlace |
|---|---|
| Archivo de Figma (versión "Entrega Órbita 2") |https://www.figma.com/design/sV91qGglKWmJEgOTmBeQnE/Mockups?node-id=18-1623&t=9TqAnVJec13rMBVS-1|
| Prototipo (enlace que empieza por `figma.com/proto/`) |https://www.figma.com/proto/sV91qGglKWmJEgOTmBeQnE/Mockups?t=GqdhUwTFOXkCpQiE-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&node-id=3-43&starting-point-node-id=3%3A43|
| Prototipo Sobremesa | https://www.figma.com/proto/sV91qGglKWmJEgOTmBeQnE/Mockups?node-id=18-1625&t=89cdveM0H860WM1Y-1&scaling=scale-down&content-scaling=fixed&page-id=18%3A1623 |
| Proyecto de Google Stitch (solo si lo has usado) | |

## Dónde está cada cosa en Figma

| Entregable | Página y sección del archivo |
|---|---|
| Inventario de decisiones |Página 4(Guía de Estilo)|
| Wireframes rediseñados con sus notas |Página 4(Guía de Estilo)|
| Componentes |Página 4(Guía de Estilo) Al lado de las pantallas en "Decisiones Visuales"|
| Mockups del happy path |Página 1(Mockup Dispositivo Móvil)|
| Pantalla principal en el segundo ancho |Página 2 (Mockup Tablet)|
| Pantallas en modo oscuro |Página 1(Mockup Dispositvo Móvil) y Página 3 (Mockup Sobremesa)|
| Guía de estilo |Página 4(Guía de Estilo)|

## Lista de comprobación de Figma

- [X] Variables en dos colecciones (primitivos y semánticos), con alias, modos claro y oscuro, ámbito, descripción y sintaxis de código.
- [X] Estilos de texto, efecto y retícula vinculados a las variables.
- [X] Componentes con Auto layout, variables, propiedades y variantes de estado.
- [ ] Mockups construidos enteros con Auto layout y espacios sacados de variables.
- [X] Pantalla principal en un segundo ancho, con los mismos componentes.
- [X] Modo oscuro aplicado con el selector de modo.
- [X] Prototipo que recorre el happy path completo.
- [X] Prueba 1 superada: al cambiar `color/primary`, cambian todas las pantallas a la vez.
- [X] Prueba 2 superada: con todos los mockups en modo oscuro, nada desaparece contra el fondo.

## Resumen de decisiones

### Rediseño de los wireframes
Se han cambiado todas las pantallas para que se viesen más limpias y que hubiese mas separación entre los elementos para tener mas orden visual.

### Color
El color principal de la aplicación es 2F2D2E (Gris Oscuro), y el color secundario 0582CA (Azul)

Se eligieron estos colores porque el gris oscuro los tonos oscuros o neutros transmiten sofisticación, modernidad y exclusividad,
reduce la fatiga visual al usuario al navegar durante largos períodos de tiempo, perfecto para las personas que pasan mucho tiempo buscando en la aplicación inspiración o nuevas prendas de ropa.

El azul transmite profesionalidad, seguridad y transparencia, como es una aplicación que cuenta con un mercado de subastas genera confianza desde un primer momento.

En modo claro el contraste más bajo es de 3.75:1 entre el gris oscuro y el negro, no es tan evidente porque es usado con elementos de navegación que siguen siendo bien visibles, no se utiliza con textos.

En modo oscuro es el mismo contraste entre los mismos colores, no se nota porque se usa solo para barras que separan secciones y en bordes de barras de búsqueda y en los campos para introducir precios, siguen siendo bien visibles en el fondo negro.

### Tipografía
Se usa la fuente Plus Jakarta Sans, a diferencia de la fuente Inter, esta tiene remates ligeramente más redondeados y abiertos, dándole a la app una identidad más juvenil, fresca y dinámica, al poseer trazos limpios permite que los títulos grandes, los nombres de las prendas y los detalles de cada publicación se lean con mucha claridad sin perder la elegancia. 

Se usa 24px para los "title", 20px para los "title h2", 16px para los "title h3", 15px para el "body", 14px para el "body secondary" y 12px para "caption", que son como ejemplo la hora a la que se publicó algo.

### Espaciado y retícula

Se ha utilizado una retícula de 4 columnas centradas con un ancho de 75, para que todo esté bien separado, legible y ordenado.

### Componentes
Como ejemplo los botones de pujar en la pestaña subastas que tendrián el valor estaPujando que sería true o false para mostar el texto o que está cargando.

### Responsive y modo oscuro
Qué tuviste que ajustar al pasar la pantalla principal al segundo ancho, y qué corregiste en tus variables al pasar los mockups a modo oscuro.

## Uso de IA
En esta entrega de la órbita 2 se ha utilizado la IA para aconsejar sobre colores que vayan bien en el modo oscuro y que concuerden con los que se usan en el modo claro para no perder contraste.

También se ha usado para hacer una criba de fuentes para saber cuál puede ser la mejor sin perder la esencia de la aplicación.

## Lo que ha quedado pendiente
En esta entrega no he conseguido aplicar los auto-layouts, después de haberlos visto en clase y con varios tutoriales de Youtube no he conseguido poder implementarlos por no haber entendido como hacerlos.
