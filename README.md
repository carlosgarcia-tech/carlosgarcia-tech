<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1620,45:16303d,100:2c5364&height=240&section=header&text=Carlos%20Garcia&fontSize=64&fontColor=ffffff&fontAlignY=36&animation=fadeIn&desc=Software%20Developer&descSize=22&descAlignY=58&descColor=8fd3ff" width="100%" alt="Carlos Garcia - Software Developer" />

<a href="https://github.com/carlosgarcia-tech">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=2C9CFF&center=true&vCenter=true&width=760&height=40&lines=Backend+Developer+%7C+Node.js+%26+TypeScript;Java+%2F+Spring+Boot+%7C+REST+API+Design;Onion+Architecture+%7C+Testing+%7C+Clean+Code;Blue%2FGreen+Deployments+%7C+Ansible+%7C+Docker;Construyendo+productos+reales%2C+de+punta+a+punta" alt="Typing SVG" />
</a>

<br/><br/>

<img src="https://skillicons.dev/icons?i=nodejs,ts,java,spring,express,nextjs,postgres,docker,ansible,nginx&perline=10" alt="Core stack" />

<br/><br/>

<a href="https://linkedin.com/in/carlos-garcia-gg"><img src="https://img.shields.io/badge/LinkedIn-carlos--garcia--gg-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://carlosgarcia-tech.github.io"><img src="https://img.shields.io/badge/Portfolio-carlosgarcia--tech.github.io-16303d?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
<a href="mailto:cgarciagarcia729@gmail.com"><img src="https://img.shields.io/badge/Email-cgarciagarcia729%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br/>

<img src="https://img.shields.io/badge/Ubicaci%C3%B3n-Oaxaca%2C%20M%C3%A9xico-2c5364?style=flat-square" alt="Ubicacion" />
<img src="https://img.shields.io/badge/Modalidad-100%25%20Remoto-2c5364?style=flat-square" alt="Remoto" />
<img src="https://img.shields.io/badge/Experiencia-3%20a%C3%B1os-2c5364?style=flat-square" alt="Experiencia" />
<img src="https://img.shields.io/badge/Ingl%C3%A9s-B1%20%E2%86%92%20B2-2c5364?style=flat-square" alt="Ingles" />
<img src="https://komarev.com/ghpvc/?username=carlosgarcia-tech&label=Visitas&color=2c5364&style=flat-square" alt="Visitas" />

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:16303d,100:2c5364&height=46&section=header&text=Sobre%20m%C3%AD&fontSize=22&fontColor=ffffff&fontAlign=4&fontAlignY=52" width="100%" alt="Sobre mi" />

Soy desarrollador de software de **Oaxaca, México**, trabajo **100% remoto** y cuento con **3 años de experiencia** entre proyectos freelance y productos propios. Mi foco está en el **backend**, el **diseño de APIs REST** y la **arquitectura de software**, con una base sólida en **Node.js / TypeScript** y **Java / Spring Boot**.

Me gusta construir sistemas completos: desde el esquema de base de datos hasta el pipeline que los despliega en producción. No me conformo con que algo funcione; busco que sea **testeable, mantenible, observable y reversible**. Por eso mis proyectos incluyen pruebas automatizadas serias, infraestructura como código y estrategias de despliegue que permiten volver atrás en menos de un minuto.

Además de programar, tengo experiencia de **liderazgo técnico** como Scrum Master y Tech Lead en equipos ágiles, y vengo de una carrera previa de cuatro años como gerente de sucursal, lo que me dio criterio para decidir bajo presión y comunicar con claridad.

<table>
<tr>
<td width="50%" valign="top">

**Actualmente**

- Construyo **Commons Marketplace**, una plataforma de e-commerce full stack con despliegue propio.
- Mantengo y vendo **VaniaBot**, un bot comercial de WhatsApp con orquestación multi-instancia.
- Profundizo en **Java 21 y Spring Boot** a nivel profesional.

</td>
<td width="50%" valign="top">

**Me interesa**

- Arquitectura limpia y lógica de negocio testeable sin mocks.
- Infraestructura como código, redes y despliegues sin downtime.
- Sistemas resilientes: circuit breakers, fallbacks y recuperación automática.

</td>
</tr>
</table>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:16303d,100:2c5364&height=46&section=header&text=Proyecto%20estrella&fontSize=22&fontColor=ffffff&fontAlign=4&fontAlignY=52" width="100%" alt="Proyecto estrella" />

### Commons Marketplace

**Ecosistema full stack propio** &nbsp;|&nbsp; backend, client y deploy &nbsp;|&nbsp; 2025 – presente

<img src="https://skillicons.dev/icons?i=nodejs,express,nextjs,postgres,ansible,githubactions,nginx,jest&perline=8" alt="Commons Marketplace stack" />

Plataforma de e-commerce completa, diseñada y construida de punta a punta: aplicación web, API, base de datos relacional y pipeline de despliegue propio.

| Área | Detalle |
|:--|:--|
| **Stack** | Node.js / Express, Next.js, PostgreSQL |
| **API** | Más de 50 endpoints REST con autenticación y autorización basada en roles |
| **Arquitectura** | Onion Architecture sobre MVC, con lógica de negocio testeable sin mocks |
| **Testing** | 1,010 pruebas automatizadas, 80% de cobertura con Jest |
| **Tiempo real** | Chat con proveedores intercambiables (Socket.io / Ably) detrás de una interfaz de repositorio compartida |
| **CI/CD** | Pipeline propio con Ansible y GitHub Actions |
| **Resiliencia** | Despliegues Blue/Green con rollback en menos de 1 minuto mediante Nginx como reverse proxy |
| **Seguridad** | Exposición segura de servicios con VPN (Tailscale) |

<details>
<summary><b>Ver arquitectura por capas (Onion Architecture)</b></summary>

<br/>

La lógica de negocio vive en el centro y no depende de frameworks, base de datos ni proveedores externos. Las dependencias apuntan siempre hacia adentro, lo que permite probar el dominio sin mocks y cambiar la infraestructura sin reescribir reglas de negocio.

```mermaid
flowchart TB
    subgraph Infra["Infraestructura"]
        direction TB
        subgraph App["Aplicación"]
            direction TB
            subgraph Dom["Dominio"]
                E["Entidades y reglas de negocio"]
            end
            U["Casos de uso"]
        end
        R["Repositorios PostgreSQL"]
        C["Proveedores de chat: Socket.io / Ably"]
        H["Controladores HTTP / Express"]
    end
    H --> U
    U --> E
    R -. implementa .-> U
    C -. implementa .-> U
```

</details>

<details>
<summary><b>Ver estrategia de despliegue Blue/Green</b></summary>

<br/>

Dos entornos idénticos conviven detrás de Nginx. El tráfico se mueve al entorno nuevo solo cuando está sano, y si algo falla se revierte automáticamente al anterior en menos de un minuto. Toda la infraestructura está definida como código con Ansible y los servicios se exponen de forma privada con Tailscale.

```mermaid
flowchart LR
    Dev["Push a main"] --> GA["GitHub Actions"]
    GA --> AN["Ansible"]
    AN --> NEW["Entorno nuevo (Green)"]
    NEW --> HC{"Health check"}
    HC -- "OK" --> SW["Nginx cambia el tráfico"]
    HC -- "Falla" --> RB["Rollback automático"]
    SW --> LIVE["Producción"]
    RB --> OLD["Entorno anterior (Blue)"]
    OLD --> LIVE
```

</details>

<details>
<summary><b>Ver detalle del chat en tiempo real</b></summary>

<br/>

El chat está desacoplado del proveedor de transporte. Tanto Socket.io como Ably implementan la misma interfaz de repositorio, de modo que se pueden intercambiar sin tocar los casos de uso ni las reglas de negocio.

```mermaid
flowchart LR
    UC["Caso de uso: enviar mensaje"] --> IF["Interfaz ChatRepository"]
    IF --> S["Adaptador Socket.io"]
    IF --> A["Adaptador Ably"]
```

</details>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:16303d,100:2c5364&height=46&section=header&text=Proyectos%20destacados&fontSize=22&fontColor=ffffff&fontAlign=4&fontAlignY=52" width="100%" alt="Proyectos destacados" />

### VaniaBot

**Producto comercial** &nbsp;|&nbsp; desarrollador único &nbsp;|&nbsp; nov 2025 – presente

<img src="https://skillicons.dev/icons?i=ts,nodejs,docker,githubactions&perline=4" alt="VaniaBot stack" />

Bot de WhatsApp construido con TypeScript y Baileys, **vendido comercialmente por grupo**. Es un producto real, con usuarios y mantenimiento continuo.

| Característica | Detalle |
|:--|:--|
| **Alcance funcional** | Más de 200 comandos en 9 dominios y más de 80 servicios integrados |
| **Orquestación** | Orquestador multi-instancia con 50 sesiones concurrentes y estado aislado por sesión |
| **Recuperación** | Heartbeat / Recovery Service para reconexión automática |
| **Resiliencia** | Middleware Pipeline con fallback de IA (Groq / LLaMA 3) y Circuit Breaker por proveedor |
| **Mantenimiento** | Refactor mayor v2.0.0: cerca de 6,800 líneas eliminadas en 177 archivos |
| **Entrega** | CI/CD con GitHub Actions y Docker, más de 502 commits |

```mermaid
flowchart LR
    M["Mensaje entrante"] --> P["Middleware Pipeline"]
    P --> CMD["Router de comandos"]
    CMD --> SVC["Servicios integrados"]
    SVC --> CB{"Circuit Breaker"}
    CB -- "Cerrado" --> EXT["Proveedor externo"]
    CB -- "Abierto" --> FB["Fallback de IA: Groq / LLaMA 3"]
    ORQ["Orquestador multi-instancia"] -. "50 sesiones aisladas" .-> P
    HB["Heartbeat / Recovery"] -. "reconexión automática" .-> ORQ
```

<br/>

### PathFinder API

**Portafolio** &nbsp;|&nbsp; desarrollador único &nbsp;|&nbsp; 2025

<img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,redis&perline=4" alt="PathFinder stack" />

API RESTful de pathfinding con mapas, waypoints, obstáculos y optimización de rutas. Incluye autenticación **JWT**, control de acceso por roles (**RBAC**) y caché con **Redis** para acelerar cálculos repetidos.

<br/>

### Hotel-System UI

**Frontend** &nbsp;|&nbsp; desarrollador único &nbsp;|&nbsp; 2025

<img src="https://skillicons.dev/icons?i=angular,ts&perline=2" alt="Hotel-System UI stack" />

Interfaz en Angular para un sistema de gestión y reservas de hotel, con arquitectura basada en componentes, enrutamiento y pruebas unitarias con Karma.

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:16303d,100:2c5364&height=46&section=header&text=Stack%20tecnol%C3%B3gico&fontSize=22&fontColor=ffffff&fontAlign=4&fontAlignY=52" width="100%" alt="Stack tecnologico" />

<table>
<tr>
<td width="180" valign="middle"><b>Lenguajes</b></td>
<td><img src="https://skillicons.dev/icons?i=ts,js,java,bash,html,css&perline=6" alt="Lenguajes" /></td>
</tr>
<tr>
<td valign="middle"><b>Backend</b></td>
<td><img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,spring&perline=6" alt="Backend" /></td>
</tr>
<tr>
<td valign="middle"><b>Frontend</b></td>
<td><img src="https://skillicons.dev/icons?i=react,nextjs,angular&perline=6" alt="Frontend" /></td>
</tr>
<tr>
<td valign="middle"><b>Bases de datos</b></td>
<td><img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,supabase&perline=6" alt="Bases de datos" /></td>
</tr>
<tr>
<td valign="middle"><b>DevOps e infraestructura</b></td>
<td><img src="https://skillicons.dev/icons?i=docker,githubactions,gitlab,ansible,nginx,linux&perline=6" alt="DevOps" /></td>
</tr>
<tr>
<td valign="middle"><b>Testing</b></td>
<td><img src="https://skillicons.dev/icons?i=jest,vitest&perline=6" alt="Testing" /></td>
</tr>
<tr>
<td valign="middle"><b>Herramientas</b></td>
<td><img src="https://skillicons.dev/icons?i=git,github,vscode,idea,postman&perline=6" alt="Herramientas" /></td>
</tr>
</table>

<div align="center">

<br/>

<img src="https://img.shields.io/badge/Tailscale-VPN-242424?style=for-the-badge&logo=tailscale&logoColor=white" alt="Tailscale" />
<img src="https://img.shields.io/badge/Socket.io-Realtime-010101?style=for-the-badge&logo=socketdotio&logoColor=white" alt="Socket.io" />
<img src="https://img.shields.io/badge/Ably-Realtime-FF5416?style=for-the-badge&logoColor=white" alt="Ably" />
<img src="https://img.shields.io/badge/Karma-Unit%20Testing-56C5A8?style=for-the-badge&logo=karma&logoColor=white" alt="Karma" />
<img src="https://img.shields.io/badge/Baileys-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Baileys" />
<img src="https://img.shields.io/badge/Groq-LLaMA%203%20%7C%20Whisper-F55036?style=for-the-badge&logoColor=white" alt="Groq" />
<img src="https://img.shields.io/badge/JWT-Auth-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT" />

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:16303d,100:2c5364&height=46&section=header&text=Especialidades&fontSize=22&fontColor=ffffff&fontAlign=4&fontAlignY=52" width="100%" alt="Especialidades" />

<table>
<tr>
<td width="50%" valign="top">

#### Arquitectura y diseño

- Onion Architecture sobre MVC
- Diseño de APIs REST con autenticación y roles
- Arquitectura orientada a microservicios
- Middleware Pipeline
- Circuit Breaker y cadenas de fallback
- Interfaces de repositorio intercambiables
- Principios SOLID y separación de responsabilidades

</td>
<td width="50%" valign="top">

#### Redes y seguridad

- Modelo TCP/IP y DNS
- Subnetting básico
- Reverse proxy con Nginx
- VPN con Tailscale
- Firewalls y acceso remoto por SSH
- Enrutamiento de tráfico Blue/Green
- Exposición segura de servicios

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### Bases de datos

- Diseño de esquemas relacionales
- Optimización en PostgreSQL y MySQL
- Fundamentos de SQL transferibles a SQL Server
- Caché con Redis
- Modelado documental con MongoDB
- Supabase como backend gestionado

</td>
<td width="50%" valign="top">

#### Calidad y automatización

- Testing con Jest, Vitest y Karma
- 1,010+ pruebas y 80% de cobertura en proyecto principal
- CI/CD con GitHub Actions y GitLab CI/CD
- Contenedores con Docker
- Infraestructura como código con Ansible
- Estrategias de rollback automático

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### Inteligencia artificial

- Integración con Groq SDK (LLaMA 3, Whisper)
- Cadenas de fallback multi-proveedor
- IA como capa de respaldo dentro de pipelines resilientes

</td>
<td width="50%" valign="top">

#### Metodología y colaboración

- Agile y Scrum
- GitHub Flow, Pull Requests y Code Review
- Liderazgo técnico (Scrum Master y Tech Lead)
- Comunicación en equipos remotos y distribuidos
- Toma de decisiones bajo presión

</td>
</tr>
</table>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:16303d,100:2c5364&height=46&section=header&text=C%C3%B3mo%20trabajo&fontSize=22&fontColor=ffffff&fontAlign=4&fontAlignY=52" width="100%" alt="Como trabajo" />

| Principio | En la práctica |
|:--|:--|
| **Diseñar para probar** | Separo el dominio de la infraestructura para que las reglas de negocio se prueben sin mocks y con feedback rápido. |
| **Desacoplar lo que puede cambiar** | Proveedores de chat, de IA y de base de datos viven detrás de interfaces, así que cambiarlos no rompe el núcleo. |
| **Desplegar sin miedo** | Blue/Green, health checks y rollback automático hacen que publicar sea una operación rutinaria y reversible. |
| **Tolerar fallos** | Circuit breakers, heartbeats y recuperación automática mantienen el servicio vivo cuando un tercero falla. |
| **Automatizar lo repetible** | Todo lo que se hace dos veces termina en un pipeline de CI/CD o en un playbook de Ansible. |
| **Reducir complejidad** | Prefiero refactorizar y eliminar código antes que acumularlo, como en el refactor v2.0.0 de VaniaBot. |

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:16303d,100:2c5364&height=46&section=header&text=Estad%C3%ADsticas%20de%20GitHub&fontSize=22&fontColor=ffffff&fontAlign=4&fontAlignY=52" width="100%" alt="Estadisticas de GitHub" />

<div align="center">

<img height="190" src="https://github-readme-stats.vercel.app/api?username=carlosgarcia-tech&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&bg_color=0b1620&title_color=2C9CFF&icon_color=2C9CFF" alt="GitHub Stats" />
<img height="190" src="https://github-readme-stats.vercel.app/api/top-langs/?username=carlosgarcia-tech&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&bg_color=0b1620&title_color=2C9CFF" alt="Top Languages" />

<br/>

<img src="https://streak-stats.demolab.com/?user=carlosgarcia-tech&theme=tokyonight&hide_border=true&background=0b1620&ring=2C9CFF&fire=2C9CFF&currStreakLabel=2C9CFF" alt="GitHub Streak" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=carlosgarcia-tech&theme=tokyo-night&hide_border=true&area=true&bg_color=0b1620&color=2C9CFF&line=2C9CFF&point=ffffff" width="100%" alt="Activity Graph" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=carlosgarcia-tech&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=10&margin-h=10" alt="Trophies" />

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:16303d,100:2c5364&height=46&section=header&text=Trayectoria&fontSize=22&fontColor=ffffff&fontAlign=4&fontAlignY=52" width="100%" alt="Trayectoria" />

```mermaid
timeline
    title Trayectoria profesional y académica
    2017 - 2021 : Gerente de Sucursal en Amor Amor Café : Liderazgo de equipo, inventario, caja y operación diaria
    2018 - 2022 : Técnico en Programación en CBTis 248
    2023 - 2025 : Ingeniería de Software en Jala University : Roles de Developer, Scrum Master y Tech Lead
    2025 : PathFinder API y Hotel-System UI : Inicio de Commons Marketplace
    Nov 2025 - presente : VaniaBot, producto comercial : Commons Marketplace en evolución
```

<table>
<tr>
<td width="50%" valign="top">

#### Educación

**Ingeniería de Software**
Jala University, 2023 – 2025

Coordiné sprints, revisé Pull Requests de mis compañeros y lideré decisiones técnicas en equipos ágiles como Developer, Scrum Master y Tech Lead.

**Técnico en Programación**
CBTis 248, Oaxaca, 2018 – 2022

</td>
<td width="50%" valign="top">

#### Experiencia previa

**Gerente de Sucursal**
Amor Amor Café, 2017 – 2021

Ascendí de miembro del equipo a gerente en cuatro años. Lideré turnos, capacitación y estándares de servicio, gestioné inventario y caja, y optimicé procesos para reducir desperdicio y tiempos de espera.

Esa etapa me dio criterio operativo, comunicación clara y la costumbre de resolver problemas en tiempo real.

</td>
</tr>
</table>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:16303d,100:2c5364&height=46&section=header&text=Idiomas%20y%20objetivos&fontSize=22&fontColor=ffffff&fontAlign=4&fontAlignY=52" width="100%" alt="Idiomas y objetivos" />

<table>
<tr>
<td width="50%" valign="top">

#### Idiomas

| Idioma | Nivel |
|:--|:--|
| Español | Nativo |
| Inglés | B1: lectura técnica y escritura fluida, preparándome activamente para B2 |

</td>
<td width="50%" valign="top">

#### Objetivos

- Profundizar en Java 21 y Spring Boot a nivel profesional.
- Llevar mis proyectos hacia arquitecturas de microservicios.
- Seguir creciendo como Tech Lead en equipos remotos.
- Alcanzar el nivel B2 de inglés.

</td>
</tr>
</table>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:16303d,100:2c5364&height=46&section=header&text=Contacto&fontSize=22&fontColor=ffffff&fontAlign=4&fontAlignY=52" width="100%" alt="Contacto" />

<div align="center">

¿Tienes un proyecto, una vacante o quieres conversar sobre arquitectura de software, backend o DevOps? Escríbeme.

<br/>

<a href="https://linkedin.com/in/carlos-garcia-gg"><img src="https://img.shields.io/badge/LinkedIn-carlos--garcia--gg-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://carlosgarcia-tech.github.io"><img src="https://img.shields.io/badge/Portfolio-carlosgarcia--tech.github.io-16303d?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
<a href="mailto:cgarciagarcia729@gmail.com"><img src="https://img.shields.io/badge/Email-cgarciagarcia729%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br/><br/>

<i>Primero hazlo funcionar, luego hazlo testeable, después hazlo reversible.</i>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,45:16303d,100:0b1620&height=120&section=footer" width="100%" alt="Footer" />

</div>
