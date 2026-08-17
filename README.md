# Luiz Felipe de Mello Grochevski

**Backend Developer** (Java/Spring Boot + Flutter) | Security Engineering  
3+ anos em produção • Ferramentas próprias de AppSec em Rust

> **TL;DR** — Desenvolvo backends robustos com foco em segurança aplicada; desenvolvo e mantenho ferramentas de AppSec em Rust.  
> Building in public — compartilho o processo, não só o resultado.

<div align="center">
  <a href="https://github.com/LuizGrochevski"><img src="https://img.shields.io/badge/OS-Linux-A81D33?style=flat-square&logo=linux&logoColor=white" alt="Linux" /></a>
  <a href="https://www.coursera.org/professional-certificates/google-cybersecurity"><img src="https://img.shields.io/badge/Study-Google%20Cybersecurity-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google Cybersecurity Certificate" /></a>
</div>

## Sumário

- [Sobre mim](#sobre-mim)
- [Tecnologias](#tecnologias)
- [Projetos em Destaque](#projetos-em-destaque)
- [Objetivo](#objetivo)
- [Contato](#contato)

## Sobre mim

- 3+ anos construindo e mantendo apps backend e mobile em produção (TX Fuel, Evo Sistemas, DIXI Soluções).
- Stack principal: **Java, Spring Boot, Flutter/Dart, PostgreSQL, APIs REST**.
- Diferencial: ferramentas de segurança ofensiva/defensiva em **Rust** (scanner de rede, SAST, API security, honeypot).
- Engenharia de Software (Universidade Positivo) + Google Cybersecurity Certificate (em andamento).
- Gosto de transformar estudo em ferramenta real — cada projeto do pipeline nasceu de algo que eu precisava na prática.

## Tecnologias

| Categoria | Dominadas | Em estudo / Uso frequente |
| :--- | :--- | :--- |
| **Linguagens** | Java, Rust, Dart/Flutter | Python |
| **Frameworks** | Spring Boot, Quarkus | FastAPI |
| **Fundamentos** | APIs REST, TCP/IP, HTTP, Sockets | Modelo OSI, Engenharia Assíncrona |
| **Segurança** | OWASP Top 10, SAST, Nmap, SQLMap | Banner Grabbing, Enumeração |
| **Ambiente** | Linux, Git, Docker, Maven | Termux / Android |

## Projetos em Destaque

Dois pipelines independentes: auditoria de rede e AppSec de código.

**Rede & Monitoramento**

```
Sentinel-RS (scan) → netwatch-api (orquestra) → cve-lookup (CVEs) → netwatch-dashboard (visualiza)
                              ↑
        traprs (detecção de ataques, roda em paralelo, alimenta via webhook)
```

- **[Sentinel-RS](https://github.com/LuizGrochevski/Sentinel-RS)** — Scanner assíncrono em Rust (TCP/UDP/SYN, fingerprinting 64+, TLS/JA3S, Nmap XML).
- **[netwatch-api](https://github.com/LuizGrochevski/netwatch-api)** — API FastAPI + JWT que orquestra o Sentinel-RS.
- **[netwatch-dashboard](https://github.com/LuizGrochevski/netwatch-dashboard)** — Painel web em React + Vite para visualização de scans em tempo real.
- **[cve-lookup](https://github.com/LuizGrochevski/cve-lookup)** — CLI Python para consulta de vulnerabilidades NVD/CPE.
- **[traprs](https://github.com/LuizGrochevski/traprs)** — Honeypot TCP (SSH/HTTP/HTTPS) com alertas em tempo real.
- **[syswatch-tui](https://github.com/LuizGrochevski/syswatch-tui)** — Dashboard TUI em Rust (Ratatui) para monitoramento em Termux/Android.

**AppSec**

```
javasast-rs / apisec-rs / secretscan-rs  (scanners independentes)
                    ↓
plugins Maven/Gradle (CI/CD)  +  insecure-java-lab (alvo de teste)
                    ↓
       Relatórios (JSON / Markdown / SARIF)
```

- **[javasast-rs](https://github.com/LuizGrochevski/javasast-rs)** — SAST para Java (12 regras OWASP, SARIF, baseline, plugins Maven/Gradle).
- **[javasast-maven-plugin](https://github.com/LuizGrochevski/javasast-maven-plugin)** — Plugin Maven que roda javasast-rs durante o build.
- **[javasast-gradle-plugin](https://github.com/LuizGrochevski/javasast-gradle-plugin)** — Plugin Gradle equivalente, integrado na task `check`.
- **[insecure-java-lab](https://github.com/LuizGrochevski/insecure-java-lab)** — Código Java deliberadamente vulnerável usado como alvo de teste.
- **[apisec-rs](https://github.com/LuizGrochevski/apisec-rs)** — Testes de API a partir de OpenAPI (auth quebrada, IDOR, headers, rate limit).
- **[secretscan-rs](https://github.com/LuizGrochevski/secretscan-rs)** — Detecção de secrets (histórico git + entropia).

## Objetivo

Atuar como **Backend Developer** (Java/Spring Boot e Flutter), aplicando Security Engineering como diferencial técnico. Aberto a oportunidades remotas ou híbridas.

## Contato

<a href="https://br.linkedin.com/in/luiz-felipe-grochevski" target="_blank">
  <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://www.threads.com/@luiz.grochevski" target="_blank">
  <img src="https://img.shields.io/badge/-Threads-000000?style=for-the-badge&logo=threads&logoColor=white" alt="Threads" />
</a>
<a href="https://www.instagram.com/luiz.grochevski" target="_blank">
  <img src="https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
</a>
