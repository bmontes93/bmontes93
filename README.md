<p align="center">
  <img src="https://raw.githubusercontent.com/bmontes93/bmontes93/main/banner.png" width="100%" alt="Bryan Montes — Senior Full Stack Engineer" />
</p>

<h1 align="center">Bryan Montes · Thekerdruid</h1>

<p align="center">
  <strong>Senior Full Stack Engineer &nbsp;|&nbsp; AI & Computer Vision Specialist &nbsp;|&nbsp; E-commerce Architect</strong>
</p>

<p align="center">
  <a href="https://bmontesdev.me" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://www.linkedin.com/in/bmontesdev/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:bmontesr930620@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/bmontes93">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=bmontes93&style=for-the-badge&color=0e75b6" alt="Profile views"/>
</p>

---

##  About Me

I design and build **complex, production-ready systems** — from high-throughput e-commerce platforms to state-of-the-art AI pipelines. My work is defined by three core principles:

- 🏗 **Architectural Clarity** — Clean separation of concerns with scalable, maintainable design patterns.
- ⚡ **Performance First** — Sub-second loads, optimized bundles, SSR/SSG strategies, and FP16 AI inference.
- 🎨 **Premium UX** — Cinematic animations (GSAP, Framer Motion), 3D experiences (Three.js/React Three Fiber), and pixel-perfect interfaces.

---

##  Highlighted Projects

###  [EXON-FACE](https://github.com/bmontes93/EXON-FACE) — High-Performance Computer Vision System
> **Python · ONNX Runtime · OpenCV · InsightFace · BiSeNet · Gradio · Docker**

A state-of-the-art face-swapping engine engineered for **cinema-quality output**, built on top of the InsightFace model suite.

- 🧠 **Precision AI Pipeline** — BiSeNet segmentation for pixel-perfect facial masking (eyes, mouth, skin). CodeFormer + GFPGAN post-processing enhancers for low-resolution face restoration.
- ⚙️ **Hardware-Agnostic Acceleration** — ONNX Runtime with pre-tuned NVIDIA CUDA support and FP16 inference profiles (Cinema / Balanced / Fast).
- 🐳 **Production-Ready** — Dockerized environment, one-click `.bat` installer, CLI + Gradio GUI for both casual and automated usage.

---

###  [botpredictor](https://github.com/bmontes93/botpredictor) — Machine Learning Soccer Prediction Pipeline
> **Python · Playwright · Celery · Redis · PostgreSQL · pandas · NumPy · XGBoost · LightGBM**

Pipeline automatizado de extracción de datos, inferencia probabilística con Machine Learning y alertas de apuestas de valor (*Value Betting*) para fútbol en tiempo real.

- ⚙️ **Arquitectura por Fases** — Ejecución orquestada en base al inicio del evento: T-24 análisis de sentimiento sobre bajas; T-12 captura de cuotas base en bookmakers; T-60 trigger asíncrono para detección de alineaciones oficiales en Sofascore; y T-55 ejecución del modelo de inferencia.
- 🧠 **Modelado ML Avanzado** — Algoritmos predictivos basados en XGBoost y LightGBM entrenados para determinar probabilidades reales ($P_{bot}$) de mercados de córneres, tarjetas y BTTS + Over 2.5.
- 📊 **Cálculo de Valor Implícito** — Aplica una formulación de margen de seguridad (`(1 / P_bot) * (1 + alpha) < Cuota_Bookie` con $\alpha = 0.05$) para recomendar alertas únicamente en mercados con valor real frente a las cuotas del mercado.

---

###  [ALL-DAY](https://github.com/bmontes93/ALL-DAY) — Plataforma SaaS de Gestión de Eventos
> **Next.js 15 · React 19 · TypeScript · TailwindCSS v4 · PostgreSQL · Prisma ORM · NextAuth.js · Pusher · Resend · Culqi**

Plataforma integral de gestión de eventos y conexión con proveedores locales en Huaraz (SaaS). Ofrece pagos seguros, notificaciones y gamificación.

- 🛡️ **Ecosistema Seguro** — Verificación de proveedores (DNI + reconocimiento facial) y sistema de mensajería interna con privacidad anti-stalking.
- 📅 **Gestión de Reservas** — Flujo interactivo con control de disponibilidad en tiempo real, validaciones con Zod y pagos divididos en dos partes (50% de depósito inicial) integrados con Culqi.
- 🔔 **Notificaciones Multicanal** — Alertas Push nativas vía Service Workers, avisos in-app en tiempo real con Sonner y correos electrónicos transaccionales profesionales vía Resend.
- 🏆 **Gamificación y Fidelización** — Progreso por niveles de usuario (Bronce, Plata, Oro, VIP) y acumulación de puntos por eventos completados.

---

###  [bots](https://github.com/bmontes93/bots) — Unified Telegram Bots Ecosystem (SaaS)
> **Python · aiogram 3.0 · FastAPI · PostgreSQL · SQLAlchemy 2.0 · Redis · APScheduler · Docker**

Ecosistema modular SaaS de automatización, verificación de pagos y retención de usuarios para canales privados, conformado por tres bots de Telegram paralelos integrados bajo un backend unificado.

- 🛡️ **Bot de Verificación** — Procesa comprobantes de depósitos/transferencias mediante FSM, delega aprobaciones a grupos de administración con teclados inline y genera enlaces de invitación exclusivos con validación automatizada.
- 🔄 **Bot de Retención** — Agente en segundo plano (APScheduler) que alerta sobre la expiración inminente de suscripciones (T-3 días y T-1 día), gestiona la expulsión de canales de usuarios inactivos y ejecuta flujos de recuperación automáticos.
- 📣 **Bot de Marketing** — Consola de difusión publicitaria programable para el envío masivo de campañas de engagement segmentadas por estados de suscripción.
- 🐳 **Infraestructura de Grado Producción** — Dockerizado completo y desacoplado, orquestando sesiones asíncronas con SQLAlchemy, almacenamiento intermedio (FSM) sobre Redis y base de datos relacional PostgreSQL.

---

###  [Sheinclon](https://github.com/bmontes93/Sheinclon) — Full-Stack E-commerce Platform
> **TypeScript · Node.js · TypeORM · SQLite · React · Vite**

A high-fidelity Shein clone built for **performance and scalability**. Migrated from MongoDB to a relational SQL architecture with TypeORM for a more robust data model. Features include:

- 🎬 **Cinematics UI** — Blur-up image loading, animated product cards (hover zoom + alternate angle reveal), and editorial-style layouts.
- 🛒 **Full E-commerce Engine** — Dynamic catalog with real-time filtering, persistent shopping cart, wishlist, variant management (size/color), discount coupon system, and a user review module.
- 🔒 **TypeScript Full-Stack** — Strict static typing across frontend and backend for maximum safety and maintainability.

---

###  [TAHUAGYM](https://github.com/bmontes93/TAHUAGYM) — Premium Fitness Management Platform
> **Next.js 16 · TypeScript · TailwindCSS · Three.js · React Three Fiber · Framer Motion · GSAP**

A visually stunning web platform for a premium training center in Huaraz, Perú. Achieved **Lighthouse 95+ Performance Score**.

- 🌐 **Advanced Architecture** — Hybrid SSR/SSG rendering with Next.js App Router (Server Components by default), Atomic Design system, and dynamic lazy loading.
- 🎮 **3D Product Visualizer** — Interactive Three.js/React Three Fiber showcase for merchandise (Tahua Labs).
- 🔍 **SEO & Accessibility** — Full Open Graph, Schema.org JSON-LD structured data, WCAG AA compliance, keyboard navigation, and automated sitemap generation.

---

###  [CALC101NG](https://github.com/bmontes93/CALC101NG) — Plataforma Matemática Simbólica
> **React 19 · TypeScript · Vite · MathLive · Function-Plot · Python · FastAPI · SymPy · Docker**

Plataforma matemática inteligente de nueva generación. Resuelve derivadas, integrales, ecuaciones y sistemas con pasos detallados y gráficas interactivas.

- 🧮 **Editor WYSIWYG Nativo** — Teclado matemático virtual con MathLive para escribir fórmulas (integrales, fracciones, matrices) de forma natural y matemática.
- 📈 **Gráficas Dinámicas** — Visualización automática 2D interactiva de ecuaciones, inecuaciones y regiones sombreadas mediante Function-Plot.
- ⚡ **Motor Asíncrono de Alta Velocidad** — API construida sobre FastAPI y SymPy para el cálculo y simplificación matemática simbólica en milisegundos.
- 🎨 **Diseño Premium Glassmorphism** — Interfaz inmersiva con modo oscuro nativo y micro-interacciones interactivas fluidas usando Framer Motion.

---

###  [GEST E-Commerce](https://github.com/bmontes93/GEST-E-COMERCE) — Microservices E-commerce Solution
> **TypeScript · React · Vite · Python · FastAPI · Docker · Docker Compose · JWT**

A robust, decoupled commerce infrastructure designed with **enterprise-grade separation of concerns**.

- 🏗 **Microservices Architecture** — Fully containerized with Docker Compose; React/Vite frontend calls a Python FastAPI backend, each independently deployable.
- 🔐 **Secure Auth System** — JWT-based authentication with role management and a full administrative dashboard.
- 🚀 **DevOps Ready** — `render.yaml` for zero-config cloud deployment, `docker-compose up --build` for identical dev/prod environments.

---

###  [quantslot-sdk](https://github.com/bmontes93/quantslot-sdk) — QuantSlot Math Engine & RTP API
> **Node.js · Express · Monte Carlo Simulations · Cryptographic RNG (CSPRNG)**

Motor matemático y backend de simulación estocástica de alto rendimiento para la industria de iGaming (tragamonedas / slots) diseñado bajo estándares de certificación internacional.

- 🎲 **Simulador Monte Carlo** — Capacidad para ejecutar millones de giros en segundos para validar métricas clave de juego, frecuencia de aciertos (hit frequency) y porcentaje de RTP.
- ⚙️ **Mecánicas Complejas** — Soporte nativo para Cluster-Pay (cuadrículas 5x5), cascadas infinitas, multiplicadores y bonificaciones multinivel.
- 🔒 **Seguridad CSPRNG** — Generación de números aleatorios criptográficamente seguros para garantizar la aleatoriedad matemática exigida por certificadoras (GLI, iTech Labs).

---

###  [Hide-Clone-USB](https://github.com/bmontes93/Hide-Clone-USB) — USB Auto-Sync Service
> **PowerShell · Robocopy · Windows Task Scheduler · Event-Driven Architecture**

Servicio silencioso y de alto rendimiento para la sincronización y respaldo automatizado de dispositivos de almacenamiento USB en Windows.

- ⚡ **Arquitectura Orientada a Eventos** — Activación instantánea mediante triggers de eventos del sistema (DriverFrameworks Event ID 2003/2101), eliminando el consumo de CPU por polling en reposo.
- 🚀 **Copia Multihilo** — Transferencias de archivos masivas ultra-rápidas mediante Robocopy optimizado a 32 hilos (`/MT:32`) y modo de respaldo (`/B`) para archivos protegidos.
- 👤 **Ejecución Invisible** — Corre como servicio en el contexto de `NT AUTHORITY\SYSTEM` de manera totalmente oculta y sin interfaces de consola molestas para el usuario.

---

###  [CHAMBEAFACIL](https://github.com/bmontes93/CHAMBEAFACIL) — Job Market Platform
> **JavaScript · Full-Stack**

A scalable digital marketplace connecting employers and workers, focused on the Peruvian market.

---

###  [Cientific-Calc](https://github.com/bmontes93/Cientific-Calc) — Scientific Calculator
> **JavaScript**

Browser-based scientific calculator providing advanced mathematical operations within a polished, modern, and mobile-responsive web interface.

---

##  Technology Stack

### 🧠 Artificial Intelligence & Computer Vision
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/ONNX_Runtime-007EC6?style=for-the-badge&logo=onnx&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
</p>

### 🌐 Frontend Development
<p align="left">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
</p>

### ⚙️ Backend, Databases & Cache
<p align="left">
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
</p>

### 🛠️ DevOps, Task Queues & Utilities
<p align="left">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white"/>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white"/>
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white"/>
</p>

---

##  GitHub Metrics

<p align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=bmontes93&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=1f6feb&count_private=true&include_all_commits=true&hide_rank=true&cache_seconds=1800&v=1.1" height="165" alt="GitHub Stats"/>
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=bmontes93&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&count_private=true&cache_seconds=1800&v=1.1" height="165" alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=bmontes93&theme=tokyonight&hide_border=true&background=0d1117&stroke=58a6ff&ring=1f6feb&fire=ff9300&currStreakLabel=58a6ff&count_private=true&v=1.1" alt="GitHub Streak"/>
</p>

---

<p align="center">
  <i>"Transforming complex requirements into elegant, high-performance engineering."</i><br/>
  <b>— Thekerdruid  ·  bmontes93</b>
</p>
