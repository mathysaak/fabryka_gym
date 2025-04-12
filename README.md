# Fabryka Gym

**Práctica:** Desarrollo de un sitio web con HTML5 y CSS3  
**Asignatura:** Programación Web y Servicios  
**Autor:** SARAPURA, MATIAS

---

## 🏋️‍♂️ Descripción General

Fabryka Gym es un sitio web estático diseñado para un gimnasio, con el objetivo de ofrecer una experiencia de usuario clara, accesible y visualmente atractiva.  
El proyecto utiliza HTML5 y CSS3 con una estructura modular para garantizar mantenibilidad y escalabilidad.

---

## 🔗 Enlaces

- **Repositorio:** [github.com/mathysaak/fabryka_gym](https://github.com/mathysaak/fabryka_gym)
- **Sitio Web Desplegado:** [mathysaak.github.io/fabryka_gym](https://mathysaak.github.io/fabryka_gym)
- **Video Demostrativo:** Ver en Google Drive

---

## 📁 Estructura de Carpetas
fabryka_gym/
├── assets/
├── css/
│   ├── base/
│   ├── components/
│   ├── layout/
│   ├── pages/
│   └── styles.css
├── html/
└── README.md
---

## 🎨 Decisiones de Diseño

### 1. Estructura Modular

- **Razón:** Separación de preocupaciones para mejorar mantenibilidad y escalabilidad.
- **Impacto:** Permite entender rápidamente la estructura y modificar secciones específicas sin afectar otras.

### 2. CSS Personalizado

- **Base:** `base.css` define estilos generales y `variables.css` gestiona la coherencia visual.
- **Responsive:** `responsive.css` usa media queries para adaptarse a móviles, tablets y escritorio.
- **Reutilización:** Componentes como `buttons.css` y `hero.css` se usan en múltiples páginas.
- **Centralización:** `styles.css` importa todos los estilos en un solo archivo enlazado en HTML.

### 3. HTML Semántico

- **Uso de etiquetas:** `<header>`, `<main>`, `<footer>`, etc.
- **Impacto:** Mejora la accesibilidad y el SEO.

### 4. Organización de Activos

- **Categorías:** `gif/`, `images/`, `vsg/` para facilitar identificación y mantenimiento de recursos.

### 5. Diseño Visual

- **Colores y temas:** Variables definidas en `variables.css`; posibilidad de tema global en `theme.css`.
- **Componentes:** Estilos personalizados para secciones clave, manteniendo la coherencia con variables globales.

---

## 📌 Nota

Este proyecto es parte de una práctica académica y está enfocado en aplicar buenas prácticas de maquetado web moderno.

