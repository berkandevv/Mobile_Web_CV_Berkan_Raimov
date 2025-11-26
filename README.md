# 📱 Mobile Web CV

Este proyecto es un **Currículum Web Responsive**, diseñado con enfoque mobile-first y navegación tipo aplicación móvil.  
Incluye experiencia, estudios, idiomas, portafolio de proyectos y formulario de contacto funcional integrado con Netlify Forms.

---

## 🚀 Demo en producción

🔗 **URL en Netlify:** [berkan-cv.netlify.app](https://berkan-cv.netlify.app)

---

## 🧩 Características principales

✅ Diseño mobile-first  
✅ Navegación inferior tipo app  
✅ Header con foto ampliada estilo perfil  
✅ Secciones separadas en páginas HTML  
✅ Portafolio con capturas y tecnologías con iconos  
✅ Stack con Devicon (HTML, CSS, JS, Bootstrap, PHP, Laravel, React, Java, MySQL, Git)  
✅ Formulario funcional con **Netlify Forms**  
✅ Descarga del CV en PDF  
✅ Totalmente estático — sin build, sin frameworks  

---

## 🛠 Tecnologías utilizadas

### 🌐 Frontend
- HTML
- Bootstrap 5
- Bootstrap Icons
- Devicon

### 🔧 Herramientas
- Git
- GitHub
- Netlify

---

## 📂 Estructura del proyecto (ACTUAL)

```
Mobile_Web_CV/
 ├─ html/
 │   ├─ index.html
 │   ├─ experiencia.html
 │   ├─ estudios.html
 │   ├─ idiomas.html
 │   ├─ portafolio.html
 │   ├─ contacto.html
 │   ├─ img/
 │   │   ├─ yo.jpeg
 │   │   ├─ examen.png
 │   │   └─ laravel.jpeg
 │   └─ docs/
 │       └─ CV_BerkanR.pdf
 └─ README.md
```

---

## 🌍 Despliegue en Netlify

### ✅ Configuración correcta

**Publish directory:**
```
html
```

**Branch:**
```
main
```

**Build command:**
```
(ninguno)
```

---

## ✉ Formulario de contacto (Netlify Forms)

El formulario funciona gracias a:

```
<form name="contacto" method="POST" data-netlify="true" netlify>
<input type="hidden" name="form-name" value="contacto">
```

⚠ Importante: el formulario **solo aparece en Netlify Forms después del primer envío desde la web publicada**.

---

## 📱 Secciones del CV

| Página | Contenido |
|--------|-----------|
| `index.html` | Presentación, stack, menú |
| `experiencia.html` | Trayectoria + habilidades transferibles |
| `estudios.html` | Formación actual y previa |
| `idiomas.html` | Competencias lingüísticas |
| `portafolio.html` | Proyectos con capturas e iconos |
| `contacto.html` | Formulario + enlaces directos |

---

## 📦 Cómo usar este repositorio

### ✅ Clonar
```bash
git clone https://github.com/tu-usuario/Mobile_Web_CV.git
```

### ✅ Abrir localmente
Simplemente abre:
```
html/index.html
```

_No requiere instalación ni servidor._

---

## 🧾 Licencia

Este proyecto es de uso personal.  
Puedes inspirarte, pero no reutilizar foto, datos personales ni contenido textual.

---

