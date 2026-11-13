<p align="center">
  <img src="./assets/hero-banner.svg" width="100%" alt="Bryan Montes · Thekerdruid — Senior Full Stack & Systems Engineer HUD" />
</p>

<p align="center">
  <a href="https://bmontesdev.me" target="_blank">
    <img src="https://img.shields.io/badge/Portafolio-090D16?style=for-the-badge&logo=google-chrome&logoColor=38BDF8" alt="Portafolio"/>
  </a>
  <a href="https://www.linkedin.com/in/bmontesdev/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-090D16?style=for-the-badge&logo=linkedin&logoColor=38BDF8" alt="LinkedIn"/>
  </a>
  <a href="mailto:bmontesr930620@gmail.com">
    <img src="https://img.shields.io/badge/Contacto_Directo-090D16?style=for-the-badge&logo=gmail&logoColor=F43F5E" alt="Email"/>
  </a>
  <a href="https://github.com/bmontes93/bmontes93/actions/workflows/readme-ci.yml">
    <img src="https://img.shields.io/github/actions/workflow/status/bmontes93/bmontes93/readme-ci.yml?branch=main&style=for-the-badge&logo=githubactions&logoColor=10B981&label=SYSTEMS%20CI&color=090D16" alt="Quality CI"/>
  </a>
  <img src="https://img.shields.io/badge/Commits-GPG_Verified-090D16?style=for-the-badge&logo=gnupg&logoColor=10B981" alt="GPG Verified"/>
</p>

---

## Sistemas en Producción & Showcase de Ingeniería

Cada sistema está diseñado bajo tres principios no negociables: **baja latencia medible**, **arquitectura desacoplada libre de deuda técnica** y **verificación matemática/automatizada antes de entrar a producción**.

<p align="center">
  <img src="./assets/projects-bento.svg" width="100%" alt="Proyectos Destacados — Simulaciones y Telemetría en Vivo" />
</p>

<div align="center">

| Sistema | Dominio Técnico | Stack de Producción | Accesos Directos |
| :--- | :--- | :--- | :---: |
| **EXON-FACE** | Visión Artificial & Restauración Generativa | Python · ONNX Runtime · CUDA FP16 · BiSeNet · Docker | [**Código Fuente**](https://github.com/bmontes93/EXON-FACE) · [**Docs**](https://github.com/bmontes93/EXON-FACE#readme) |
| **Motor Predictivo ML** | Modelado Probabilístico & Value-Betting | Python · XGBoost · LightGBM · Celery · Redis · Playwright | `Producción Activa` |
| **quantslot-sdk** | Simulación Estocástica Monte Carlo & iGaming | Node.js · TypeScript · CSPRNG (GLI-19) · V8 Engine | [**Código Fuente**](https://github.com/bmontes93/quantslot-sdk) · [**SDK**](https://github.com/bmontes93/quantslot-sdk#readme) |
| **TAHUAGYM 3D** | E-Commerce Inmersivo WebGL & SSR/SSG | Next.js 15 · React 19 · Three.js / R3F · Tailwind v4 | `Producción Activa` |

</div>

---

## Arquitectura Distribuida & Flujo de Datos en Tiempo Real

Diseño de referencia implementado para cargas de alta concurrencia, desacoplando la capa de validación perimetral, el bus de eventos asíncrono y los nodos de inferencia acelerados por GPU:

<p align="center">
  <img src="./assets/architecture-live.svg" width="100%" alt="Blueprint de Arquitectura Distribuida en Vivo" />
</p>

---

## Telemetría de Estación de Trabajo & Benchmarks Reales

Ejecución verificada sobre entorno Linux (Debian WSL2) con aceleración dedicada NVIDIA CUDA / TensorRT y suites de pruebas automatizadas:

<p align="center">
  <img src="./assets/terminal-bench.svg" width="100%" alt="Terminal de Benchmarks y Telemetría en Vivo" />
</p>

---

## Ecosistema Tecnológico & Herramientas de Producción

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,opencv,nodejs,typescript,fastapi,postgres,redis,nextjs,react,threejs,tailwind,docker,githubactions,linux&theme=dark" alt="Tech Stack Icons" />
</p>

| Dominio de Ingeniería | Patrones & Estándares Aplicados | Seguridad, Hardening & I+D |
| :--- | :--- | :--- |
| **IA & Visión por Computador** | Cuantización FP16/INT8 · Precarga en VRAM · Segmentación semántica BiSeNet | Inferencia local de LLMs (GGUF/AWQ con vLLM) y agentes autónomos |
| **Backend & Sistemas Distribuidos** | CQRS · Event-Driven Architecture · Máquinas de Estado Finito (FSM) · Celery Pools | Validación estricta en fronteras (Pydantic / Zod) + Rate Limiting en Redis |
| **Simulación & Criptografía** | Motores Monte Carlo (>1M ops/s) · Matrices dinámicas Cluster-Pay 5×5 | Generación de entropía CSPRNG auditable y firma criptográfica GPG |
| **Frontend & Gráficos 3D** | React Server Components (RSC) · Geometrías y Shaders GLSL a 60 FPS | Compilación de núcleos matemáticos a WebAssembly (Rust / WASM) |

---

<details>
<summary><b>Explorar catálogo adicional de arquitecturas SaaS, motores simbólicos y utilidades de sistema</b></summary>

<br/>

| Proyecto | Arquitectura & Stack | Resumen de Ingeniería | Acceso |
| :--- | :--- | :--- | :---: |
| **Telegram SaaS Suite** | Python · aiogram 3 · FastAPI · PostgreSQL · Redis · Docker | Ecosistema de 3 bots concurrentes: validación de pagos vía FSM, retención automatizada con APScheduler y campañas segmentadas. | `Enterprise` |
| **ALL-DAY SaaS** | Next.js 15 · React 19 · TypeScript · Prisma · Culqi · Pusher | Plataforma de reservas con pagos divididos (50% anticipo), verificación de identidad y notificaciones Push vía Service Workers. | `Producción` |
| **CALC101NG** | FastAPI · SymPy · React 19 · TypeScript · MathLive · Docker | Motor asíncrono de cálculo simbólico (derivadas, integrales y sistemas paso a paso) con editor matemático WYSIWYG y graficación 2D. | [**Repositorio**](https://github.com/bmontes93/CALC101NG) |
| **GEST E-Commerce** | TypeScript · React · FastAPI · Docker Compose · JWT | Infraestructura de comercio electrónico desacoplada en microservicios independientes con autenticación JWT y rotación de sesiones. | [**Repositorio**](https://github.com/bmontes93/GEST-E-COMERCE) |
| **Hide-Clone-USB** | PowerShell · Robocopy (32 Hilos) · Windows Event Triggers | Servicio silencioso accionado por eventos del kernel (`DriverFrameworks`), cero consumo de CPU en reposo y sincronización multihilo. | [**Repositorio**](https://github.com/bmontes93/Hide-Clone-USB) |

</details>

---

## Actividad de Ingeniería & Contribuciones

<p align="center">
  <img src="https://raw.githubusercontent.com/bmontes93/bmontes93/output/github-contribution-grid-snake-dark.svg" width="100%" alt="Mapa de Contribuciones Animado" />
</p>

<p align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=bmontes93&show_icons=true&theme=tokyonight&hide_border=true&bg_color=090D16&title_color=38BDF8&text_color=E2E8F0&icon_color=10B981&count_private=true&include_all_commits=true&hide_rank=true&cache_seconds=1800&v=3.0" height="165" alt="Estadísticas de GitHub"/>
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=bmontes93&layout=compact&theme=tokyonight&hide_border=true&bg_color=090D16&title_color=38BDF8&text_color=E2E8F0&count_private=true&cache_seconds=1800&v=3.0" height="165" alt="Lenguajes Principales"/>
</p>

---

## Disponibilidad Profesional & Contacto

Disponible para posiciones **Senior Full Stack Engineer**, **Tech Lead** y **Consultoría en Inferencia de IA / Arquitecturas de Alta Concurrencia**:

- **Modalidad & Zona Horaria:** Remoto Internacional / Híbrido · **UTC-5** (alineación directa con equipos en EE.UU., LATAM y Europa).
- **Canales Directos:** [**Portafolio Web (bmontesdev.me)**](https://bmontesdev.me) &nbsp;·&nbsp; [**LinkedIn (/in/bmontesdev)**](https://www.linkedin.com/in/bmontesdev/) &nbsp;·&nbsp; [**bmontesr930620@gmail.com**](mailto:bmontesr930620@gmail.com)
