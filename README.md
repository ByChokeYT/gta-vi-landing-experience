# 🌴 Grand Theft Auto VI — Premium Tribute Landing Page

Una landing page interactiva de tributo a **Grand Theft Auto VI**, desarrollada con **Astro**, **Tailwind CSS** y **GSAP (ScrollTrigger)**. El proyecto cuenta con un diseño inmersivo y responsivo que traslada la vibrante atmósfera costera y de luces de neón del estado de Leonida y Vice City directamente al navegador.

👉 **Mira el proyecto en tu entorno local:** `http://localhost:4321/`

---

## ✨ Características Principales

*   **🎬 Intro de Máscara de Scroll Cinemática:** Animación fluida de zoom al hacer scroll sobre el logotipo oficial de GTA VI usando GSAP ScrollTrigger, revelando el contenido principal de forma ininterrumpida.
*   **📻 Vice City Cassette Radio:** Reproductor de cassette clásico totalmente interactivo con control de volumen, sintonización de emisoras reales (Synthwave, Funk/Soul, Heavy Rock) y ecualizador animado.
*   **📱 Leonida Social Club (Parodia de TikTok):** Sección interactiva que emula posts de video virales en vertical. Incluye animación interactiva de reacciones (corazones SVG neon que flotan y se desvanecen) y contador dinámico de likes.
*   **👥 Galería de Protagonistas:** Fichas interactivas para Lucía y Jason con efectos de iluminación personalizados en hover y revelación secuencial (staggered entries).
*   **🖼️ Galería de Capturas Oficiales:** Mosaico de capturas del juego con visualizador lightbox integrado para ampliar imágenes en pantalla completa.
*   **⏱️ Cuenta Atrás de Lanzamiento:** Contador en tiempo real para el estreno en consolas de nueva generación (PlayStation 5 y Xbox Series X|S).
*   **📬 Registro al Social Club:** Formulario de suscripción interactivo con validación de estado.

---

## 🛠️ Tecnologías Utilizadas

*   [Astro](https://astro.build/) — Framework web ultra veloz para sitios enfocados en contenido.
*   [GSAP & ScrollTrigger](https://gsap.com/) — Librería de animación estándar de la industria para transiciones ultra fluidas al hacer scroll.
*   [Tailwind CSS](https://tailwindcss.com/) — Estilos modernos y responsivos basados en utilidades.
*   [TypeScript](https://www.typescriptlang.org/) — Tipado estático y robusto para las interacciones del reproductor y efectos de me gusta.

---

## 🚀 Estructura de Carpetas

```text
/
├── public/
│   ├── fonts/           # Fuentes oficiales tipográficas de GTA
│   └── logo-stack.svg   # Vector para la máscara de scroll
├── src/
│   ├── assets/          # Imágenes de fondo, retratos e iconos vectoriales
│   ├── components/      # Componentes modulares y reutilizables en Astro
│   │   ├── Countdown.astro
│   │   ├── Footer.astro
│   │   ├── Gallery.astro
│   │   ├── HeroMask.astro
│   │   ├── Leonida.astro
│   │   ├── Navbar.astro
│   │   ├── Protagonists.astro
│   │   ├── RadioPlayer.astro
│   │   ├── SocialFeed.astro
│   │   └── TrailerModal.astro
│   ├── layouts/
│   │   └── Layout.astro # Plantilla global, fuentes y estilos neón
│   └── pages/
│       └── index.astro  # Página de entrada principal
└── package.json
```

---

## 💻 Instalación y Desarrollo

Sigue estos sencillos pasos para instalar y ejecutar el proyecto en tu entorno local:

1. **Clona este repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repo.git
   ```

2. **Instala las dependencias:**
   ```bash
   npm install
   ```

3. **Inicia el servidor de desarrollo:**
   ```bash
   npm run dev
   ```
   El sitio estará disponible en: [http://localhost:4321/](http://localhost:4321/)

4. **Compila para producción:**
   ```bash
   npm run build
   ```

---

## 📜 Licencia

Este es un proyecto tributo desarrollado con fines exclusivamente académicos y demostrativos. Todas las marcas comerciales, logotipos, música e imágenes pertenecen a **Rockstar Games, Inc.** y **Take-Two Interactive Software**.
