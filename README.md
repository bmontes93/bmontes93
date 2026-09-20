<p align="center">
  <img src="https://raw.githubusercontent.com/bmontes93/bmontes93/main/banner.png" width="100%" alt="Bryan Montes — Senior Full Stack & Systems Engineer" />
</p>

<h1 align="center">Bryan Montes · Thekerdruid</h1>

<p align="center">
  <strong>Senior Full Stack & Systems Engineer &nbsp;|&nbsp; IA Aplicada, Visión Artificial & Arquitecturas de Alto Rendimiento</strong>
</p>

<p align="center">
  <a href="https://bmontesdev.me" target="_blank">
    <img src="https://img.shields.io/badge/Portafolio-000000?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portafolio"/>
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
</p>

---

## Perfil Profesional

Ingeniero de software especializado en el diseño e implementación de **sistemas de alto rendimiento, modelos de visión por computador y arquitecturas backend distribuidas**. Mi trabajo se enfoca en resolver problemas de ingeniería complejos con tres directrices técnicas:

* **Arquitectura y Modularidad:** Separación rigurosa de responsabilidades mediante patrones desacoplados, diseño orientado a dominios y APIs de baja latencia.
* **Rendimiento y Optimización:** Inferencia acelerada por hardware (FP16 / CUDA), procesamiento asíncrono y optimización de recursos a nivel de infraestructura.
* **Calidad y Resiliencia:** Tipado estático estricto, suites de pruebas automatizadas y despliegues reproducibles con Docker y pipelines de CI/CD.

---

## Proyectos Principales (Showcase)

### [EXON-FACE](https://github.com/bmontes93/EXON-FACE) — Sistema de Visión Artificial y Procesamiento Facial
> **Python · ONNX Runtime · NVIDIA CUDA (FP16) · OpenCV · InsightFace · BiSeNet · Docker**

Motor de análisis, segmentación y transposición facial de alta fidelidad diseñado para flujos de procesamiento en imagen y vídeo de nivel cinematográfico.

* **Pipeline de Inferencia:** Segmentación facial a nivel de píxel mediante BiSeNet para generación de máscaras anatómicas precisas (ojos, labios y contornos). Integración con CodeFormer y GFPGAN para restauración de rostros de baja resolución.
* **Aceleración por Hardware:** Motor de ejecución sobre ONNX Runtime optimizado para núcleos NVIDIA CUDA bajo precisión media (FP16), reduciendo drásticamente los tiempos de inferencia por fotograma.
* **Despliegue y Automatización:** Contenedorización completa en Docker, scripts de inicialización automatizados, interfaz gráfica interactiva con Gradio y modo CLI para procesamiento por lotes.

---

### Motor Predictivo ML & Value-Betting Deportivo `[🔒 Repositorio Privado / Sistema Propietario]`
> **Python · XGBoost · LightGBM · Celery · Redis · PostgreSQL · Playwright · Pandas**

Pipeline analítico continuo para la ingesta de datos en tiempo real, modelado probabilístico de eventos de fútbol internacional y detección de ineficiencias de mercado (*Value Betting*).

* **Orquestación Temporal Estricta:** Pipeline distribuido accionado por ventanas temporales relativas al inicio del evento: análisis de bajas en T-24h, captura de cuotas base en T-12h, extracción reactiva de alineaciones oficiales en T-60min (Sofascore) e inferencia probabilística en T-55min.
* **Modelado Probabilístico:** Algoritmos supervisados (XGBoost y LightGBM) entrenados con ingeniería de variables históricas para calcular la probabilidad real ($P_{bot}$) sobre mercados de alta liquidez.
* **Detección de Ventaja Estadística:** Algoritmo cuantitativo con margen de seguridad (`(1 / P_bot) * (1 + alpha) < Cuota_Bookie` con $\alpha = 0.05$), emitiendo alertas operativas únicamente cuando existe un valor esperado positivo (*Edge*).

---

### [quantslot-sdk](https://github.com/bmontes93/quantslot-sdk) — Motor Matemático y Simulación Estocástica para iGaming
> **Node.js · TypeScript · Simulaciones Monte Carlo · CSPRNG Criptográfico**

Motor matemático de simulación probabilística y certificación de slots digitales conforme a las directrices técnicas exigidas por laboratorios internacionales (GLI, iTech Labs).

* **Simulador Monte Carlo:** Capacidad para ejecutar millones de iteraciones y giros en segundos, certificando empíricamente curvas de volatilidad, distribución de frecuencias (*hit frequency*) y RTP teórico.
* **Mecánicas de Juego Complejas:** Soporte para estructuras dinámicas Cluster-Pay (5x5), sistemas de cascadas continuas, multiplicadores acumulativos y rondas de bonificación multinivel.
* **Aleatoriedad Certificable:** Generador de números aleatorios criptográficamente seguro (CSPRNG) para garantizar uniformidad e independencia estadística rigurosa.

---

### [TAHUAGYM](https://github.com/bmontes93/TAHUAGYM) — Plataforma Web de Alto Rendimiento con Renderizado 3D
> **Next.js · TypeScript · Three.js · React Three Fiber · TailwindCSS · Framer Motion · GSAP**

Plataforma web comercial orientada a una experiencia visual cinematográfica y ultra-fluida, alcanzando un índice de rendimiento de **Lighthouse 95+**.

* **Arquitectura Web Avanzada:** Renderizado híbrido SSR/SSG con Next.js App Router (React Server Components), arquitectura de diseño atómico y carga diferida (*lazy loading*) de recursos pesados.
* **Visualizador 3D en Tiempo Real:** Renderizado interactivo de productos mediante Three.js y React Three Fiber con geometrías y shaders optimizados para mantener 60 FPS estables.
* **Accesibilidad y SEO Técnico:** Cumplimiento de directrices WCAG AA, navegación completa por teclado, estructura semántica e integración de datos estructurados JSON-LD.

---

<details>
<summary><b>Ver más proyectos de arquitectura y software especializado</b></summary>

<br/>

#### Ecosistema SaaS de Automatización & Pagos para Telegram `[🔒 Solución Empresarial Privada]`
> **Python · aiogram 3 · FastAPI · PostgreSQL · SQLAlchemy 2.0 · Redis · APScheduler · Docker**

Arquitectura distribuida para control de accesos, verificación de pagos y retención de usuarios en canales privados mediante tres servicios especializados:
* **Verificación:** Validación de comprobantes bancarios mediante máquinas de estado finito (FSM), delegación a paneles administrativos y emisión de enlaces de invitación temporales de un solo uso.
* **Retención:** Agente programado en segundo plano con APScheduler para avisos preventivos de expiración y revocación automática de membresías inactivas.
* **Marketing:** Consola de difusión programada para campañas segmentadas según el estado de la suscripción.

---

#### [ALL-DAY](https://github.com/bmontes93/ALL-DAY) — Plataforma SaaS para Gestión de Eventos
> **Next.js 15 · React 19 · TypeScript · PostgreSQL · Prisma ORM · Culqi · Resend · Pusher**

Plataforma integral para reservas de eventos y conexión de proveedores:
* **Seguridad:** Flujo de validación de identidad de prestadores de servicios y mensajería interna con privacidad protegida.
* **Transaccionalidad:** Sistema de reservas con pagos divididos (anticipo del 50%) integrado con la pasarela de pagos Culqi.
* **Tiempo Real:** Notificaciones Push nativas vía Service Workers y avisos in-app mediante Pusher.

---

#### [CALC101NG](https://github.com/bmontes93/CALC101NG) — Motor de Cálculo Simbólico y Gráficas Dinámicas
> **React · TypeScript · Vite · MathLive · Function-Plot · Python · FastAPI · SymPy · Docker**

Plataforma matemática de análisis analítico:
* Backend asíncrono con FastAPI y SymPy para cálculo y simplificación algebraica (derivadas, integrales y sistemas) en milisegundos.
* Editor visual WYSIWYG mediante MathLive y graficación interactiva en 2D con Function-Plot.

---

#### [GEST E-Commerce](https://github.com/bmontes93/GEST-E-COMERCE) — Arquitectura E-Commerce Desacoplada
> **TypeScript · React · Vite · Python · FastAPI · Docker Compose · JWT**

Infraestructura de tienda virtual desacoplada con separación completa entre capa de presentación y servicios de backend:
* Microservicios contenerizados de despliegue independiente mediante Docker Compose.
* Sistema de autenticación con tokens JWT y panel administrativo de control de inventario y órdenes.

---

#### [Hide-Clone-USB](https://github.com/bmontes93/Hide-Clone-USB) — Servicio de Sincronización Orientado a Eventos
> **PowerShell · Robocopy (32 Threads) · Windows Task Scheduler**

Servicio silencioso en segundo plano para respaldo automatizado de dispositivos de almacenamiento externo:
* Desencadenamiento reactivo mediante eventos de sistema (`DriverFrameworks`), eliminando el consumo de CPU por sondeo constante (*polling*).
* Copia masiva multihilo a 32 subprocesos concurrentes con permisos elevados del sistema operativo.

</details>

---

## Stack Tecnológico

### Inteligencia Artificial & Visión por Computador
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/NVIDIA_CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA"/>
  <img src="https://img.shields.io/badge/ONNX_Runtime-007EC6?style=for-the-badge&logo=onnx&logoColor=white" alt="ONNX Runtime"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn"/>
</p>

### Frontend & Arquitectura Web
<p align="left">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" alt="Three.js"/>
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite"/>
</p>

### Backend, Bases de Datos & Caché
<p align="left">
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma"/>
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy"/>
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
</p>

### Testing, DevOps & Infraestructura
<p align="left">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/PyTest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="PyTest"/>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright"/>
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" alt="Celery"/>
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell"/>
</p>

---

## Métricas de Actividad

<p align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=bmontes93&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=1f6feb&count_private=true&include_all_commits=true&hide_rank=true&cache_seconds=1800&v=1.3" height="165" alt="Estadísticas de GitHub"/>
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=bmontes93&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&count_private=true&cache_seconds=1800&v=1.3" height="165" alt="Lenguajes Principales"/>
</p>

---

<p align="center">
  <i>"Transformando requerimientos de alta complejidad en arquitecturas de software robustas, eficientes y escalables."</i><br/>
  <b>Bryan Montes · Thekerdruid</b>
</p>
