<p align="center">
  <img src="https://raw.githubusercontent.com/bmontes93/bmontes93/main/banner.png" width="100%" alt="Bryan Montes — Senior Full Stack & Systems Engineer" />
</p>

<h1 align="center">Bryan Montes · Thekerdruid</h1>

<p align="center">
  <strong>Senior Full Stack & Systems Engineer &nbsp;|&nbsp; IA Aplicada & Visión Artificial &nbsp;|&nbsp; Arquitecturas de Alto Rendimiento</strong>
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
  <a href="https://github.com/bmontes93/bmontes93/actions/workflows/readme-ci.yml">
    <img src="https://github.com/bmontes93/bmontes93/actions/workflows/readme-ci.yml/badge.svg" alt="Quality CI"/>
  </a>
</p>

---

## Sobre Mí & Filosofía de Ingeniería

Soy **Bryan Montes**, desarrollador y arquitecto de software enfocado en la construcción de **sistemas de alta concurrencia, pipelines avanzados de Inteligencia Artificial y arquitecturas web de alto rendimiento**. Mi trabajo combina análisis matemático, optimización a bajo nivel y diseño de infraestructuras desacopladas:

- **Arquitectura Limpia & Modular:** Construcción de sistemas desacoplados, orientados a dominios y basados en microservicios escalables que facilitan la evolución técnica continua sin acumulación de deuda técnica.
- **Rendimiento Extremo:** Optimización rigurosa de latencia: inferencia acelerada con CUDA/FP16, procesamiento asíncrono y tiempos de respuesta sub-segundo con estrategias SSR/SSG.
- **Experiencias Interactivas 3D:** Integración de gráficos en tiempo real mediante WebGL y Three.js, manteniendo estándares de rendimiento Lighthouse 95+.

---

## Dominios de Especialidad

| Área Técnica | Stack & Herramientas Clave | Enfoque de Ingeniería |
| :--- | :--- | :--- |
| **IA & Visión Artificial** | Python · ONNX Runtime · NVIDIA CUDA · OpenCV · InsightFace | Inferencia en tiempo real (FP16), segmentación facial y restauración generativa |
| **Machine Learning & Big Data** | XGBoost · LightGBM · Celery · Redis · PostgreSQL · Playwright | Orquestación distribuida, pipelines reactivos y modelos cuantitativos |
| **Sistemas & iGaming Math** | Node.js · TypeScript · Simulaciones Monte Carlo · CSPRNG | Simulación estocástica masiva (millones de giros/s) y certificación matemática |
| **Frontend Moderno & 3D Web** | Next.js 15 · React 19 · Three.js · React Three Fiber · TailwindCSS | Renderizado 3D a 60 FPS estables, Server Components y accesibilidad AA |

---

## Estándares de Ingeniería & Prácticas de Desarrollo

- **Tipado Estricto de Extremo a Extremo:** TypeScript configurado en modo estricto en frontend/Node.js y Python tipado estáticamente con chequeo continuo para prevención temprana de regresiones.
- **Flujo de Integración y Entrega Continua (CI/CD):** Validación automatizada en cada Pull Request mediante GitHub Actions (análisis estático, linting, tests unitarios y de integración).
- **Infraestructura Inmutable y Reproducible:** Contenerización exhaustiva con Docker y Docker Compose con builds multi-etapa para generar artefactos mínimos, seguros y portables entre entornos.
- **Diseño Resiliente:** Manejo defensivo de excepciones, colas de tareas con reintentos exponenciales y observabilidad mediante logging estructurado.

---

## Patrones de Diseño & Paradigmas de Arquitectura

- **Sistemas Distribuidos & Backend:**
  - *CQRS & Arquitectura Orientada a Eventos:* Segregación de responsabilidades de comando y consulta para maximizar el throughput de lectura y asegurar consistencia transaccional en escritura.
  - *Máquinas de Estado Finito (FSM):* Modelado formal de flujos de verificación bancaria, retención de usuarios y transiciones de estado deterministas en servicios asíncronos y bots.
  - *Inversión de Dependencias:* Desacoplamiento de la infraestructura mediante patrones de Repositorio y Service Layer en FastAPI, Node.js y Next.js.
- **Inferencia de IA & Procesamiento de Datos:**
  - *Worker Pools & Pipelines Asíncronos:* Distribución de carga con Celery y Redis para aislar tareas CPU/GPU-intensivas sin bloquear el bucle de eventos principal.
  - *Model Caching & Quantization:* Optimización de memoria en inferencia mediante modelos ONNX en media precisión (FP16) y precarga de pesos en VRAM para eliminar cold-starts.
- **Frontend de Alto Rendimiento:**
  - *React Server Components (RSC):* Minimización del tamaño del bundle JavaScript del cliente y serialización eficiente de datos directamente desde el servidor.
  - *Atomic Design & Shaders WebGL:* Componentización modular estricta y optimización de shaders GLSL para renderizado 3D a 60 FPS estables.

---

## Seguridad, Hardening & Criptografía

- **Aleatoriedad Criptográfica Certificable (CSPRNG):** Generación de entropía estadística no predecible conforme a normativas internacionales de certificación de software para iGaming (GLI / iTech Labs).
- **Validación Estricta en Fronteras:** Validación en tiempo de compilación y runtime de esquemas de datos mediante Pydantic (Python) y Zod (TypeScript), previniendo inyecciones y datos malformados antes de ingresar a la capa de dominio.
- **Defensa en Profundidad & Control de Acceso:**
  - Hashing criptográfico robusto (Argon2 / bcrypt) para credenciales y autenticación basada en tokens JWT con expiración corta y rotación.
  - Limitación de tasa (*Rate Limiting*) defensiva en memoria sobre Redis para mitigar ataques de fuerza bruta y denegación de servicio (DDoS).

---

## Investigación & Exploración Técnica Activa (I+D)

Líneas de investigación tecnológica y desarrollo experimental continuo:

- **Sistemas de Agentes Autónomos & LLMs Locales:** Cuantización eficiente de modelos de lenguaje (GGUF, AWQ), inferencia de baja latencia con vLLM y orquestación de agentes con memorias vectoriales.
- **Aceleración con Rust & WebAssembly:** Compilación de núcleos matemáticos y de simulación a WASM para ejecutar procesamiento intensivo a velocidad nativa en navegadores.
- **Patrones Event-Driven Distribuidos:** Implementación de Event Sourcing y CQRS para arquitecturas distribuidas de alta concurrencia y consistencia eventual.

---

## Proyectos Destacados

### [EXON-FACE](https://github.com/bmontes93/EXON-FACE) — Sistema de Visión Artificial y Procesamiento Facial
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX_Runtime-007EC6?style=flat-square&logo=onnx&logoColor=white)
![CUDA](https://img.shields.io/badge/NVIDIA_CUDA_FP16-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

Motor de análisis, segmentación y transposición facial de alta fidelidad diseñado para flujos de procesamiento en imagen y vídeo de calidad cinematográfica.

```mermaid
flowchart LR
    A[Ingesta de Fotograma] --> B[Segmentación BiSeNet]
    B --> C[Alineación InsightFace]
    C --> D[Inferencia ONNX Runtime CUDA FP16]
    D --> E[Restauración CodeFormer / GFPGAN]
    E --> F[Composición Final de Alta Fidelidad]
```

- **Pipeline de Inferencia:** Segmentación anatómica a nivel de píxel mediante BiSeNet para generación de máscaras faciales exactas (ojos, labios y contornos). Incorpora restauración generativa con CodeFormer y GFPGAN para reconstrucción nítida en baja resolución.
- **Aceleración por Hardware:** Motor sobre ONNX Runtime optimizado para núcleos NVIDIA CUDA en media precisión (FP16), reduciendo drásticamente la latencia por fotograma.
- **Entorno de Producción:** Empaquetado completo en Docker, scripts de inicialización automatizados, CLI para procesamiento en lote e interfaz gráfica interactiva en Gradio.
- **Accesos Técnicos:** [Código Fuente](https://github.com/bmontes93/EXON-FACE) &nbsp;·&nbsp; [Documentación del Repositorio](https://github.com/bmontes93/EXON-FACE#readme)

---

### Motor Predictivo ML & Value-Betting Deportivo
![Status](https://img.shields.io/badge/Status-En_Producción-00c853?style=flat-square)
![ML](https://img.shields.io/badge/XGBoost_&_LightGBM-FF6F00?style=flat-square)
![Celery](https://img.shields.io/badge/Celery_&_Redis-37814A?style=flat-square)
![Playwright](https://img.shields.io/badge/Playwright_Scraping-2EAD33?style=flat-square)

Pipeline cuantitativo continuo de extracción de datos en tiempo real, modelado estadístico y detección de ineficiencias de cuotas en fútbol internacional.

```mermaid
flowchart LR
    T24[T-24h: Scraping & Contexto] --> T12[T-12h: Captura de Cuotas Base]
    T12 --> T60[T-60m: Alineaciones Sofascore]
    T60 --> T55[T-55m: Inferencia XGBoost / LightGBM]
    T55 --> EDGE[Evaluación de Edge Probabilístico]
    EDGE --> ALERT[Alerta Operativa con Valor Esperado]
```

- **Orquestación Temporal Automatizada:** Pipeline asíncrono accionado por ventanas temporales estrictas: análisis de noticias y bajas en T-24h, captura de cuotas base en T-12h, extracción reactiva de alineaciones oficiales en T-60min (Sofascore) e inferencia probabilística en T-55min.
- **Modelado Probabilístico Calibrado:** Algoritmos supervisados (XGBoost y LightGBM) entrenados para estimar la probabilidad real (`P_bot`) sobre mercados de alta liquidez (córneres, tarjetas y goles combinados).
- **Ventaja Matemática (Edge):** Filtro cuantitativo con margen de seguridad probabilístico (`(1 / P_bot) * (1 + α) < Cuota_Bookie` con `α = 0.05`), disparando alertas de valor esperado positivo únicamente cuando existe una ineficiencia medible en el mercado.

---

### [quantslot-sdk](https://github.com/bmontes93/quantslot-sdk) — Motor Matemático y Simulación Estocástica para iGaming
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white)
![MonteCarlo](https://img.shields.io/badge/Simulaciones_Monte_Carlo-purple?style=flat-square)
![CSPRNG](https://img.shields.io/badge/Seguridad-CSPRNG-success?style=flat-square)

Motor matemático de simulación probabilística y certificación de slots digitales conforme a los estándares técnicos exigidos por laboratorios internacionales (GLI, iTech Labs).

- **Simulador Monte Carlo Masivo:** Capacidad para ejecutar millones de giros en pocos segundos, validando empíricamente curvas de volatilidad, distribución de frecuencias (*hit frequency*) y RTP teórico.
- **Mecánicas Dinámicas Complejas:** Soporte para estructuras dinámicas Cluster-Pay (5x5), sistemas de cascadas infinitas, multiplicadores acumulativos y rondas de bonificación multinivel.
- **Aleatoriedad Certificable:** Generador de números aleatorios criptográficamente segura (CSPRNG) para garantizar uniformidad estadística y total ausencia de patrones predictibles.
- **Accesos Técnicos:** [Código Fuente](https://github.com/bmontes93/quantslot-sdk) &nbsp;·&nbsp; [Documentación del SDK](https://github.com/bmontes93/quantslot-sdk#readme)

---

### TAHUAGYM — Plataforma Web de Alto Rendimiento con Renderizado 3D
![NextJS](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![ThreeJS](https://img.shields.io/badge/Three.js_3D-000000?style=flat-square&logo=three.js&logoColor=white)
![Lighthouse](https://img.shields.io/badge/Lighthouse-95%2B_Score-00c853?style=flat-square&logo=lighthouse&logoColor=white)
![Tailwind](https://img.shields.io/badge/TailwindCSS_v4-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

Plataforma web comercial diseñada para brindar una experiencia interactiva inmersiva y cinematográfica, manteniendo un rendimiento sobresaliente de **Lighthouse 95+**.

- **Arquitectura Web Moderna:** Renderizado híbrido SSR/SSG mediante Next.js App Router (React Server Components), arquitectura de diseño atómico y carga perezosa (*lazy loading*) de recursos pesados.
- **Visualizador 3D en Tiempo Real:** Renderizado interactivo de productos mediante Three.js y React Three Fiber con geometrías y shaders optimizados para mantener 60 FPS estables en dispositivos móviles y de escritorio.
- **Accesibilidad y SEO Técnico:** Cumplimiento de estándares WCAG AA, navegación completa por teclado, estructura semántica e integración de datos estructurados JSON-LD.

---

## Métricas de Rendimiento & Benchmarks Cuantitativos

| Sistema / Proyecto | Métrica Principal | Benchmark / Resultado Técnico | Entorno de Ejecución |
| :--- | :--- | :--- | :--- |
| **EXON-FACE** | Latencia de inferencia por frame | Reducción significativa de tiempo de procesamiento vs FP32 | NVIDIA CUDA / Tensor Cores |
| **Motor Predictivo ML** | Ventana de ejecución de inferencia | Pipeline de ingesta, cálculo y alerta completado en <90s | Celery Workers + Redis Cache |
| **quantslot-sdk** | Throughput de simulación estocástica | Millones de tiradas simuladas y analizadas en segundos | Node.js V8 Engine / In-Memory |
| **TAHUAGYM** | Core Web Vitals (Lighthouse) | 95+ Performance, 100 Accesibilidad, 100 SEO | Next.js Server Components |

---

## Trayectoria de Impacto & Hitos Técnicos

| Dominio de Ingeniería | Hito Técnico / Impacto de Producción | Paradigma Tecnológico |
| :--- | :--- | :--- |
| **Simulación Estocástica** | Motor de certificación para iGaming capaz de procesar >1,000,000 giros/segundo sin desviación estadística | Node.js · CSPRNG · Monte Carlo |
| **Visión Artificial en Tiempo Real** | Pipeline cinematográfico de transposición facial con latencia minimizada en GPUs con Tensor Cores | Python · ONNX Runtime · CUDA FP16 |
| **Modelado Predictivo Deportivo** | Orquestación distribuida de extracción, inferencia y evaluación de cuotas en <90s antes del inicio de eventos | XGBoost · Celery · Redis · Playwright |
| **Plataformas Web Inmersivas** | Experiencia comercial con renderizado 3D interactivo en tiempo real alcanzando puntuaciones Lighthouse 95+ | Next.js · Three.js · React Three Fiber |
| **Automatización & Ecosistemas SaaS** | Arquitectura modular de bots y gestión de membresías con verificación FSM y pasarelas de pago | FastAPI · PostgreSQL · aiogram 3 · Docker |

---

<details>
<summary><b>Ver más proyectos de arquitectura y software especializado</b></summary>

<br/>

#### Ecosistema SaaS de Automatización & Pagos para Telegram
> **Python · aiogram 3 · FastAPI · PostgreSQL · SQLAlchemy 2.0 · Redis · APScheduler · Docker**

Arquitectura distribuida para control de accesos, verificación de pagos y retención de usuarios en comunidades privadas mediante tres bots paralelos:
* **Verificación:** Procesamiento y validación de comprobantes bancarios mediante máquinas de estado finito (FSM), delegación a paneles administrativos y emisión de enlaces de invitación de un solo uso.
* **Retención:** Agente en segundo plano con APScheduler para avisos preventivos de renovación y revocación automática de membresías inactivas.
* **Difusión:** Módulo de comunicaciones segmentadas para campañas programadas de reactivación.

---

#### ALL-DAY — Plataforma SaaS para Gestión de Eventos
> **Next.js 15 · React 19 · TypeScript · PostgreSQL · Prisma ORM · Culqi · Resend · Pusher**

Plataforma integral para reservas de eventos y conexión de proveedores locales:
* **Seguridad:** Flujo de validación de identidad de prestadores de servicios y mensajería interna con privacidad protegida.
* **Transaccionalidad:** Sistema de reservas con pagos divididos (anticipo del 50%) integrado con la pasarela Culqi.
* **Tiempo Real:** Notificaciones Push nativas vía Service Workers y avisos in-app en tiempo real mediante Pusher.

---

#### [CALC101NG](https://github.com/bmontes93/CALC101NG) — Motor de Cálculo Simbólico y Gráficas Dinámicas
> **React · TypeScript · Vite · MathLive · Function-Plot · Python · FastAPI · SymPy · Docker**

Plataforma de análisis matemático simbólico:
* Backend asíncrono con FastAPI y SymPy para simplificación algebraica, derivadas e integrales analíticas en milisegundos.
* Editor visual interactivo WYSIWYG mediante MathLive y graficación matemática en 2D reactiva con Function-Plot.
* **Accesos Técnicos:** [Código Fuente](https://github.com/bmontes93/CALC101NG) &nbsp;·&nbsp; [Documentación de la API](https://github.com/bmontes93/CALC101NG#readme)

---

#### [GEST E-Commerce](https://github.com/bmontes93/GEST-E-COMERCE) — Arquitectura E-Commerce Desacoplada
> **TypeScript · React · Vite · Python · FastAPI · Docker Compose · JWT**

Infraestructura de tienda virtual con separación completa entre capa de presentación y servicios de backend:
* Microservicios contenerizados de despliegue independiente orquestados con Docker Compose.
* Sistema de autenticación seguro basado en tokens JWT y panel administrativo integral para inventario y órdenes.
* **Accesos Técnicos:** [Código Fuente](https://github.com/bmontes93/GEST-E-COMERCE)

---

#### [Hide-Clone-USB](https://github.com/bmontes93/Hide-Clone-USB) — Servicio de Sincronización Orientado a Eventos
> **PowerShell · Robocopy (32 Hilos) · Windows Task Scheduler**

Servicio silencioso en segundo plano para sincronización y respaldo automatizado de unidades de almacenamiento:
* Desencadenamiento reactivo mediante eventos de sistema (`DriverFrameworks`), eliminando el consumo continuo de CPU por polling.
* Copia masiva multihilo a 32 subprocesos concurrentes con permisos elevados del sistema operativo.
* **Accesos Técnicos:** [Código Fuente](https://github.com/bmontes93/Hide-Clone-USB)

</details>

---

## Stack Tecnológico

### Inteligencia Artificial & Computación Científica
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

### Testing, DevOps & Automatización
<p align="left">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/PyTest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="PyTest"/>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright"/>
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" alt="Celery"/>
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell"/>
</p>

---

## Disponibilidad Profesional & Contacto

Disponible para posiciones senior de ingeniería, liderazgo técnico y consultoría de arquitectura de sistemas:

- **Roles de Interés:** Senior Full Stack Engineer · Tech Lead · Especialista en Inferencia de IA & Arquitectura Backend.
- **Modalidad:** Remoto internacional / Híbrido.
- **Zona Horaria:** UTC-5 (disponibilidad operativa para alineación con equipos en EE.UU., LATAM y Europa).
- **Canal Directo:** [LinkedIn](https://www.linkedin.com/in/bmontesdev/) &nbsp;|&nbsp; [bmontesr930620@gmail.com](mailto:bmontesr930620@gmail.com) &nbsp;|&nbsp; [bmontesdev.me](https://bmontesdev.me)

---

## Métricas de Actividad

<p align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=bmontes93&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=1f6feb&count_private=true&include_all_commits=true&hide_rank=true&cache_seconds=1800&v=1.8" height="165" alt="Estadísticas de GitHub"/>
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=bmontes93&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&count_private=true&cache_seconds=1800&v=1.8" height="165" alt="Lenguajes Principales"/>
</p>

---

<p align="center">
  <i>"Transformando requerimientos de alta complejidad en arquitecturas de software robustas, eficientes y escalables."</i><br/>
  <b>Bryan Montes · Thekerdruid</b>
</p>
