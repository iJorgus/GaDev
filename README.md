# 🌊 GaDev — Ingeniería de Software con acento Gaditano

<p align="center">
  <img src="./public/favicon.ico" width="80" alt="GaDev Logo" />
</p>

> **Agencia boutique de ingeniería de software** para el comercio local de Cádiz. Tecnología de primer nivel, con el trato cercano de siempre.

---

## ✨ Estética & Filosofía

GaDev no es solo código; es artesanía digital. Este proyecto utiliza una estética **Dark Room** combinada con el gradiente **"Cádiz Sunset"** (#0077b6 → #0096c7 → #ee9b00) para crear una experiencia de usuario premium, fluida y profundamente ligada a nuestra identidad local.

### 🛠️ Tech Stack Premium

- **Framework:** [Astro 6.x](https://astro.build/) (Arquitectura de Islas)
- **Estilos:** [Tailwind CSS v4](https://tailwindcss.com/) (Tokens de diseño personalizados)
- **3D & Interactividad:** [Three.js](https://threejs.org/) (Nubes de puntos interactivas)
- **Animaciones:** [GSAP](https://gsap.com/) & [ScrollTrigger](https://gsap.com/scrolltrigger/)
- **Smooth Scroll:** [Lenis](https://lenis.darkroom.engineering/)

---

## 🏗️ Estructura del Proyecto

El código está optimizado y dividido en componentes atómicos para facilitar su mantenimiento y escalabilidad:

```text
/
├── src/
│   ├── components/       # Componentes visuales e interactivos
│   │   ├── Hero.astro    # Sección principal con canvas 3D
│   │   ├── Navbar.astro  # Navegación con scroll-blur
│   │   ├── Stats.astro   # Contadores de impacto
│   │   └── ...           # Bento grids, portafolio y canvas 3D
│   ├── layouts/
│   │   └── Layout.astro  # Shell HTML, SEO y scripts globales
│   ├── styles/
│   │   └── global.css    # Design System & Tailwind v4 Theme
│   └── pages/
│       └── index.astro   # Composición de la Landing Page
├── public/               # Assets estáticos (Modelos, imágenes, favicons)
└── package.json          # Dependencias y scripts
```

---

## 🕹️ Desarrollo

GaDev utiliza las últimas versiones del ecosistema web para asegurar el mejor rendimiento:

1. **Instalar dependencias:**
   ```bash
   npm install
   ```

2. **Servidor de desarrollo (localhost:4321):**
   ```bash
   npm run dev
   ```

3. **Compilación para producción:**
   ```bash
   npm run build
   ```

---

## 📸 Componentes Destacados

- **Catedral Point Cloud:** Representación 3D interactiva de la Catedral de Cádiz en el Hero.
- **Puerta de Tierra Divider:** Divisor panorámico interactivo entre secciones.
- **Bento Services:** Grid de servicios dinámico con efectos de iluminación (Spotlight).
- **Footer Reveal:** Efecto de "revelación" de pie de página estilo Apple Creative.

---

<p align="center">
  Hecho con arte en Cádiz 🇪🇸
</p>
