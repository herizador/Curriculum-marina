# Assets - Marina Alcain Ruano

Esta carpeta contiene todos los recursos multimedia del sitio web.

## 📁 Estructura

```
assets/
├── images/          # Imágenes de la galería y fotos profesionales
├── icons/           # Iconos personalizados (si los hay)
└── README.md        # Este archivo
```

## 🖼️ Imágenes recomendadas

### Para la galería de trabajos

**Tamaño recomendado**: 800x800px o 1200x1200px
**Formato**: JPEG, WebP o PNG
**Peso máximo**: 500KB por imagen

### Nombres sugeridos para las imágenes:

- `corte-moderno-1.jpg`
- `corte-moderno-2.jpg`
- `balayage-1.jpg`
- `balayage-2.jpg`
- `peinado-novia-1.jpg`
- `peinado-novia-2.jpg`
- `tratamiento-keratina-1.jpg`
- `color-fantasia-1.jpg`
- `recogido-elegante-1.jpg`
- `corte-asimetrico-1.jpg`

### Para el hero/portada

- `marina-profesional.jpg` (1200x800px)
- `salon-interior.jpg` (1920x1080px)

## 🔄 Cómo reemplazar los placeholders

1. **Sube tus imágenes** a la carpeta `assets/images/`

2. **Reemplaza en `index.html`**:
   ```html
   <!-- Cambiar esto -->
   <div class="aspect-square bg-gradient-to-br from-rose to-gold flex items-center justify-center">
       <div class="text-center text-white p-8">
           <i class="fas fa-image text-6xl mb-4 opacity-50"></i>
           <p class="text-lg font-semibold">Corte Moderno</p>
           <p class="text-sm opacity-75">Degradado con mechas</p>
       </div>
   </div>
   
   <!-- Por esto -->
   <img src="assets/images/corte-moderno-1.jpg" 
        alt="Corte moderno con degradado" 
        class="w-full h-full object-cover">
   ```

3. **Optimiza las imágenes**:
   - Usa herramientas como [TinyPNG](https://tinypng.com/) para comprimir
   - Convierte a WebP para mejor rendimiento
   - Añade `loading="lazy"` para carga diferida

## 📱 Responsive Images

Para mejor rendimiento en móviles, puedes usar:

```html
<picture>
    <source media="(max-width: 768px)" srcset="assets/images/corte-mobile.jpg">
    <source media="(min-width: 769px)" srcset="assets/images/corte-desktop.jpg">
    <img src="assets/images/corte-desktop.jpg" alt="Corte moderno" class="w-full h-full object-cover">
</picture>
```

## 🎨 Colores de la marca

- **Dorado principal**: #D4AF37
- **Dorado oscuro**: #B8860B
- **Rosa pastel**: #F7CAC9
- **Blanco**: #FFFFFF
- **Negro**: #000000
- **Gris**: #6B7280

## 📝 Notas importantes

- **Derechos de autor**: Asegúrate de tener permisos para usar todas las imágenes
- **Privacidad**: No subas fotos de clientes sin su consentimiento
- **Calidad**: Usa imágenes de alta calidad pero optimizadas para web
- **SEO**: Añade texto alternativo descriptivo a todas las imágenes
