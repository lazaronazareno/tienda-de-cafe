# Tienda de Café - Proyecto Web

Este proyecto es una recreación del sitio web de Tienda de Café (https://tiendadecafe.com.ar/) con una estructura básica de ruteo y diseño responsive.

## Estructura del Proyecto

```
tienda-de-cafe/
├── index.html              # Página principal con todas las secciones
├── nuestro-cafe.html       # Página de productos de café
├── tutoriales.html         # Página de tutoriales
├── locales.html           # Página de locales
├── menu.html              # Página del menú
├── trabaja-con-nosotros.html # Página de empleos
├── franquicias.html       # Página de franquicias
├── contacto.html          # Página de contacto
├── css/
│   └── styles.css         # Archivo CSS global
├── images/                # Carpeta para imágenes
└── README.md             # Este archivo
```

## Características Implementadas

### Página Principal (index.html)

- **Header fijo** con navegación a todas las páginas
- **Hero Section** con slider automático sin JavaScript (solo CSS)
  - 3 slides con transiciones automáticas
  - Navegación por puntos
- **Sección de Productos** con slider horizontal de productos de café
- **Sección de Destacados** con dos imágenes (Secretos del Barista y Nuestros Platos)
- **Sección Nuestro Café** con descripción detallada de 6 tipos de café
- **Call-to-Action de Locales** con estilo atractivo
- **Sección de Newsletter** para suscripción
- **Footer completo** con enlaces organizados

### Características Técnicas

- **Diseño responsive** para móviles, tablets y desktop
- **CSS Grid y Flexbox** para layouts modernos
- **Slider sin JavaScript** usando CSS animations y radio buttons
- **Paleta de colores** basada en tonos marrones (#8B4513, #A0522D)
- **Tipografía** clara y legible
- **Efectos hover** y transiciones suaves
- **Navegación activa** que muestra la página actual

### Ruteo

Todas las páginas están interconectadas con:

- Header común con navegación completa
- Footer común con enlaces organizados
- Enlaces activos que cambian según la página actual
- Las páginas secundarias tienen contenido placeholder

## Slider Hero (Sin JavaScript)

El slider utiliza:

- Radio buttons ocultos para controlar las slides
- CSS transitions para cambios suaves
- Animation keyframes para auto-play de 3 segundos por slide
- Puntos de navegación interactivos

## Responsividad

- **Desktop**: Layout completo con grids de múltiples columnas
- **Tablet**: Adaptación de grids a 2 columnas
- **Mobile**: Layout de una columna con menú hamburguesa

## Próximos Pasos

1. Agregar imágenes reales en la carpeta `images/`
2. Implementar contenido real en las páginas secundarias
3. Agregar funcionalidad JavaScript para el menú hamburguesa
4. Implementar formularios funcionales
5. Optimizar SEO y meta tags

## Imágenes Necesarias

Para completar el diseño, agregar estas imágenes en la carpeta `images/`:

- `logo.png` - Logo de Tienda de Café
- `hero-capsulas.jpg` - Imagen de cápsulas de café
- `hero-tostado.jpg` - Imagen de proceso de tostado
- `hero-locales.jpg` - Imagen de locales
- Productos de café (6 imágenes)
- Imágenes de cafés individuales (6 imágenes)
- `secretos-barista.jpg` y `nuestros-platos.jpg`

## Tecnologías Utilizadas

- HTML5 semántico
- CSS3 con Grid, Flexbox y Animations
- Diseño Mobile-First
- Metodología BEM para nomenclatura CSS
