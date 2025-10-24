# Instrucciones para Actualizar Assets

Esta landing page está completamente funcional pero utiliza placeholders en lugar de las imágenes reales. Aquí están las instrucciones para actualizar cada asset cuando los tengas disponibles.

## 1. Video de YouTube

**Ubicación:** `src/components/VideoSection.astro` (línea ~20)

**Qué hacer:**
1. Sube el video del curso a YouTube
2. Obtén el ID del video (el código después de `v=` en la URL)
3. Reemplaza el placeholder comentado con:

```html
<iframe
  class="w-full aspect-video"
  src="https://www.youtube.com/embed/TU_VIDEO_ID"
  title="El Poder del Agradecimiento"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen
></iframe>
```

## 2. Imagen de Carolina Novoa (Hero)

**Ubicación:** `src/components/Hero.astro` (línea ~37)

**Qué hacer:**
1. Guarda la imagen de Carolina en `public/carolina-hero.jpg` (o formato que prefieras)
2. Reemplaza el div placeholder con:

```html
<img
  src="/carolina-hero.jpg"
  alt="Carolina Novoa - Terapeuta Espiritual"
  class="w-full h-full object-cover"
/>
```

## 3. Imagen de Carolina Novoa (Sobre Section)

**Ubicación:** `src/components/SobreCarolina.astro` (línea ~17)

**Qué hacer:**
1. Guarda la imagen profesional de Carolina en `public/carolina-about.jpg`
2. Reemplaza el div placeholder con:

```html
<img
  src="/carolina-about.jpg"
  alt="Carolina Novoa - Terapeuta Espiritual y Health Coach"
  class="w-full h-full object-cover"
/>
```

## 4. Mockups de los Módulos

**Ubicación:** `src/components/ModulosSection.astro` (líneas ~142-184)

**Qué hacer:**
1. Guarda los mockups en `public/modulos/`:
   - `public/modulos/modulo-1.jpg`
   - `public/modulos/modulo-2.jpg`
   - `public/modulos/modulo-3.jpg`

2. Reemplaza cada placeholder div con:

```html
<img
  src="/modulos/modulo-1.jpg"
  alt="Módulo 1 - Fundamentos del Agradecimiento"
  class="w-full h-full object-cover"
/>
```

## 5. Banner de Hotmart

**Ubicación:** Si quieres usar el banner en alguna sección

**Qué hacer:**
1. Guarda el banner en `public/banner-hotmart.jpg`
2. Úsalo donde lo necesites

## 6. Imagen OG para SEO

**Ubicación:** `src/layouts/Layout.astro` (línea 13)

**Qué hacer:**
1. Crea una imagen OG de 1200x630px con el título del curso
2. Guárdala en `public/og-image.jpg`
3. Esta imagen se usará cuando compartan la página en redes sociales

## 7. Link de Hotmart

**Ubicación:** `src/components/PrecioSection.astro` (línea ~91)

**Qué hacer:**
1. Obtén tu link de afiliado/venta de Hotmart
2. Reemplaza `https://pay.hotmart.com/TU_LINK_DE_HOTMART` con tu link real

**IMPORTANTE:** También actualiza el mismo link en:
- `src/components/Hero.astro` (línea ~28) - Botón "Acceder al Curso"

## 8. Enlaces de Redes Sociales

**Ubicación:** `src/components/Footer.astro` (líneas ~40-72)

**Qué hacer:**
Reemplaza los enlaces de ejemplo con los reales:
- Instagram: https://instagram.com/carolinanovoa
- Facebook: https://facebook.com/carolinanovoa
- YouTube: https://youtube.com/@carolinanovoa
- Email: contacto@carolinanovoa.com

## 9. Meta Pixel de Facebook (Opcional)

Si quieres agregar el Meta Pixel para tracking:

**Ubicación:** `src/layouts/Layout.astro`

**Qué hacer:**
1. Obtén tu Pixel ID de Facebook Business Manager
2. Agrega el código del pixel similar al que está en el ejemplo de referencia

## Estructura de Carpeta Public Recomendada

```
public/
├── favicon.svg
├── iconxd.png
├── og-image.jpg
├── carolina-hero.jpg
├── carolina-about.jpg
├── banner-hotmart.jpg
└── modulos/
    ├── modulo-1.jpg
    ├── modulo-2.jpg
    └── modulo-3.jpg
```

## Pruebas Antes de Publicar

1. **Verifica todos los links** - Especialmente el de Hotmart
2. **Prueba el video de YouTube** - Asegúrate de que se reproduzca correctamente
3. **Revisa las imágenes** - Que no estén pixeladas o muy pesadas
4. **Optimiza las imágenes** - Usa herramientas como TinyPNG o Squoosh
5. **Prueba en móvil** - La landing debe verse perfecta en todos los dispositivos
6. **Verifica el SEO** - Usa herramientas como Lighthouse o PageSpeed Insights

## Comandos para Desarrollo

```bash
# Instalar dependencias (si aún no lo has hecho)
npm install

# Ejecutar en modo desarrollo
npm run dev

# Construir para producción
npm run build

# Vista previa de la versión de producción
npm run preview
```

## Contacto

Si tienes alguna pregunta sobre cómo actualizar cualquier elemento, no dudes en preguntar.
