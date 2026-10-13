# Kondorflow — Sitio Web Oficial

**HG Next Gen Solutions** · Perú · Uruguay · LATAM  
Landing page institucional en HTML/CSS/JS puro — sin frameworks externos.  
Lema: **Scale, Automate, Flow.**  
Posicionamiento: agencia de marketing digital e IA con equipos en Perú y Uruguay para toda Latinoamérica.

## 📁 Estructura del repositorio

```
/
├── index.html                  ← Página principal (landing page completa)
├── thank-you.html              ← Agradecimiento tras enviar el formulario (/thank-you)
├── pago-exitoso.html           ← Página post-pago Mercado Pago
├── 404.html                    ← Página de error personalizada
├── CNAME                       ← Dominio personalizado GitHub Pages
├── sitemap.xml                 ← Mapa del sitio para Google
├── robots.txt                  ← Permisos para buscadores
├── site.webmanifest            ← Config PWA (íconos icon-192 / icon-512)
│
├── og-image.jpg                ← Imagen al compartir en redes y WhatsApp (1200×630)
├── kondorlogo1.png             ← Logo cóndor 1024 px (datos estructurados)
├── kondorlogo1.webp            ← Logo cóndor 640 px (nav, hero, footer)
├── favicon.ico / favicon-16x16.png / favicon-32x32.png / apple-touch-icon.png
├── icon-192.png / icon-512.png ← Íconos de la app web (manifest)
├── kondorlogo2.png             ← Logo horizontal (sin uso actualmente)
│
└── logos de clientes (reemplazar con logos reales):
    ├── logo-save.webp              260×120px, fondo transparente
    ├── logo-clinica-benavides.webp 260×120px, fondo transparente
    ├── logo-black-diamond.webp     260×120px, fondo transparente
    └── logo-good-way-clean.webp    260×120px, fondo transparente
```

Mientras un logo de cliente sea el marcador de 1×1 px, la web muestra las iniciales del cliente.
Al subir el logo real con el mismo nombre de archivo, aparece solo (no hay que tocar el código).

## 🧩 Servicios (sección por pilares)

| Pilar | Servicios |
|---|---|
| Atrae más clientes | Sitios web y landing pages · SEO · WordPress · Contenido para redes sociales |
| Vende y atiende 24/7 | Agentes de IA · Chatbots con IA (RAG) · WhatsApp Business con IA · Automatización de procesos |
| Escala tu operación | Software a medida y SaaS · Analítica y BI · Ciencia de datos · Soporte y correo corporativo |

Más el paquete **Solución Digital 360°**. Si cambias un servicio, cámbialo también en el schema `OfferCatalog`
y en las opciones del formulario (`servicio`).

## 🎨 Sistema de diseño (v3)

Los colores están como variables en el `:root` de cada página.

| Rol | Color | Uso |
|---|---|---|
| Violeta eléctrico | `#4B02F3` | Botones, enlaces, íconos y foco |
| Violeta profundo | `#490FCD` | Hover de botones y enlaces |
| Verde lima | `#C1FF72` | Solo en el logo y el indicador "Disponible ahora" |
| Tinta | `#181336` | Titulares, secciones oscuras y footer |
| Papel / tinte | `#F7F6FB` / `#F2EEFF` | Secciones alternas y chips de íconos |

Tipografías: Plus Jakarta Sans (titulares, botones, etiquetas y logotipo), Inter (texto e interfaz) y Playfair Display en cursiva (palabra destacada de los titulares). Íconos: Lucide (licencia ISC).

## 🚀 Deploy en GitHub Pages

1. Sube todos los archivos a la raíz del repositorio (branch `main`)
2. **Settings → Pages → Branch: main → / (root)**
3. Con el archivo `CNAME` ya incluido, GitHub Pages conectará `kondorflow.com` automáticamente
4. Configura en tu DNS: registro `A` apuntando a las IPs de GitHub Pages, o `CNAME` a `tuusuario.github.io`

## 💳 Mercado Pago — URL de redirección

En el campo "¿A dónde quieres redirigir a tu cliente?" → **Pago aprobado**:
```
https://kondorflow.com/pago-exitoso.html
```

## 🔧 Personalización rápida

| Qué cambiar | Dónde buscar en index.html |
|---|---|
| Número de WhatsApp (todos los botones van a Uruguay) | Buscar `59892327235` |
| Email principal | Buscar `info@kondorflow.com` |
| Google Analytics | Buscar `G-J55EJNXZVR` |
| Redes sociales | Footer → comentario "Redes sociales" (añadir solo enlaces reales) |
| Logos de clientes | Reemplazar archivos `.webp` |
| Preguntas frecuentes | Cambiar la pregunta visible **y** la misma pregunta en el schema `FAQPage` |

## ✅ Checklist

- [ ] Reemplazar logos de clientes `.webp` con logos reales
- [ ] Añadir URLs reales de redes sociales en el footer
- [ ] Publicar una política de privacidad (el formulario recoge datos personales)
- [ ] Crear o completar el Perfil de Empresa de Google (Google Business Profile)
- [ ] Enviar `sitemap.xml` en Google Search Console
- [ ] En Mercado Pago configurar URL: `https://kondorflow.com/pago-exitoso.html`

## 📞 Contacto

- Teléfono y WhatsApp Uruguay: +598 92 327 235
- Teléfono Perú: +51 943 489 132
- Email: info@kondorflow.com
- Soporte: support@kondorflow.com
- Ventas: sales@kondorflow.com

---
*Kondorflow © 2026 — HG Next Gen Solutions*
