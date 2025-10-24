# ✅ Checklist Antes de Publicar

## 📸 Assets y Medios

- [ ] Subir video del curso a YouTube
- [ ] Agregar ID del video en `src/components/VideoSection.astro`
- [ ] Agregar foto de Carolina (Hero) en `public/carolina-hero.jpg`
- [ ] Agregar foto de Carolina (About) en `public/carolina-about.jpg`
- [ ] Agregar mockup Módulo 1 en `public/modulos/modulo-1.jpg`
- [ ] Agregar mockup Módulo 2 en `public/modulos/modulo-2.jpg`
- [ ] Agregar mockup Módulo 3 en `public/modulos/modulo-3.jpg`
- [ ] Crear y agregar imagen OG en `public/og-image.jpg` (1200x630px)
- [ ] Optimizar todas las imágenes (TinyPNG, Squoosh)

## 🔗 Links y Configuración

- [ ] Actualizar link de Hotmart en `src/components/PrecioSection.astro` (línea 91)
- [ ] Actualizar link de Hotmart en `src/components/Hero.astro` (línea 28)
- [ ] Actualizar link de Instagram en `src/components/Footer.astro`
- [ ] Actualizar link de Facebook en `src/components/Footer.astro`
- [ ] Actualizar link de YouTube en `src/components/Footer.astro`
- [ ] Actualizar email de contacto en `src/components/Footer.astro`
- [ ] Verificar URL del sitio en `src/layouts/Layout.astro` (línea 11)

## 💰 Precio y Oferta

- [ ] Confirmar precio del curso ($47 USD)
- [ ] Confirmar precio tachado ($97 USD)
- [ ] Verificar garantía de 7 días
- [ ] Revisar lista de lo que incluye el curso

## 📝 Contenido y Textos

- [ ] Revisar todos los textos por errores ortográficos
- [ ] Verificar que los 3 módulos tengan la información correcta
- [ ] Confirmar biografía de Carolina Novoa
- [ ] Revisar FAQ y agregar/quitar preguntas si es necesario
- [ ] Verificar manejo de objeciones

## 🎨 Diseño y Estilo

- [ ] Probar en Chrome
- [ ] Probar en Firefox
- [ ] Probar en Safari
- [ ] Probar en dispositivos móviles (iPhone, Android)
- [ ] Probar en tablet
- [ ] Verificar que todos los colores se vean correctos
- [ ] Verificar que los gradientes funcionen bien

## 🚀 Performance y SEO

- [ ] Ejecutar Lighthouse audit (objetivo: 90+ en todas las métricas)
- [ ] Verificar PageSpeed Insights (móvil y escritorio)
- [ ] Revisar meta tags en `src/layouts/Layout.astro`
- [ ] Verificar que la descripción meta sea apropiada
- [ ] Verificar keywords
- [ ] Probar compartir en Facebook (vista previa OG)
- [ ] Probar compartir en Twitter/X
- [ ] Probar compartir en WhatsApp
- [ ] Verificar que el favicon aparezca correctamente

## 🔧 Funcionalidad

- [ ] Probar todos los botones CTA
- [ ] Verificar que el scroll suave funcione
- [ ] Probar navegación entre secciones
- [ ] Verificar que el accordion de FAQ funcione
- [ ] Probar el link de compra (que redirija a Hotmart)
- [ ] Verificar que el video de YouTube se reproduzca

## 📱 Tracking y Analytics (Opcional)

- [ ] Configurar Meta Pixel de Facebook
- [ ] Configurar Google Analytics
- [ ] Configurar Google Tag Manager
- [ ] Configurar conversiones en Hotmart
- [ ] Probar eventos de tracking

## 🌐 Deploy y Hosting

- [ ] Elegir plataforma de hosting (Netlify, Vercel, etc.)
- [ ] Configurar dominio personalizado
- [ ] Configurar SSL/HTTPS
- [ ] Configurar redirects si es necesario
- [ ] Hacer backup del código
- [ ] Ejecutar `npm run build` sin errores
- [ ] Verificar que `dist/` se genere correctamente

## ✉️ Marketing y Comunicación

- [ ] Preparar email de lanzamiento
- [ ] Crear posts para redes sociales
- [ ] Preparar historias de Instagram
- [ ] Crear anuncios de Facebook/Instagram
- [ ] Configurar secuencia de emails en Hotmart

## 📋 Legal y Compliance

- [ ] Verificar términos y condiciones
- [ ] Verificar política de privacidad
- [ ] Agregar disclaimer si es necesario
- [ ] Verificar compliance con leyes locales
- [ ] Revisar política de reembolso

## 🔒 Seguridad

- [ ] Verificar que no haya información sensible en el código
- [ ] Revisar que las API keys estén en variables de entorno
- [ ] Verificar protección HTTPS
- [ ] Revisar headers de seguridad

## 📊 Pre-Launch Testing

- [ ] Hacer compra de prueba en Hotmart
- [ ] Verificar que llegue el email de confirmación
- [ ] Verificar acceso al contenido después de compra
- [ ] Probar flujo completo de usuario
- [ ] Solicitar feedback de 2-3 personas de confianza

## 🎯 Post-Launch

- [ ] Monitorear métricas las primeras 24 horas
- [ ] Revisar tasa de conversión
- [ ] Verificar que no haya errores 404
- [ ] Revisar comentarios/feedback inicial
- [ ] Hacer ajustes según datos recopilados

---

## 📞 Recursos de Ayuda

- **INSTRUCCIONES_ASSETS.md** - Cómo actualizar todos los placeholders
- **RESUMEN_PROYECTO.md** - Información completa del proyecto
- **package.json** - Scripts disponibles
- **Astro Docs**: https://docs.astro.build

## 🎉 Cuando Todo Esté Listo

```bash
# Build final
npm run build

# Preview local del build
npm run preview

# Deploy (según tu plataforma)
# Netlify: netlify deploy --prod
# Vercel: vercel --prod
```

---

**¡Éxito con el lanzamiento de "El Poder del Agradecimiento"!**
