# Prathayan 🍃

Proyecto final del curso de "Introducción al Desarrollo Frontend" (202510) de ADA ITW.  
Landing page para **Prathayan**, cantante profesional y profesora de canto, con enfoque en liberación vocal, yoga y mantras.

---

## 🌐 Demo

[Ver sitio en vivo →](https://prathayan.netlify.app) 

---

## 📋 Descripción

Sitio web first mobile de una sola página (landing page) desarrollado como trabajo práctico final.  
El objetivo fue presentar los servicios de Prathayan de manera clara, estética y accesible, respetando su identidad visual: colores tierra, tipografías elegantes y un tono cálido e introspectivo.

---

## ✅ Trabajo realizado

- **Header** con navegación fija, top-bar animada y burger menu en mobile
- **Secciones**: Hero · Sobre mí · Galería · Testimonio · Contacto
- **Cita / testimonio** de alumna real
- **Grilla de fotos** responsive (1 col mobile / 2 col tablet / 3 col desktop)
- **Formulario de contacto** con fieldset, listo para Netlify Forms
- **Footer** con links de navegación y contacto (WhatsApp, Instagram, Spotify)
- **Diseño responsivo** mobile-first (mobile / tablet / desktop / large desktop)
- **Links de navegación** funcionales con anclas internas
- **Deploy** en Netlify con URL pública
- **Repositorio** en GitHub con estructura correcta

---

## 🛠️ Tecnologías utilizadas

- HTML5 semántico
- CSS3 (variables, flexbox, grid, media queries, animaciones)
- Google Fonts: [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) + [Jost](https://fonts.google.com/specimen/Jost)
- Font Awesome 6 (íconos)
- Netlify Forms (formulario de contacto)

---

## 📁 Estructura del proyecto

```
prathayan/
├── index.html
├── style.css
├── assets/
│   ├── prathayan-logo.png
│   ├── imagen-hero.webp
│   ├── image-galeria-1.webp
│   ├── image-galeria-2.webp
│   ├── image-galeria-3.webp
│   ├── image-galeria-4.webp
│   ├── image-galeria-5.webp
│   └── image-galeria-6.webp
└── README.md
```

---

## 🖼️ Optimización de imágenes

Todas las imágenes fueron optimizadas con **[Squoosh](https://squoosh.app/)**:
- Formato: **WebP**
- Calidad: **75%**

Esto reduce el peso de las imágenes significativamente sin pérdida visual perceptible, mejorando los tiempos de carga del sitio.

---

## ♿ Accesibilidad

- Todas las imágenes tienen atributo `alt` descriptivo
- Íconos decorativos con `aria-label` donde corresponde
- Contraste de colores adecuado entre texto y fondo
- Meta description incluida para SEO
- Semántica HTML correcta: `header`, `main`, `section`, `footer`, `nav`, `figure`, `figcaption`, `blockquote`, `cite`

---

## 📱 Responsive

| Breakpoint | Dispositivo |
|---|---|
| Mobile (default) | < 768px |
| Tablet | ≥ 768px |
| Desktop | ≥ 1024px |
| Large desktop | ≥ 1280px |

---

## 🚀 Deploy

El sitio está deployado en **Netlify**.  
El formulario de contacto utiliza **Netlify Forms** (atributo `netlify` en el `<form>`), sin necesidad de backend.

---

## ✍️ Autora del proyecto

Desarrollado por **Sofía De Alessandre** como trabajo práctico final del curso de Frontend, Mayo-2026.  
El sitio representa a **Prathayan** — cantante profesional y profesora de canto.