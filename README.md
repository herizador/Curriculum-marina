# Marina Alcain Ruano - Portafolio de Peluquería

Una página web moderna y responsive para el portafolio profesional de Marina Alcain Ruano, especialista en peluquería.

## 🌟 Características

- **Diseño moderno y elegante** con paleta de colores blanco, negro y dorado
- **Totalmente responsive** - optimizado para móviles, tablets y desktop
- **Animaciones suaves** con efectos de scroll y hover
- **Formulario de contacto funcional** con validación
- **Galería de trabajos** con grid responsive
- **Secciones completas**: Inicio, Sobre mí, Servicios, Galería, Testimonios y Contacto
- **Optimizado para SEO** con meta tags apropiados
- **Listo para desplegar** en GitHub Pages y Render

## 🚀 Despliegue en GitHub Pages

### Opción 1: Despliegue automático (Recomendado)

1. **Fork o clona este repositorio**
   ```bash
   git clone https://github.com/tu-usuario/marina-peluqueria.git
   cd marina-peluqueria
   ```

2. **Sube el código a tu repositorio de GitHub**
   ```bash
   git add .
   git commit -m "Portafolio de Marina Alcain Ruano"
   git push origin main
   ```

3. **Activa GitHub Pages**
   - Ve a tu repositorio en GitHub
   - Haz clic en **Settings** (Configuración)
   - Desplázate hasta **Pages** en el menú lateral
   - En **Source**, selecciona **Deploy from a branch**
   - Selecciona **main** como branch
   - Haz clic en **Save**

4. **¡Listo!** Tu sitio estará disponible en:
   `https://tu-usuario.github.io/marina-peluqueria`

### Opción 2: Despliegue manual

1. **Crea un repositorio nuevo** en GitHub llamado `marina-peluqueria`

2. **Sube los archivos**
   ```bash
   git init
   git add .
   git commit -m "Portafolio de Marina Alcain Ruano"
   git branch -M main
   git remote add origin https://github.com/tu-usuario/marina-peluqueria.git
   git push -u origin main
   ```

3. **Sigue los pasos 3-4 de la Opción 1**

## 🌐 Despliegue en Render

### Paso a paso para Render

1. **Prepara tu repositorio**
   - Asegúrate de que tu código esté en GitHub
   - Los archivos deben estar en la raíz del repositorio

2. **Crea una cuenta en Render**
   - Ve a [render.com](https://render.com)
   - Regístrate con tu cuenta de GitHub

3. **Crea un nuevo servicio**
   - Haz clic en **New +**
   - Selecciona **Static Site**

4. **Configura el servicio**
   - **Name**: `marina-peluqueria` (o el nombre que prefieras)
   - **Repository**: Selecciona tu repositorio de GitHub
   - **Branch**: `main`
   - **Root Directory**: Deja vacío (los archivos están en la raíz)
   - **Build Command**: Deja vacío
   - **Publish Directory**: Deja vacío

5. **Despliega**
   - Haz clic en **Create Static Site**
   - Render construirá y desplegará tu sitio automáticamente
   - Tu sitio estará disponible en: `https://marina-peluqueria.onrender.com`

## 📁 Estructura del proyecto

```
marina-peluqueria/
├── index.html          # Página principal
├── script.js           # JavaScript con animaciones y funcionalidades
├── README.md           # Este archivo
└── assets/             # (Opcional) Para imágenes futuras
    ├── images/
    └── icons/
```

## 🎨 Personalización

### Cambiar información personal

1. **Datos de contacto** en `index.html`:
   - Busca y reemplaza el número de teléfono: `+34 123 456 789`
   - Cambia el email: `marina@peluqueria.com`
   - Actualiza la dirección en la sección de contacto

2. **Redes sociales** en `index.html`:
   - Cambia los enlaces de WhatsApp, Instagram y Facebook
   - Actualiza los usernames en `script.js`

3. **Contenido personalizado**:
   - Modifica la biografía en la sección "Sobre mí"
   - Actualiza los servicios ofrecidos
   - Añade testimonios reales de clientes

### Añadir imágenes reales

1. **Crea una carpeta `assets/images/`**
2. **Reemplaza los placeholders** en la galería:
   ```html
   <!-- Cambiar esto -->
   <div class="aspect-square bg-gradient-to-br from-rose to-gold">
   
   <!-- Por esto -->
   <img src="assets/images/corte-1.jpg" alt="Corte moderno" class="w-full h-full object-cover">
   ```

3. **Optimiza las imágenes**:
   - Usa formatos WebP o JPEG
   - Redimensiona a máximo 800x800px
   - Comprime para web

### Cambiar colores

En `index.html`, modifica la configuración de TailwindCSS:
```javascript
colors: {
    'gold': '#D4AF37',        // Color dorado principal
    'rose': '#F7CAC9',        // Color rosa pastel
    'dark-gold': '#B8860B',   // Dorado oscuro
}
```

## 🔧 Funcionalidades técnicas

### JavaScript incluido

- **Navegación suave** entre secciones
- **Animaciones de scroll** (fade-in)
- **Menú móvil** responsive
- **Formulario de contacto** con validación
- **Efectos hover** en galería y servicios
- **Notificaciones** para el formulario
- **Integración con WhatsApp** e Instagram

### CSS y diseño

- **TailwindCSS** para estilos
- **Font Awesome** para iconos
- **Google Fonts** (Playfair Display + Inter)
- **Diseño responsive** con breakpoints
- **Animaciones CSS** personalizadas

## 📱 Optimización móvil

La página está completamente optimizada para dispositivos móviles:

- **Menú hamburguesa** en pantallas pequeñas
- **Grid responsive** que se adapta a cualquier tamaño
- **Botones táctiles** optimizados
- **Texto legible** en todos los dispositivos
- **Carga rápida** en conexiones lentas

## 🚀 Mejoras futuras

### Funcionalidades que se pueden añadir

1. **Sistema de reservas online**
2. **Blog de consejos de belleza**
3. **Galería con lightbox**
4. **Chat en vivo**
5. **Sistema de reviews**
6. **Integración con Google Maps**
7. **Analytics de Google**

### Para añadir reservas online

```html
<!-- Añadir en la sección de servicios -->
<div class="bg-white rounded-2xl shadow-lg p-8">
    <h3 class="text-xl font-serif font-semibold mb-4">Reservar cita</h3>
    <a href="https://calendly.com/marina-alcain" 
       class="bg-gold hover:bg-dark-gold text-white px-6 py-3 rounded-lg font-semibold transition-all duration-300">
        Reservar ahora
    </a>
</div>
```

## 🆘 Solución de problemas

### GitHub Pages no actualiza

1. Verifica que el branch sea `main`
2. Espera 5-10 minutos para la propagación
3. Limpia la caché del navegador (Ctrl+F5)

### Render no despliega

1. Verifica que el repositorio sea público
2. Asegúrate de que `index.html` esté en la raíz
3. Revisa los logs de build en Render

### Formulario no funciona

El formulario está configurado para mostrar notificaciones. Para funcionalidad real:

1. **Usa un servicio como Formspree**:
   ```html
   <form action="https://formspree.io/f/tu-id" method="POST">
   ```

2. **O integra con Netlify Forms**:
   ```html
   <form name="contact" method="POST" data-netlify="true">
   ```

## 📞 Soporte

Si tienes problemas con el despliegue o necesitas personalizaciones adicionales:

1. **Revisa este README** primero
2. **Consulta la documentación** de GitHub Pages o Render
3. **Verifica que todos los archivos** estén en el repositorio

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Puedes usarlo libremente para tu portafolio personal.

---

**¡Disfruta de tu nueva página web profesional!** 🎉

*Creado con ❤️ para Marina Alcain Ruano*
