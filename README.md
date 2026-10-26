# Alejandro Pérez Bretón — CV & Portfolio Web

> **Technical Lead & Cloud Architect**
> Especialista en arquitectura backend distribuida, microservicios de misión crítica, ecosistemas cloud (Azure / GCP), DevOps y adopción estratégica de Inteligencia Artificial.

Sitio web en producción: [aperezbreton.com](https://aperezbreton.com)

---

## 🚀 Características y Arquitectura del Sitio

El proyecto es un currículum web interactivo de alto impacto visual y rendimiento extremo, construido bajo los estándares y tendencias de diseño 2025/2026 (inspiración Apple / Linear, Dark Mode, Bento Grid y Glassmorphism):

### 1. Experiencia de Usuario & Reclutadores (Human UX)
- **Descarga de CV en PDF integrada:** Botón 1-click en el navbar y hero que activa la ventana de impresión/exportación con un formato ejecutivo A4 adaptado.
- **Hoja de estilos `@media print` (ATS-Friendly):** Al imprimir o guardar como PDF (`Cmd + P`), el diseño se adapta a un documento ejecutivo de 2 páginas con fondo blanco, tipografía nítida y estructura sin elementos oscuros o decorativos desbordados.
- **Botón "Copiar Email":** Copiado al portapapeles con feedback visual mediante un **toast notification** flotante (`aperezbreton@gmail.com`).
- **Navegación Responsive Móvil:** Barra de navegación con menú desplegable para dispositivos móviles.
- **Identidad visual de la trayectoria:** Logos locales de los empleadores en la línea de tiempo y de empresas/clientes en el carrusel (Imagemaker, Falabella, Globant, BC Tecnología, Emergya, MetLife, IKEA, LATAM, Transbank y TOKU), sin depender de servicios externos para cargarlos.

### 2. Optimización para Motores de Reclutamiento & Bots de IA (Machine/ATS Ready)
- **Schema.org (JSON-LD):** Metadatos estructurados para `Person` y `ProfilePage` (`knowsAbout`, `jobTitle`, `worksFor`, `sameAs`) para indexación precisa en LinkedIn Recruiter, Google for Jobs y sistemas ATS.
- **Open Graph & Twitter Cards:** Tarjetas de previsualización enriquecida al compartir el enlace en LinkedIn, WhatsApp, Slack o Twitter.
- **Favicon Vectorial SVG Nativo:** Embebido vía Data URI con el monograma APB en alta definición.

### 3. Sección "Architecture Spotlight"
- Desglose del caso de éxito técnico: **Migración del Hub de Pagos Digitales (MetLife Chile / Imagemaker)**, detallando arquitectura hexagonal en Spring Boot 3, Azure Kubernetes Service (AKS), Azure APIM, observabilidad con Elasticsearch y pasarelas de pago (Transbank / TOKU).

---

## 🛠️ Stack Técnico del Proyecto

- **HTML5 Semántico & Accesible** (cumplimiento WCAG y navegación por teclado).
- **CSS Moderno:** Variables CSS nativas, glassmorphism (`backdrop-filter`), animaciones fluidas con aceleración por GPU.
- **Tailwind CSS:** Utilidades de layout y espaciado ágil.
- **JavaScript Vanilla (ES6+):** Cero dependencias pesadas; utiliza `IntersectionObserver` y `navigator.clipboard`.

---

## 💻 Cómo desplegar o ejecutar localmente

1. Clona el repositorio:
   ```bash
   git clone https://github.com/AleFogoCapo/aperezbreton-cv.git
   cd aperezbreton-cv
   ```
2. Abre `index.html` en tu navegador o levanta un servidor local:
   ```bash
   # Con Python
   python3 -m http.server 8000
   ```
3. Visita `http://localhost:8000`.
