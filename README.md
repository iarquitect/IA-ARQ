# Sitio Web Personal

Sitio web personal inspirado en el diseño minimalista de Arturo Tedeschi, con secciones para proyectos, cursos, noticias, entrevistas y clientes.

## Características

- **Diseño Minimalista**: Estilo limpio y elegante
- **Totalmente Responsive**: Adaptado para dispositivos móviles, tablets y escritorio
- **Navegación Suave**: Scroll suave entre secciones
- **Animaciones Sutiles**: Efectos de fade-in y hover para mejorar la experiencia
- **Secciones Incluidas**:
  - Hero/Inicio
  - Proyectos (con grid de tarjetas)
  - Cursos (lista detallada)
  - Noticias (blog/actualizaciones)
  - Entrevistas & Radio (podcasts, radio, videos)
  - Clientes (grid de logos)
  - Contacto

## Personalización

### 1. Información Personal
Edita `index.html` y reemplaza:
- "Tu Nombre" con tu nombre real
- "Profesión / Especialidad" con tu título profesional
- La descripción en la sección hero
- Los enlaces de contacto (email, LinkedIn, Instagram)

### 2. Proyectos
En la sección de proyectos, reemplaza:
- Los títulos de los proyectos
- Las descripciones
- Los años
- Las imágenes placeholder con tus propias imágenes

### 3. Cursos
Actualiza la información de los cursos:
- Títulos
- Descripciones
- Fechas
- Ubicación (Online/Presencial)
- Duración

### 4. Noticias
Agrega tus propias noticias con:
- Fechas
- Títulos
- Resúmenes
- Enlaces a artículos completos

### 5. Entrevistas
Incluye tus entrevistas con:
- Tipo de medio (Podcast, Radio, Video)
- Título
- Descripción
- Fecha
- Enlace para escuchar/ver

### 6. Clientes
Reemplaza los placeholders con:
- Logos de tus clientes (imágenes)
- Nombres de clientes
- Descripción del proyecto realizado

### 7. Colores y Tipografía
En `styles.css`, puedes personalizar los colores en la sección `:root`:
```css
:root {
    --primary-color: #000;
    --secondary-color: #666;
    --accent-color: #333;
    --bg-color: #fff;
    --bg-alt: #f8f8f8;
    /* ... */
}
```

## Agregar Imágenes

1. Crea una carpeta `images` en la raíz del proyecto (si no existe)
2. Agrega tus imágenes de proyectos, clientes, etc.
3. Reemplaza los `<div class="placeholder-image">` con:
```html
<img src="images/tu-imagen.jpg" alt="Descripción">
```

## Estructura de Archivos

```
.
├── index.html      # Estructura HTML principal
├── styles.css      # Estilos y diseño
├── script.js       # Funcionalidad JavaScript
├── images/         # Carpeta para imágenes
└── README.md       # Este archivo
```

## Uso

Simplemente abre `index.html` en tu navegador web. No se requiere servidor ni instalación de dependencias.

Para desarrollo local con live reload, puedes usar:
- VS Code con Live Server extension
- Python: `python -m http.server 8000`
- Node.js: `npx serve`

## Navegación

El sitio incluye:
- Menú de navegación fijo en la parte superior
- Enlaces de navegación suave entre secciones
- Menú hamburguesa para dispositivos móviles

## Licencia

Personaliza y usa este sitio como desees para tu portafolio personal.
