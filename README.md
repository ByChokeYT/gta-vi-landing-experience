# 🌴 gta-vi-landing-experience

Una landing page interactiva y de alto rendimiento que actúa como tributo a **Grand Theft Auto VI**, desarrollada usando **Astro 5**, **Tailwind CSS v4** y **GSAP (ScrollTrigger)**. El sitio traslada la vibrante atmósfera costera y de luces de neón del estado de Leonida y Vice City directamente al navegador.

Este proyecto destaca por su arquitectura limpia y modular, animaciones fluidas al hacer scroll y elementos altamente interactivos para el usuario.

---

## 💡 Origen del Proyecto e Inspiración

El concepto inicial del efecto de máscara de scroll de este proyecto y su diseño base están inspirados en el videotutorial del creador y desarrollador de software **midudev**:
🎥 **[Cómo recrear la web de GTA 6 - Tutorial de midudev](https://www.youtube.com/watch?v=YAgkFlyw_i0)**

A partir de este concepto original enfocado en la máscara de zoom cinemática, expandimos y profesionalizamos la plataforma añadiendo múltiples secciones interactivas, modularizando la arquitectura en componentes aislados y puliendo la estética visual a nivel de una producción comercial.

---

## 🤖 Modelo de Desarrollo y Colaboración de IA

Este proyecto ha sido desarrollado e implementado en colaboración con **Antigravity**, un agente de Inteligencia Artificial enfocado en desarrollo de software avanzado creado por el equipo de **Google DeepMind**. 

El modelo de desarrollo estructurado con el agente de IA permitió:
*   **Modularización Limpia:** Descomponer un archivo monolítico de inicio en un ecosistema de componentes independientes de Astro.
*   **Optimización de Código:** Limpiar el copy quitando elementos informales (emojis básicos de texto) y sustituyéndolos por animaciones avanzadas de SVG y estilos dinámicos.
*   **Refactorización Segura:** Asegurar la consistencia visual del ScrollTrigger de GSAP previniendo desalineaciones críticas de la máscara CSS.

---

## 🛠️ Tecnologías y Arquitectura

### Stack Tecnológico
*   **[Astro 5](https://astro.build/)** — El framework preferido para sitios web enfocados en contenido rápido. Genera HTML estático ultraligero con hidratación mínima de JavaScript.
*   **[Tailwind CSS v4 (Vite Plugin)](https://tailwindcss.com/)** — Utilizado para una maquetación responsiva moderna, control de colores HSL fluidos, temas neón y transiciones optimizadas por GPU.
*   **[GSAP & ScrollTrigger](https://gsap.com/)** — Para modelar la línea de tiempo cinemática y la animación de cascada (stagger) de los componentes al hacer scroll.
*   **[TypeScript](https://www.typescriptlang.org/)** — Controla la lógica interactiva del reproductor de música y las simulaciones de la red social de forma robusta.

### Modos de Construcción y Renderizado
*   **Modo de Renderizado Estático (Static Build):** El proyecto está configurado para compilarse en modo puramente estático (`output: "static"`). Esto significa que se genera en un conjunto de archivos HTML, CSS y JS optimizados, ideales para ser alojados de forma gratuita y con máxima velocidad en plataformas como **GitHub Pages**, Vercel, Netlify o Cloudflare Pages.
*   **Modelo de Componentes Astro:** Estructura modular dividida en componentes reutilizables (`.astro`) que separan la lógica de estilos e interactividad del script principal de la página.

---

## ✨ Características Principales

*   **🎬 Intro de Máscara Cinemática (GSAP):** Una transición fluida en la que el logotipo de GTA VI se amplía mediante scroll hasta revelar el contenido de la web sin saltos visuales.
*   **📻 Vice City Cassette Radio:** Reproductor vintage interactivo con selección de estaciones reales (Synthwave, Funk, Rock), control de volumen por deslizador y ecualizador animado que responde al estado del audio.
*   **📱 Leonida Social Club:** Simulación de una red social móvil (tipo TikTok/Reels) que incluye una animación interactiva donde flotan eclosiones de corazones SVG neón con efecto de desenfoque al hacer clic.
*   **👥 Fichas de Lucía & Jason:** Perfiles detallados de los protagonistas del videojuego con sombras dinámicas en hover y animaciones staggered.
*   **🖼️ Galería Lightbox:** Mosaico fluido de capturas oficiales con ventana modal integrada y cierre optimizado al dar clic fuera de los límites.
*   **⏱️ Contador de Lanzamiento:** Cronómetro de cuenta atrás en tiempo real optimizado mediante JavaScript.

---

## 🚀 Instalación y Uso Local

Para ejecutar este proyecto localmente en tu máquina, sigue estos pasos:

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/ByChokeYT/gta-vi-landing-experience.git
   ```

2. **Accede a la carpeta del proyecto:**
   ```bash
   cd gta-vi-landing-experience
   ```

3. **Instala las dependencias necesarias:**
   ```bash
   npm install
   ```

4. **Inicia el servidor local de desarrollo:**
   ```bash
   npm run dev
   ```
   Abre [http://localhost:4321](http://localhost:4321) en tu navegador para ver la experiencia.

5. **Compila para producción (Genera la carpeta `/dist` estática):**
   ```bash
   npm run build
   ```

---

## 📜 Créditos y Derechos de Autor

Este proyecto ha sido desarrollado únicamente para fines educativos, de portfolio y aprendizaje técnico. Todos los materiales de audio, imágenes de marca, nombres y logotipos mostrados pertenecen a **Rockstar Games** y **Take-Two Interactive**.
