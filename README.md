# 🐛 Bugs Dev - Landing Page Corporativa

> Sitio web institucional para agencia de desarrollo de software especializada en soluciones Agrotech y aplicaciones a medida.

![Bugs Dev Preview](public/images/readme-banner.png)

## 📋 Sobre el Proyecto

Este repositorio contiene el código fuente del sitio web oficial de **Bugs Dev**. El objetivo fue desarrollar una landing page de alto rendimiento, con una identidad visual fuerte ("Dark Mode" nativo) y una experiencia de usuario fluida.

El sitio actúa como punto de contacto central para clientes y showcase de nuestros proyectos destacados, incluyendo aplicaciones de escritorio para ingeniería agronómica y plataformas educativas.

## 🚀 Tecnologías (Stack Tecnológico)

El proyecto fue construido priorizando la velocidad de carga (Performance), SEO y la mantenibilidad del código.

* **Core:** [Astro](https://astro.build/) (v5) - Para generación de sitios estáticos y "Zero JS by default".
* **Estilos:** [Tailwind CSS](https://tailwindcss.com/) (v4) - Diseño responsivo y sistema de diseño personalizado.
* **Lenguaje:** [TypeScript](https://www.typescriptlang.org/) - Para lógica robusta y tipado estático en componentes.
* **Interactividad:** Vanilla JS (Scripts optimizados dentro de islas de Astro).
* **Formularios:** Integración con [Formspree](https://formspree.io/) vía AJAX + Notificaciones Toast personalizadas.

## ✨ Características Clave

* **⚡ Performance:** Puntuación 100/100 en Lighthouse.
* **📱 Contacto Directo:** Botón flotante de **WhatsApp** integrado y Formulario de contacto con notificaciones AJAX en tiempo real.
* **🎨 Diseño UI/UX:**
    * Paleta de colores personalizada: *Space Indigo* (Base), *Classic Crimson* (Acción) y *Lime Cream* (Highlights).
    * Diseño "Mobile First" totalmente responsivo.
    * Menú de navegación "Sticky" con efecto glassmorphism y versión móvil animada.
* **🖼️ Portfolio Interactivo:** Sistema de Modales (Dialog API) que soporta galerías mixtas (Video + Imágenes) y scroll infinito.

## 👩‍💻 Mi Rol en el Proyecto

**Frontend Lead & Arquitectura**

Como encargada del desarrollo Frontend, mis responsabilidades incluyeron:

1.  **Arquitectura de Componentes:** Creación de componentes reutilizables (`Navbar`, `Cards`, `Modals`) para asegurar escalabilidad.
2.  **Integración de Diseño:** Traducción de la identidad visual a variables de CSS y configuración de Tailwind v4.
3.  **Lógica Interactiva:** Implementación de TypeScript para el manejo del DOM, validación de formularios y lógica de los modales.
4.  **Optimización de Assets:** Gestión de carga de imágenes y videos para mantener el rendimiento.

## 🛠️ Instalación y Despliegue

Si deseas correr este proyecto localmente:

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/Apine15/bugs-dev-web.git](https://github.com/Apine15/bugs-dev-web.git)
    ```
2.  **Instalar dependencias:**
    ```bash
    npm install
    ```
3.  **Iniciar servidor de desarrollo:**
    ```bash
    npm run dev
    ```
    *El sitio estará disponible en `http://localhost:4321`*

4.  **Construir para producción:**
    ```bash
    npm run build
    ```
    *Esto generará la carpeta `dist/` con los archivos estáticos listos para desplegar.*

## 📂 Estructura del Proyecto

```text
/
├── public/          # Assets estáticos (Imágenes, Videos, Favicon)
├── src/
│   ├── components/  # Piezas UI (Navbar, Contact, Portfolio...)
│   ├── layouts/     # Plantillas base (HTML, Head, SEO)
│   ├── pages/       # Rutas del sitio (index.astro)
│   └── styles/      # Configuración de Tailwind y CSS Global
└── astro.config.mjs # Configuración del compilador


## 📞 Contacto

**Andrea Pineda** - Frontend Lead & Agritech Specialist  
[LinkedIn] https://www.linkedin.com/in/andreapinedalink/ | [Portfolio Personal]https://apine15.github.io/portfolio-personal/

---
*Desarrollado con 🐛 y ❤️ por el equipo de Bugs Dev.*