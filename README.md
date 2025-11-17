Game Desk – Catálogo de Ofertas de Videojuegos

![Pantalla principal](img/pantalla_principal.png)  
![Detalle de oferta](img/detalle_oferta.png)


Game Desk es un proyecto desarrollado con **React + TypeScript + Vite** que muestra un catálogo de videojuegos en oferta. Su objetivo es presentar información clara y visual sobre descuentos, precios, formato (“físico” o “digital”) e imágenes de productos.

Se desarrolló como parte de un proyecto académico utilizando tecnologías web modernas y herramientas necesarias para documentar un portafolio profesional en GitHub.

🚀 Objetivo del Proyecto

- Mostrar ofertas reales o simuladas de videojuegos en una aplicación web moderna.  
- Practicar desarrollo con **React**, componentes, estados y renderizado dinámico.  
- Utilizar herramientas del ecosistema moderno: React, TypeScript, Vite, Firebase (opcional).  
- Crear un repositorio profesional con documentación clara.

🧩 Tecnologías Utilizadas

### 🔹 Frontend  
- React  
- TypeScript  
- Vite  
- CSS3 / estilos personalizados  
- HTML (solo como punto de entrada vía index.html)

### 🔹 Backend / Procesamiento  
- Scripts en la carpeta `backend/`  
- Procesamiento y limpieza de datos  
- Firebase Realtime Database (según implementación)

🔹 Otros  
- GitHub Pages / Firebase Hosting  
- Markdown para documentación  
- Archivos `.md` del equipo

---

## 📁 Estructura del Proyecto  
La siguiente estructura corresponde al contenido real de este repositorio:
```
game_desk/
│
├── .firebaserc
├── .gitignore
├── CHANGELOG_GAME_DESK.md
├── GUIA_VISUAL.md
├── IMPLEMENTACION_COMPLETADA.md
├── RESUMEN_FINAL.md
│
├── eslint.config.js
├── firebase.json
│
├── index.html # Punto de entrada básico para React
│
├── src/ # CÓDIGO PRINCIPAL (React)
│ ├── components/ # Componentes reutilizables
│ ├── pages/ # Páginas del proyecto
│ ├── assets/ # Imágenes / recursos
│ └── main.tsx # Entrada de React
│
├── backend/ # Scripts de scraping (según versión)
│
├── package.json # Dependencias (React, React-DOM, Vite, etc.)
├── package-lock.json
│
├── tsconfig.json
├── tsconfig.app.json
├── tsconfig.node.json
│
└── vite.config.ts # Configuración de Vite
```

🖥️ ¿Qué hace el proyecto?

- Muestra un catálogo de videojuegos con componentes de React.  
- Incluye imágenes, precios, descuentos y formato físico/digital.  
- Permite crecer con filtros, búsqueda o conexión a backend.  
- Usa React para renderizar los elementos dinámicamente.

---

## 🧾 PreRequisitos

- Node.js (versión 18+ recomendada)  
- NPM (incluido con Node.js)  
- Cuenta de Firebase (opcional, si se va a desplegar)

---

## 🔧 Instalación y Ejecución

### 1. Clonar el repositorio
```
git clone https://github.com/jimena-mejia/game_desk.git
cd game_desk
```

### 2. Instalar dependencias
```npm install```

### 3. Ejecutar en modo desarrollo
```npm run dev```

El proyecto abrirá en:  
```
👉 http://localhost:5173
```
---

## 📦 Crear build para producción

Los archivos optimizados se generan en la carpeta:
```
dist/
```
---

## 📡 Despliegue con Firebase (opcional)
```
npm install -g firebase-tools
firebase login
firebase init
firebase deploy
```


Jimena Mejía Víquez
Proyecto académico – Instituto Tecnológico de Costa Rica (TEC)
Año 2025
