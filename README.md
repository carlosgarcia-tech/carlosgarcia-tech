<div align="center">

<img src="assets/header.svg" width="100%" alt="Carlos Garcia - Software Developer" />

<a href="https://github.com/carlosgarcia-tech">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=2C9CFF&center=true&vCenter=true&width=760&height=40&lines=Backend+Developer+%7C+Node.js+%26+TypeScript;Java+%2F+Spring+Boot+%7C+REST+API+Design;Clean+Architecture+%7C+Testing+%7C+CI%2FCD;Blue%2FGreen+Deployments+%7C+Ansible+%7C+Docker" alt="Typing SVG" />
</a>

<br/><br/>

<img src="https://skillicons.dev/icons?i=nodejs,ts,java,spring,express,nextjs,postgres,docker,ansible,nginx&perline=10" alt="Core stack" />

<br/><br/>

<a href="https://linkedin.com/in/carlos-garcia-gg"><img src="https://img.shields.io/badge/LinkedIn-carlos--garcia--gg-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://carlosgarcia-tech.github.io"><img src="https://img.shields.io/badge/Portfolio-carlosgarcia--tech.github.io-16303d?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
<a href="mailto:cgarciagarcia729@gmail.com"><img src="https://img.shields.io/badge/Email-cgarciagarcia729%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br/>

<img src="https://img.shields.io/badge/Location-Oaxaca%2C%20Mexico-2c5364?style=flat-square" alt="Location" />
<img src="https://img.shields.io/badge/Work-100%25%20Remote-2c5364?style=flat-square" alt="Remote" />
<img src="https://img.shields.io/badge/English-B1%20%E2%86%92%20B2-2c5364?style=flat-square" alt="English level" />
<img src="https://komarev.com/ghpvc/?username=carlosgarcia-tech&label=Views&color=2c5364&style=flat-square" alt="Profile views" />

</div>

<br/>

<img src="assets/sec-about.svg" width="100%" alt="About me" />

<br/>

<div align="center">
  <img src="assets/terminal.svg" width="78%" alt="Animated terminal" />
</div>

<br/>

Backend-focused software developer from **Oaxaca, Mexico**, working **fully remote** with **3 years** of experience across freelance work and my own products. I design REST APIs, structure clean and testable architectures, and own the path from database schema to production deployment, with a strong base in **Node.js / TypeScript** and **Java / Spring Boot**.

I care about software that is **testable, resilient and reversible**. I've also led agile teams as **Scrum Master and Tech Lead**, and spent four years managing a café branch before moving into tech, which taught me to decide under pressure and communicate clearly.

<div align="center">
  <img src="assets/numeros.svg" width="100%" alt="Key numbers" />
</div>

<br/>

<img src="assets/sec-now.svg" width="100%" alt="Currently" />

<br/>

- Building a **full-stack marketplace** deployed with Blue/Green and automatic rollback.
- Maintaining a **commercial bot product** with real customers.
- Going deeper into **Java 21, Spring Boot and microservices**.
- Working toward **B2 English**.

<br/>

<img src="assets/sec-stack.svg" width="100%" alt="Tech stack" />

<br/>

<table>
<tr>
<td width="180" valign="middle"><b>Languages</b></td>
<td><img src="https://skillicons.dev/icons?i=ts,js,java,bash&perline=4" alt="Languages" /></td>
</tr>
<tr>
<td valign="middle"><b>Backend</b></td>
<td><img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,spring&perline=4" alt="Backend" /></td>
</tr>
<tr>
<td valign="middle"><b>Frontend</b></td>
<td><img src="https://skillicons.dev/icons?i=react,nextjs,angular&perline=3" alt="Frontend" /></td>
</tr>
<tr>
<td valign="middle"><b>Databases</b></td>
<td><img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,supabase&perline=5" alt="Databases" /></td>
</tr>
<tr>
<td valign="middle"><b>DevOps</b></td>
<td><img src="https://skillicons.dev/icons?i=docker,githubactions,gitlab,ansible,nginx,linux&perline=6" alt="DevOps" /></td>
</tr>
<tr>
<td valign="middle"><b>Testing</b></td>
<td><img src="https://skillicons.dev/icons?i=jest,vitest&perline=2" alt="Testing" /></td>
</tr>
</table>

<br/>

<img src="assets/sec-engineering.svg" width="100%" alt="Engineering" />

<br/>

| Focus                       | What it looks like in practice                                                                        |
| :-------------------------- | :---------------------------------------------------------------------------------------------------- |
| **Design for testability**  | Onion Architecture keeps business logic independent of frameworks, so it can be tested without mocks. |
| **Ship without fear**       | Blue/Green deployments, health checks and automatic rollback make releases routine and reversible.    |
| **Tolerate failure**        | Circuit breakers, fallbacks and automatic recovery keep services alive when a third party fails.      |
| **Automate the repeatable** | CI/CD pipelines, Docker and infrastructure as code with Ansible.                                      |
| **Secure by default**       | Reverse proxies, VPN-only exposure, role-based access control and sensible network boundaries.        |

<details>
<summary><b>Blue/Green deployment with automatic rollback</b></summary>

<br/>

```mermaid
flowchart LR
    Dev["Push to main"] --> CI["CI/CD pipeline"]
    CI --> NEW["New environment (Green)"]
    NEW --> HC{"Health check"}
    HC -- "Pass" --> SW["Proxy switches traffic"]
    HC -- "Fail" --> RB["Automatic rollback"]
    SW --> LIVE["Production"]
    RB --> OLD["Previous environment (Blue)"]
    OLD --> LIVE
```

</details>

<details>
<summary><b>Onion Architecture</b></summary>

<br/>

```mermaid
flowchart TB
    subgraph Infra["Infrastructure"]
        direction TB
        subgraph App["Application"]
            direction TB
            subgraph Dom["Domain"]
                E["Entities and business rules"]
            end
            U["Use cases"]
        end
        R["Data repositories"]
        P["External providers"]
        H["HTTP controllers"]
    end
    H --> U
    U --> E
    R -. implements .-> U
    P -. implements .-> U
```

</details>

<br/>

<img src="assets/sec-stats.svg" width="100%" alt="GitHub stats" />

<br/>

<div align="center">

<img height="190" src="https://github-readme-stats.vercel.app/api?username=carlosgarcia-tech&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&bg_color=0b1620&title_color=2C9CFF&icon_color=2C9CFF" alt="GitHub stats" />
<img height="190" src="https://github-readme-stats.vercel.app/api/top-langs/?username=carlosgarcia-tech&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&bg_color=0b1620&title_color=2C9CFF" alt="Top languages" />

<br/>

<img src="https://streak-stats.demolab.com/?user=carlosgarcia-tech&theme=tokyonight&hide_border=true&background=0b1620&ring=2C9CFF&fire=2C9CFF&currStreakLabel=2C9CFF" alt="GitHub streak" />

<br/>

<img src="https://ghchart.rshah.org/2C9CFF/carlosgarcia-tech" width="95%" alt="Contribution calendar" />

<br/>

<a href="https://github.com/carlosgarcia-tech?tab=followers"><img src="https://img.shields.io/github/followers/carlosgarcia-tech?style=for-the-badge&logo=github&logoColor=white&label=Followers&labelColor=0b1620&color=2C9CFF" alt="GitHub followers" /></a>
<a href="https://github.com/carlosgarcia-tech?tab=repositories"><img src="https://img.shields.io/badge/Repositories-Browse-2C9CFF?style=for-the-badge&logo=github&logoColor=white&labelColor=0b1620" alt="Repositories" /></a>

</div>

<br/>

<img src="assets/sec-background.svg" width="100%" alt="Background" />

<br/>

<table>
<tr>
<td width="50%" valign="top">

**Education**

Software Engineering, Jala University (2023 – 2025)
Led sprints and technical decisions as Developer, Scrum Master and Tech Lead.

Technical Degree in Programming, CBTis 248 (2018 – 2022)

</td>
<td width="50%" valign="top">

**Previous experience**

Branch Manager, Amor Amor Café (2017 – 2021)
Promoted from team member to manager; led the team, managed inventory and cash, and optimized daily operations.

**Languages:** Spanish (native), English (B1, working toward B2)

</td>
</tr>
</table>

<br/>

<img src="assets/sec-contact.svg" width="100%" alt="Contact" />

<br/>

<div align="center">

Have a project, an opening, or just want to talk backend and DevOps? Get in touch.

<br/><br/>

<a href="https://linkedin.com/in/carlos-garcia-gg"><img src="https://img.shields.io/badge/LinkedIn-carlos--garcia--gg-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://carlosgarcia-tech.github.io"><img src="https://img.shields.io/badge/Portfolio-carlosgarcia--tech.github.io-16303d?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
<a href="mailto:cgarciagarcia729@gmail.com"><img src="https://img.shields.io/badge/Email-cgarciagarcia729%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br/><br/>

<img src="assets/cat-walk.svg" width="100%" alt="Walking cat" />

<br/>

<img src="assets/footer.svg" width="100%" alt="Profile footer" />

</div>
