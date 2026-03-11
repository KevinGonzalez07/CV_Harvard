# CV Builder — Estilo Harvard

Generador de CV interactivo estilo Harvard para estudiantes y egresados.

## 🚀 Cómo subir a Vercel

### Opción 1: Desde la web (más fácil, sin instalar nada)

1. Crea una cuenta gratis en [vercel.com](https://vercel.com)
2. Ve a [vercel.com/new](https://vercel.com/new)
3. Haz clic en **"Browse"** o arrastra esta carpeta completa
4. Haz clic en **Deploy** — ¡listo!

Tu CV Builder estará en una URL tipo: `https://cv-builder-harvard.vercel.app`

---

### Opción 2: Con Git + GitHub (recomendado para actualizaciones)

1. Sube esta carpeta a un repositorio de GitHub:
   ```bash
   git init
   git add .
   git commit -m "CV Builder inicial"
   git remote add origin https://github.com/TU_USUARIO/cv-builder.git
   git push -u origin main
   ```

2. En [vercel.com](https://vercel.com) → **New Project** → importa tu repo de GitHub

3. Vercel detecta automáticamente que es un sitio estático y lo despliega

---

### Opción 3: Con Vercel CLI

```bash
# Instalar Vercel CLI
npm install -g vercel

# Dentro de esta carpeta:
vercel

# Seguir las instrucciones en pantalla
# En "What's your project name?" escribe: cv-builder-harvard
# En "In which directory is your code located?" presiona Enter
```

---

## 📁 Archivos del proyecto

```
cv-builder-vercel/
├── index.html      ← La aplicación completa (todo en un archivo)
├── vercel.json     ← Configuración de Vercel
├── package.json    ← Metadatos del proyecto
└── README.md       ← Este archivo
```

## ✨ Características

- 🎨 Selector de colores personalizables
- 📷 Foto opcional
- 📋 Secciones: Educación, Experiencia, Proyectos, Habilidades, Certificaciones, Voluntariado, Referencias
- 🖨️ Exportar a PDF directo desde el navegador
- 📊 Barra de progreso de completado
- 📱 Diseño responsivo
