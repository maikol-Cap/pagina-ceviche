# Ceviche Peruano - Landing Page

Landing page informativo sobre el ceviche peruano, desarrollada como proyecto de aprendizaje y demostración de habilidades en HTML, CSS y JavaScript.

## 📋 Descripción del Proyecto

Página web responsiva que presenta la receta auténtica del ceviche peruano, incluyendo historia, ingredientes, preparación paso a paso y galería visual.

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos con variables CSS, diseño responsive
- **JavaScript** - Interactividad y animaciones
- **Remix Icons** - Biblioteca de iconos
- **ScrollReveal** - Animaciones de scroll

## 📝 Historial de Desarrollo

### Paso 1: Clonado del Repositorio Base
Se clonó el repositorio base de sushi para usar como plantilla:
```bash
git clone https://github.com/bedimcode/responsive-sushi-website-2.git
```

### Paso 2: Estructura del HTML
Se personalizó el archivo `index.html` creando las siguientes secciones:
- **Header/Navbar**: Navegación con logo y enlaces
- **Hero (Inicio)**: Título principal, subtítulo y botón de acción
- **Historia**: Sección sobre el origen del ceviche peruano
- **Ingredientes**: Grid con los 6 ingredientes principales
- **Receta**: Pasos detallados para preparar el ceviche
- **Tiempo y Porciones**: Información de preparación
- **Galería**: Imágenes del plato terminado
- **Footer**: Créditos finales

### Paso 3: Sistema de Diseño y Paleta de Colores
Se implementó la paleta de colores sugerida:

| Color | Valor | Uso |
|-------|-------|-----|
| Fondo principal | `#FEF2F2` | Background general |
| Texto principal | `#450A0A` | Títulos y texto |
| Primario | `#DC2626` | Botones, footer, acentos |
| Secundario | `#F87171` | Colores claros |
| Acento amarillo | `#A16207` | Detalles |
| Borde | `#FECACA` | Bordes de tarjetas |

### Paso 4: Tipografía
Se cambió la tipografía según las recomendaciones de UI/UX Pro Max:
- **Títulos**: Playfair Display SC (serif, elegante)
- **Body**: Karla (sans-serif, legible)

```css
@import url("https://fonts.googleapis.com/css2?family=Karla:wght@300;400;500;600;700&family=Playfair+Display+SC:wght@400;700&display=swap");
```

### Paso 5: Estilos CSS (Flat Design)
Se aplicaron estilos siguiendo el patrón Flat Design Mobile:
- Botones sin border-radius (estilo square)
- Tarjetas con bordes sólidos (sin sombras)
- Interacciones con scale(0.97) en hover/press
- Transiciones rápidas (150-300ms)

### Paso 6: Ajustes de Layout
- Contenedores centrados con `margin-inline: auto`
- Header height aumentado a 5rem
- Secciones con padding vertical reducido
- Navbar: Logo a la izquierda, menús a la derecha
- Enlaces del navbar centrados verticalmente

### Paso 7: Imágenes
Se actualizaron todas las imágenes con fotos reales del ceviche:
- `hero-ceviche.png` - Imagen principal del hero
- `historia-ceviche.png` - Imagen de la sección historia
- `receta-pescado.jpg` - Imagen del ingrediente pescado
- `receta-limon.jpg` - Imagen del ingrediente limón
- `receta-cebolla.jpg` - Imagen del ingrediente cebolla
- `receta-ajilimo.webp` - Imagen del ingrediente ají
- `receta-cilantro.webp` - Imagen del ingrediente cilantro
- `receta-chocloycamote.jpg` - Imagen de acompañamiento
- `galeria-ceviche.jpg` - Imagen para galería
- `galeria-ingredientesfrescos.webp` - Imagen para galería

### Paso 8: Modificaciones en la Galería
Se eliminó la tarjeta de "Acompañamientos" de la sección galería, deixando solo 2 tarjetas:
1. El Plato Perfecto
2. Ingredientes Frescos

### Paso 9: JavaScript
Se implementó funcionalidad en `main.js`:
- Menú móvil (abrir/cerrar)
- Scroll header (cambios al hacer scroll)
- Scroll up (botón para subir)
- Scroll active (sección actual resaltada)
- Animaciones con ScrollReveal

## 📁 Estructura de Archivos

```
responsive-sushi-website-2/
├── index.html              # Archivo principal HTML
├── assets/
│   ├── css/
│   │   └── styles.css     # Estilos principales
│   ├── js/
│   │   └── main.js        # Funcionalidad JavaScript
│   └── img/
│       └── *.png/jpg/webp # Imágenes del proyecto
├── README.md              # Documentación
└── preview.png            # Vista previa del proyecto
```

## 🎨 Personalización

### Cambiar Colores
Los colores están definidos como variables CSS en `styles.css`:
```css
:root {
  --first-color: #DC2626;
  --body-color: #FEF2F2;
  --title-color: #450A0A;
  /* ... más variables */
}
```

### Añadir Nuevas Secciones
1. Agregar la sección en `index.html`
2. Añadir estilos CSS correspondientes
3. Actualizar el navbar con el nuevo enlace

## 📱 Diseño Responsivo

El proyecto está diseñado con metodología Mobile First:
- **Móvil**: 375px+
- **Tablet**: 768px+
- **Desktop**: 1150px+

## 🔧 Ejecutar el Proyecto

Simplemente abre el archivo `index.html` en tu navegador:

```bash
# Opción 1: Abrir directamente
open index.html

# Opción 2: Usar un servidor local
npx serve .
```

## 📜 Licencia

Este proyecto es de uso libre para fines educativos y de demostración.

---

**Desarrollado con ❤️ para la comunidad de amantes del ceviche peruano**
