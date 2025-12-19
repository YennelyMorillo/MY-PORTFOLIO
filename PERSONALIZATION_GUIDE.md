# 🎨 Guía de Personalización del Portafolio

Esta guía te ayudará a personalizar completamente tu portafolio con tu información, fotos y estilos.

## 📝 1. Actualizar Información Personal

### En `index.html`:

#### Actualizar Título y Nombres
Busca y reemplaza:
```html
<!-- Línea ~168 -->
<h1 class="hero-title">Yennely Sharina Morillo Marmolejos</h1>
<p class="subtitle">Peluquera Profesional | Especialista en Belleza y Estilismo</p>
```

#### Actualizar Biografía
Busca la sección "Sobre Mí" (línea ~200) y edita los párrafos con tu propia historia.

#### Actualizar Servicios
En la sección "Servicios" (línea ~300), personaliza:
- Nombres de servicios
- Descripciones
- Características de cada servicio

#### Actualizar Testimonios
En la sección "Testimonios" (línea ~500), cambia:
- Nombres de clientas (usa solo nombres, no apellidos)
- Comentarios reales
- Fechas

## 📱 2. Actualizar Redes Sociales y Contacto

### Enlaces de Redes Sociales
Busca estos enlaces en el archivo y reemplaza con tus URLs reales:

```html
<!-- En la sección Hero (línea ~185) y Footer (línea ~620) -->
<a href="https://instagram.com/TU_USUARIO" target="_blank">
<a href="https://facebook.com/TU_PAGINA" target="_blank">
<a href="https://wa.me/18095551234" target="_blank">
<a href="mailto:tu-email@ejemplo.com">
```

### Información de Contacto en Footer
```html
<!-- Línea ~640 -->
<p><i class="fas fa-phone"></i> +1 (809) 555-1234</p>
<p><i class="fas fa-envelope"></i> tu-email@ejemplo.com</p>
<p><i class="fas fa-map-marker-alt"></i> Tu Ciudad, País</p>
```

## 🖼️ 3. Agregar tus Fotos

### Paso 1: Preparar las Imágenes

#### Foto de Perfil:
1. Usa una foto profesional tuya
2. Recórtala en formato cuadrado (500x500px mínimo)
3. Guárdala como: `assets/images/profile.jpg`

#### Logo (opcional):
1. Si tienes logo, usa formato PNG con fondo transparente
2. Tamaño recomendado: 200x200px
3. Guárdalo como: `assets/images/logo.png`

#### Galería de Trabajos:
1. Selecciona 6-12 de tus mejores trabajos
2. Tamaño recomendado: 800x800px
3. Guárdalas en: `assets/images/portfolio/`
4. Nombra descriptivamente: `corte-bob-1.jpg`, `color-balayage-1.jpg`, etc.

### Paso 2: Actualizar el HTML

#### Para la Foto de Perfil:
```html
<!-- Busca la línea ~160 y reemplaza el ícono con: -->
<div class="avatar-circle">
    <img src="assets/images/profile.jpg" alt="Yennely Sharina Morillo">
</div>
```

#### Para el Logo en el Nav:
```html
<!-- Busca la línea ~140 y reemplaza: -->
<div class="logo">
    <img src="assets/images/logo.png" alt="Logo" style="height: 50px;">
    <span style="margin-left: 10px;">Sharina</span>
</div>
```

#### Para la Galería:
```html
<!-- Busca cada .portfolio-item (línea ~420) y actualiza: -->
<div class="portfolio-item">
    <div class="portfolio-image">
        <img src="assets/images/portfolio/corte-1.jpg" alt="Corte Bob">
    </div>
    <div class="portfolio-overlay">
        <h3>Transformación de Corte</h3>
        <p>Descripción del trabajo</p>
    </div>
</div>
```

## 🎨 4. Personalizar Colores

Si quieres cambiar el esquema de colores, edita `styles.css`:

```css
/* Líneas 1-10 en styles.css */
:root {
    --primary-color: #FFB6C1;     /* Color principal (rosa) */
    --secondary-color: #FF69B4;   /* Color secundario (rosa más fuerte) */
    --accent-color: #FFC0CB;      /* Color de acento */
    --dark-bg: #0a0a0a;          /* Fondo oscuro */
    --dark-card: #1a1a1a;        /* Tarjetas */
    --text-primary: #ffffff;      /* Texto principal */
    --text-secondary: #b0b0b0;    /* Texto secundario */
}
```

### Paletas de Colores Sugeridas:

#### Opción 1: Elegante Morado
```css
--primary-color: #9b59b6;
--secondary-color: #8e44ad;
```

#### Opción 2: Dorado Luxury
```css
--primary-color: #f39c12;
--secondary-color: #e67e22;
```

#### Opción 3: Mint Fresco
```css
--primary-color: #1abc9c;
--secondary-color: #16a085;
```

## 📧 5. Configurar Formulario de Contacto

### Paso 1: Registrarse en Web3Forms
1. Ve a https://web3forms.com/
2. Regístrate gratis con tu email
3. Copia tu "Access Key"

### Paso 2: Actualizar el HTML
```html
<!-- Busca la línea ~680 y reemplaza: -->
<input type="hidden" name="access_key" value="AQUI_TU_ACCESS_KEY">
```

### Paso 3: Personalizar Email de Confirmación (opcional)
En Web3Forms puedes configurar:
- Email de respuesta automática
- Plantilla personalizada
- Redirección después de enviar

## ✏️ 6. Actualizar Habilidades y Experiencia

### Editar Barras de Progreso:
```html
<!-- Busca la sección Skills (línea ~480) -->
<div class="skill-item">
    <span>Tu Habilidad</span>
    <div class="skill-bar">
        <div class="skill-fill" style="width: 95%"></div>
    </div>
</div>
```
Cambia el porcentaje (width: 95%) según tu nivel real.

### Editar Certificaciones:
```html
<!-- Línea ~560 -->
<div class="cert-item">
    <i class="fas fa-certificate"></i>
    <span>Nombre de tu Certificación</span>
</div>
```

## 🔍 7. Optimización SEO

### Actualizar Meta Tags
En el `<head>` del HTML:
```html
<meta name="description" content="Tu descripción única aquí">
<meta name="keywords" content="peluquera, belleza, estilismo, tu ciudad">
<meta name="author" content="Tu Nombre">
```

### Agregar Open Graph (para compartir en redes)
```html
<meta property="og:title" content="Tu Nombre - Peluquera Profesional">
<meta property="og:description" content="Tu descripción">
<meta property="og:image" content="URL_de_tu_foto">
<meta property="og:url" content="URL_de_tu_sitio">
```

## 📏 8. Ajustar Estadísticas

```html
<!-- Línea ~235 -->
<div class="stat-item">
    <h3>5+</h3>
    <p>Años de Experiencia</p>
</div>
```
Actualiza los números con tus datos reales.

## 🎯 9. Checklist de Personalización

- [ ] Nombre y título actualizado
- [ ] Biografía con tu historia
- [ ] Servicios personalizados
- [ ] Foto de perfil agregada
- [ ] Logo agregado (si aplica)
- [ ] Galería de trabajos con tus fotos
- [ ] Redes sociales actualizadas
- [ ] Teléfono y email correctos
- [ ] Testimonios reales
- [ ] Habilidades y niveles ajustados
- [ ] Certificaciones actualizadas
- [ ] Formulario de contacto configurado
- [ ] Colores personalizados (opcional)
- [ ] Horarios de atención actualizados

## 💡 Tips Finales

1. **Usa contenido real**: No dejes textos de ejemplo
2. **Pide permiso**: Antes de usar fotos de clientas
3. **Mantén actualizado**: Agrega nuevos trabajos regularmente
4. **Optimiza imágenes**: Usa herramientas como TinyPNG antes de subir
5. **Prueba en móvil**: Verifica que todo se vea bien en celular
6. **Revisa ortografía**: Usa corrector antes de publicar

## 🆘 ¿Necesitas Ayuda?

Si tienes dudas sobre cómo editar algo específico:
1. Busca el texto en el archivo HTML usando Ctrl+F
2. Edita con cuidado, sin borrar etiquetas HTML
3. Guarda y recarga la página en el navegador
4. Si algo sale mal, usa Ctrl+Z para deshacer

---

**¡Éxito con tu portafolio! 🌟**
