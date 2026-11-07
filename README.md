<p align="center">
  <img src="https://raw.githubusercontent.com/bmontes93/bmontes93/main/banner.png" width="100%" alt="Bryan Montes — Senior Full Stack & Systems Engineer" />
</p>

<h1 align="center">Bryan Montes · Thekerdruid</h1>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=750&lines=Especialista+en+Visi%C3%B3n+Artificial+%26+IA+de+Baja+Latencia;Arquitecturas+Distribuidas+%26+Sistemas+de+Alta+Concurrencia;Desarrollo+Full+Stack+con+Next.js+15+%2B+Three.js+3D;Ingenier%C3%ADa+de+Alto+Rendimiento+orientada+a+Producci%C3%B3n" alt="Typing SVG" />
  </a>
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
  <img src="https://img.shields.io/badge/Commits-GPG_Verified-00c853?style=for-the-badge&logo=gnupg&logoColor=white" alt="GPG Verified"/>
</p>

---

<div align="center">

| Inferencia IA | Simulación Estocástica | Rendimiento Frontend | Integración Continua |
| :---: | :---: | :---: | :---: |
| **CUDA FP16 / Tensor Cores**<br/>`Inferencia sub-frame optimizada` | **> 1,000,000 giros/s**<br/>`CSPRNG Monte Carlo Engine` | **Lighthouse 95+ Score**<br/>`WebGL / 60 FPS Estables` | **GitHub Actions**<br/>`CI/CD Automatizado` |

</div>

---

## Perfil Profesional & Filosofía de Ingeniería

Desarrollador y arquitecto de software especializado en el diseño e implementación de **sistemas de alta concurrencia, pipelines avanzados de Inteligencia Artificial y arquitecturas web de alto rendimiento**. Mi enfoque de ingeniería combina modelado matemático, aceleración por hardware y diseño de infraestructuras desacopladas:

- **Arquitectura Limpia & Modular:** Construcción de sistemas basados en microservicios, eventos asíncronos y separación estricta de responsabilidades para garantizar mantenibilidad sin deuda técnica.
- **Rendimiento Extremo:** Optimización rigurosa de latencia: inferencia acelerada con CUDA/FP16, procesamiento distribuido y tiempos de carga sub-segundo con estrategias SSR/SSG.
- **Experiencias Interactivas 3D:** Integración de gráficos en tiempo real mediante WebGL y Three.js, alcanzando 60 FPS estables y puntuaciones Lighthouse 95+.

---

## Blueprint de Arquitectura de Referencia para Producción

Diseño de arquitectura distribuida implementado para sistemas que demandan alta disponibilidad, tolerancia a fallos y procesamiento concurrente:

```mermaid
flowchart TD
    subgraph Edge["Capa Perimetral & Balanceo"]
        DNS[DNS / Cloudflare WAF] --> CDN[Edge Cache & SSL Termination]
        CDN --> LB[Reverse Proxy / Ingress Controller]
    end

    subgraph Services["Capa de Servicios & Cómputo"]
        LB --> API[API Gateway / FastAPI / Node.js]
        API --> AUTH[Control de Acceso & JWT]
        API --> QUEUE[(Redis Message Broker / Event Bus)]
        QUEUE --> WORKERS[Worker Pools / Celery Asíncrono]
        WORKERS --> AI[Inferencia IA: ONNX Runtime CUDA FP16]
    end

    subgraph DataLayer["Persistencia & Estado"]
        API --> CACHE[(Redis In-Memory L1/L2 Cache)]
        API --> DB[(PostgreSQL / Transacciones ACID)]
        WORKERS --> DB
    end

    subgraph Telemetry["Observabilidad & Telemetría"]
        API -.-> OBS[Métricas Prometheus & Grafana]
        WORKERS -.-> LOGS[Structured Tracing & Logs]
    end
```

---

## Proyectos Destacados (Showcase Grid)

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>EXON-FACE</h3>
      <p><b>Sistema de Visión Artificial & Procesamiento Facial</b></p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/CUDA_FP16-76B900?style=flat-square&logo=nvidia&logoColor=white" />
        <img src="https://img.shields.io/badge/ONNX-007EC6?style=flat-square&logo=onnx&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      </p>
      <p>Motor de análisis, segmentación y transposición facial de alta fidelidad diseñado para flujos de vídeo de calidad cinematográfica.</p>
      <ul>
        <li><b>Segmentación BiSeNet:</b> Máscaras anatómicas a nivel de píxel (ojos, labios, piel).</li>
        <li><b>Restauración Generativa:</b> CodeFormer y GFPGAN integrados para baja resolución.</li>
        <li><b>Aceleración Hardware:</b> ONNX Runtime con Tensor Cores CUDA FP16.</li>
      </ul>
      <p>
        <a href="https://github.com/bmontes93/EXON-FACE"><b>[Ver Código Fuente]</b></a> &nbsp;
        <a href="https://github.com/bmontes93/EXON-FACE#readme"><b>[Documentación]</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>Motor Predictivo ML</h3>
      <p><b>Pipeline Cuantitativo & Value-Betting Deportivo</b></p>
      <p>
        <img src="https://img.shields.io/badge/Status-Producción-00c853?style=flat-square" />
        <img src="https://img.shields.io/badge/ML-XGBoost_LightGBM-FF6F00?style=flat-square" />
        <img src="https://img.shields.io/badge/Celery-Redis-37814A?style=flat-square" />
        <img src="https://img.shields.io/badge/Playwright-Scraping-2EAD33?style=flat-square" />
      </p>
      <p>Sistema analítico continuo de extracción masiva en tiempo real, modelado estadístico y detección de ineficiencias de mercado.</p>
      <ul>
        <li><b>Orquestación por Fases:</b> T-24h contexto, T-12h cuotas base, T-60m alineaciones y T-55m inferencia.</li>
        <li><b>Modelado Probabilístico:</b> Cálculo de probabilidad real (<code>P_bot</code>) sobre mercados de alta liquidez.</li>
        <li><b>Ventaja Matemática:</b> Margen probabilístico (<code>(1 / P_bot) * (1 + α) &lt; Cuota</code>).</li>
      </ul>
      <p>
        <b>[Sistema Propietario en Producción]</b>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>quantslot-sdk</h3>
      <p><b>Motor Matemático & Simulación Estocástica</b></p>
      <p>
        <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white" />
        <img src="https://img.shields.io/badge/Monte_Carlo-purple?style=flat-square" />
        <img src="https://img.shields.io/badge/CSPRNG-Seguro-00c853?style=flat-square" />
      </p>
      <p>Motor matemático de simulación probabilística y certificación de juegos conforme a estándares técnicos GLI y iTech Labs.</p>
      <ul>
        <li><b>Simulador Masivo:</b> Evaluación de millones de tiradas en segundos para certificar RTP y volatilidad.</li>
        <li><b>Mecánicas Dinámicas:</b> Matrices Cluster-Pay (5x5), cascadas infinitas y bonificaciones.</li>
        <li><b>Aleatoriedad CSPRNG:</b> Entropía criptográfica sin sesgos ni predictibilidad.</li>
      </ul>
      <p>
        <a href="https://github.com/bmontes93/quantslot-sdk"><b>[Ver Código Fuente]</b></a> &nbsp;
        <a href="https://github.com/bmontes93/quantslot-sdk#readme"><b>[SDK Reference]</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>TAHUAGYM</h3>
      <p><b>Plataforma Web 3D & Alto Rendimiento</b></p>
      <p>
        <img src="https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/Three.js_3D-000000?style=flat-square&logo=three.js&logoColor=white" />
        <img src="https://img.shields.io/badge/Lighthouse-95%2B_Score-00c853?style=flat-square&logo=lighthouse&logoColor=white" />
        <img src="https://img.shields.io/badge/Tailwind-v4-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
      </p>
      <p>Plataforma web comercial orientada a una experiencia interactiva inmersiva, logrando puntuaciones de rendimiento sobresalientes.</p>
      <ul>
        <li><b>Arquitectura SSR/SSG:</b> App Router con React Server Components y bundle optimizado.</li>
        <li><b>Visualizador 3D:</b> Three.js y React Three Fiber con geometrías optimizadas a 60 FPS estables.</li>
        <li><b>SEO & Accesibilidad:</b> WCAG AA compliant y datos estructurados JSON-LD.</li>
      </ul>
      <p>
        <b>[Plataforma Comercial Desplegada]</b>
      </p>
    </td>
  </tr>
</table>

---

## Dominios de Especialidad & Competencias Técnicas

| Área Técnica | Stack Clave | Enfoque de Ingeniería |
| :--- | :--- | :--- |
| **IA & Visión Artificial** | Python · ONNX Runtime · NVIDIA CUDA · OpenCV · InsightFace | Inferencia en tiempo real (FP16), segmentación facial y restauración generativa |
| **Machine Learning & Big Data** | XGBoost · LightGBM · Celery · Redis · PostgreSQL · Playwright | Orquestación distribuida, pipelines reactivos y modelos cuantitativos |
| **Sistemas & iGaming Math** | Node.js · TypeScript · Simulaciones Monte Carlo · CSPRNG | Simulación estocástica masiva (millones de giros/s) y certificación matemática |
| **Frontend Moderno & 3D Web** | Next.js 15 · React 19 · Three.js · React Three Fiber · TailwindCSS | Renderizado 3D a 60 FPS estables, Server Components y accesibilidad AA |

---

## Patrones de Arquitectura, Seguridad & I+D

- **Patrones Arquitectónicos:** Segregación CQRS, Arquitectura Orientada a Eventos (EDA), Máquinas de Estado Finito (FSM) para procesos transaccionales y patrón Repositorio / Service Layer desacoplado.
- **Seguridad & Hardening:** Generación criptográfica CSPRNG certificable, validación estricta de esquemas en runtime con Pydantic y Zod, hashing Argon2/bcrypt, JWT con rotación y rate-limiting en memoria con Redis.
- **Investigación Activa (I+D):** Inferencia local de LLMs mediante cuantización GGUF/AWQ con vLLM, compilación de algoritmos matemáticos a WebAssembly con Rust y patrones Event Sourcing.

---

## Stack Tecnológico

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,opencv,nodejs,typescript,fastapi,postgres,redis,nextjs,react,threejs,tailwind,docker,githubactions,linux&theme=dark" alt="Tech Stack Icons" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/NVIDIA_CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA"/>
  <img src="https://img.shields.io/badge/ONNX_Runtime-007EC6?style=flat-square&logo=onnx&logoColor=white" alt="ONNX"/>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white" alt="Three.js"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/PyTest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="PyTest"/>
</p>

---

## Métricas de Rendimiento & Benchmarks Cuantitativos

| Sistema / Proyecto | Métrica Principal | Benchmark / Resultado Técnico | Entorno de Ejecución |
| :--- | :--- | :--- | :--- |
| **EXON-FACE** | Latencia de inferencia por frame | Reducción significativa de tiempo de procesamiento vs FP32 | NVIDIA CUDA / Tensor Cores |
| **Motor Predictivo ML** | Ventana de ejecución de inferencia | Pipeline de ingesta, cálculo y alerta completado en <90s | Celery Workers + Redis Cache |
| **quantslot-sdk** | Throughput de simulación estocástica | Millones de tiradas simuladas y analizadas en segundos | Node.js V8 Engine / In-Memory |
| **TAHUAGYM** | Core Web Vitals (Lighthouse) | 95+ Performance, 100 Accesibilidad, 100 SEO | Next.js Server Components |

---

<details>
<summary><b>Ver proyectos adicionales de arquitectura y software especializado</b></summary>

<br/>

#### Ecosistema SaaS de Automatización & Pagos para Telegram
> **Python · aiogram 3 · FastAPI · PostgreSQL · SQLAlchemy 2.0 · Redis · APScheduler · Docker**
* Arquitectura distribuida para control de accesos, verificación de comprobantes mediante máquinas de estado finito (FSM), alertas con APScheduler y campañas segmentadas.

---

#### ALL-DAY — Plataforma SaaS para Gestión de Eventos
> **Next.js 15 · React 19 · TypeScript · PostgreSQL · Prisma ORM · Culqi · Resend · Pusher**
* Sistema de reservas y pagos fraccionados (anticipo del 50%) con Culqi, verificación de identidad y notificaciones push nativas vía Service Workers.

---

#### [CALC101NG](https://github.com/bmontes93/CALC101NG) — Motor de Cálculo Simbólico y Gráficas Dinámicas
> **React · TypeScript · Vite · MathLive · Function-Plot · Python · FastAPI · SymPy · Docker**
* Backend asíncrono con FastAPI y SymPy para simplificación algebraica analítica en milisegundos y editor visual interactivo WYSIWYG con MathLive.
* **[Código Fuente](https://github.com/bmontes93/CALC101NG)** &nbsp;·&nbsp; **[Documentación de API](https://github.com/bmontes93/CALC101NG#readme)**

---

#### [GEST E-Commerce](https://github.com/bmontes93/GEST-E-COMERCE) — Arquitectura E-Commerce Desacoplada
> **TypeScript · React · Vite · Python · FastAPI · Docker Compose · JWT**
* Microservicios contenerizados de despliegue independiente mediante Docker Compose y panel administrativo integral para inventario y órdenes.
* **[Código Fuente](https://github.com/bmontes93/GEST-E-COMERCE)**

---

#### [Hide-Clone-USB](https://github.com/bmontes93/Hide-Clone-USB) — Servicio de Sincronización Orientado a Eventos
> **PowerShell · Robocopy (32 Hilos) · Windows Task Scheduler**
* Respaldo reactivo desencadenado por eventos de kernel de Windows (`DriverFrameworks`), sin consumo continuo de CPU por sondeo y copia masiva a 32 subprocesos.
* **[Código Fuente](https://github.com/bmontes93/Hide-Clone-USB)**

</details>

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
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=bmontes93&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=1f6feb&count_private=true&include_all_commits=true&hide_rank=true&cache_seconds=1800&v=2.0" height="165" alt="Estadísticas de GitHub"/>
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=bmontes93&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&count_private=true&cache_seconds=1800&v=2.0" height="165" alt="Lenguajes Principales"/>
</p>

---

<p align="center">
  <i>"Transformando requerimientos de alta complejidad en arquitecturas de software robustas, eficientes y escalables."</i><br/>
  <b>Bryan Montes · Thekerdruid</b>
</p>
