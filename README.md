# 🎾 Padel Tracker — Guía de instalación

## Estructura del proyecto
```
padel-tracker/
├── index.html
├── package.json
├── vite.config.js
├── src/
│   ├── main.jsx
│   └── App.jsx        ← acá va todo el código de la app
└── public/
    ├── icon-192.png
    └── icon-512.png
```

---

## Paso 1 — Subir a GitHub

1. Entrá a **github.com** → Sign up (gratis)
2. Click en **"New repository"**
3. Nombre: `padel-tracker` → **Create repository**
4. Subí los archivos arrastrándolos al repo (o usá GitHub Desktop)

---

## Paso 2 — Deployar en Netlify

1. Entrá a **netlify.com** → Sign up con tu cuenta de GitHub
2. Click en **"Add new site" → "Import an existing project"**
3. Elegí **GitHub** → seleccioná el repo `padel-tracker`
4. Configuración de build:
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`
5. Click **"Deploy site"**

En 2-3 minutos tenés tu URL, por ejemplo: `https://padel-tracker-lucho.netlify.app`

---

## Paso 3 — Instalar en el celular como app

### Android (Chrome):
1. Abrí la URL en Chrome
2. Menú (⋮) → **"Agregar a pantalla de inicio"**
3. Confirmás → queda el ícono en tu home 🎾

### iOS (Safari):
1. Abrí la URL en Safari
2. Botón compartir (□↑) → **"Agregar a pantalla de inicio"**
3. Confirmás → queda el ícono en tu home 🎾

---

## Paso 4 — Actualizar la app cuando hagamos mejoras

Cada vez que Claude te dé código nuevo:
1. Copiás el contenido nuevo de `App.jsx`
2. En GitHub, abrís el archivo `src/App.jsx`
3. Click en el lápiz (editar) → pegás el nuevo código → **"Commit changes"**
4. Netlify detecta el cambio automáticamente y actualiza la app en ~1 minuto
5. En el celular, la app se actualiza sola la próxima vez que la abrís

**¡No necesitás reinstalar nada!**

---

## Datos guardados

Los datos se guardan en el **localStorage** del dispositivo — no se pierden al cerrar la app, pero sí si borrás los datos del navegador.

Para hacer backup: en la pantalla de Partidos podés exportar (funcionalidad a agregar).
