# Kondorflow — Sitio Web Oficial

**HG Next Gen Solutions** · Lima, Perú · LATAM  
Landing page institucional en HTML/CSS/JS puro — sin frameworks externos.

## 📁 Estructura del repositorio

```
/
├── index.html                  ← Página principal (landing page completa)
├── pago-exitoso.html           ← Página post-pago Mercado Pago
├── 404.html                    ← Página de error personalizada
├── CNAME                       ← Dominio personalizado GitHub Pages
├── sitemap.xml                 ← Mapa del sitio para Google
├── robots.txt                  ← Permisos para buscadores
├── site.webmanifest            ← Config PWA
│
├── kondorlogo1.png             ← Ícono K+cóndor (nav, hero, favicon, footer)
├── kondorlogo2.png             ← Logo horizontal completo (futura sección hero ampliada)
│
└── logos de clientes (reemplazar con logos reales):
    ├── logo-save.webp              260×120px, fondo transparente
    ├── logo-clinica-benavides.webp 260×120px, fondo transparente
    ├── logo-black-diamond.webp     260×120px, fondo transparente
    └── logo-good-way-clean.webp    260×120px, fondo transparente
```

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
| Número de WhatsApp | Buscar `51943489132` |
| Email principal | Buscar `info@kondorflow.com` |
| Google Analytics | Buscar `G-J55EJNXZVR` |
| URLs redes sociales | Footer → botones `.soc` con `href="#"` |
| Logos de clientes | Reemplazar archivos `.webp` |

## ✅ Checklist antes de publicar

- [ ] Subir todos los archivos al repo
- [ ] Activar GitHub Pages (Settings → Pages)
- [ ] Configurar DNS del dominio kondorflow.com
- [ ] Reemplazar logos de clientes `.webp` con logos reales
- [ ] Añadir URLs reales de redes sociales en el footer
- [ ] Verificar dominio en Google Search Console
- [ ] Enviar `sitemap.xml` a Google Search Console
- [ ] En Mercado Pago configurar URL: `https://kondorflow.com/pago-exitoso.html`

## 🗑️ Archivos del repo anterior que ya no se necesitan

El repo anterior tenía solo `index.html`, `kondorlogo1.png`, `kondorlogo2.png` y `CNAME`.  
Todos esos archivos fueron reemplazados o conservados en esta versión final.  
**No hay archivos sobrantes que eliminar** — el repo anterior era limpio.

## 📞 Contacto

- WhatsApp: +51 943 489 132
- Email: info@kondorflow.com
- Soporte: support@kondorflow.com
- Ventas: sales@kondorflow.com

---
*Kondorflow © 2025 — HG Next Gen Solutions*
