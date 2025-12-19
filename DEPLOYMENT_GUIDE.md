# 🚀 Guía de Despliegue en GitHub Pages

Esta guía te ayudará a publicar tu portafolio en línea usando GitHub Pages.

## 📋 Requisitos Previos

- ✅ Tener una cuenta de GitHub
- ✅ Git instalado en tu computadora
- ✅ Tener el proyecto completo en tu computadora

## 🔧 Paso 1: Configurar Git (si no lo has hecho)

```bash
# Configurar tu nombre (usa tu nombre real)
git config --global user.name "Yennely Sharina Morillo"

# Configurar tu email (usa el mismo de GitHub)
git config --global user.email "tu-email@ejemplo.com"
```

## 📤 Paso 2: Subir Cambios al Repositorio

### Primera vez:
```bash
# 1. Ir a la carpeta del proyecto
cd "c:\Ferxxos Projects\PORT_FOLIO_SHARINA\MY-PORTFOLIO"

# 2. Agregar todos los archivos
git add .

# 3. Hacer commit
git commit -m "✨ Portafolio profesional completado"

# 4. Subir a GitHub
git push origin main
```

### Si ya has subido archivos antes:
```bash
# 1. Ver qué archivos cambiaron
git status

# 2. Agregar los cambios
git add .

# 3. Hacer commit con mensaje descriptivo
git commit -m "📝 Actualización de contenido"

# 4. Subir cambios
git push origin main
```

## 🌐 Paso 3: Activar GitHub Pages

1. **Ir a tu repositorio en GitHub**
   - https://github.com/YennelyMorillo/MY-PORTFOLIO

2. **Ir a Settings (Configuración)**
   - Click en el tab "Settings" en la parte superior

3. **Ir a Pages**
   - En el menú lateral izquierdo, busca "Pages"

4. **Configurar la fuente**
   - En "Source", selecciona: **Deploy from a branch**
   - En "Branch", selecciona: **main** (o master)
   - En la carpeta, deja: **/ (root)**
   - Click en **Save**

5. **Esperar unos minutos**
   - GitHub procesará tu sitio
   - Verás un mensaje que dice: "Your site is live at..."

## 🎉 ¡Listo! Tu Sitio Está En Línea

Tu portafolio estará disponible en:
```
https://yennelymorillo.github.io/MY-PORTFOLIO/
```

## 🔄 Actualizar Tu Sitio

Cada vez que hagas cambios y los subas a GitHub, el sitio se actualizará automáticamente:

```bash
# 1. Hacer cambios en tus archivos
# 2. Agregar y hacer commit
git add .
git commit -m "Descripción de los cambios"

# 3. Subir a GitHub
git push origin main

# 4. Esperar 1-2 minutos para ver los cambios en línea
```

## 🆘 Solución de Problemas Comunes

### Problema: No puedo hacer push
**Solución:**
```bash
# Primero hacer pull para sincronizar
git pull origin main

# Luego hacer push
git push origin main
```

### Problema: El sitio no se actualiza
**Solución:**
- Espera 2-5 minutos
- Refresca la página con Ctrl + F5 (borrar caché)
- Verifica que el commit se haya subido en GitHub

### Problema: "Permission denied"
**Solución:**
```bash
# Verificar tu autenticación
# Puede que necesites configurar un Personal Access Token
# Ve a: GitHub → Settings → Developer Settings → Personal Access Tokens
```

## 📱 Compartir Tu Portafolio

Una vez en línea, puedes compartir tu portafolio:

### Enlaces Directos:
- **Sitio Web**: https://yennelymorillo.github.io/MY-PORTFOLIO/
- **Código Fuente**: https://github.com/YennelyMorillo/MY-PORTFOLIO

### En Redes Sociales:
```
¡Mira mi nuevo portafolio profesional! 💇‍♀️✨
https://yennelymorillo.github.io/MY-PORTFOLIO/

#PeluqueraProfesional #Belleza #Estilismo
```

### En tu Perfil de Instagram/Facebook:
Agrega el enlace en tu bio o descripción

### En WhatsApp:
Puedes enviarlo directamente a tus clientas

## 🎨 Personalizar el Dominio (Opcional)

Si quieres usar tu propio dominio (ej: www.sharinapeluqueria.com):

1. Comprar un dominio en GoDaddy, Namecheap, etc.
2. En GitHub Pages Settings, agregar tu dominio personalizado
3. Configurar los DNS según las instrucciones de GitHub

## 📊 Ver Estadísticas

GitHub te permite ver:
- Número de visitas
- Páginas más vistas
- Ubicación de visitantes

Ve a: Insights → Traffic

## ✅ Checklist Final

Antes de compartir tu portafolio, verifica:

- [ ] Todas las secciones tienen contenido real
- [ ] Las imágenes se cargan correctamente
- [ ] Los enlaces de redes sociales funcionan
- [ ] El formulario de contacto está configurado
- [ ] El teléfono y email son correctos
- [ ] Se ve bien en móvil y desktop
- [ ] No hay errores de ortografía

## 🎓 Recursos Adicionales

- [Documentación oficial de GitHub Pages](https://docs.github.com/en/pages)
- [Guía de Git en español](https://git-scm.com/book/es/v2)
- [Web3Forms - Para el formulario](https://web3forms.com/)

---

**¡Felicidades! 🎉 Tu portafolio profesional está en línea y listo para impresionar a tus clientas.**
