# Luiz Felipe Grochevski

**Backend Developer · Java / Spring Boot · Flutter · Security Engineering**

🇧🇷 **Português** · [🇺🇸 English](./README-en.md)

Transformo estudo em software real. Gosto de começar por uma pergunta técnica ou um problema concreto e transformar o aprendizado em ferramentas testáveis e utilizáveis.

> **Foco atual:** Backend Development com Java/Spring Boot, enquanto aprofundo minha atuação em Security Engineering e AppSec.

<div align="center">
  <a href="https://github.com/LuizGrochevski"><img src="https://img.shields.io/badge/OS-Linux-A81D33?style=flat-square&logo=linux&logoColor=white" alt="Linux" /></a>
  <a href="https://www.coursera.org/professional-certificates/google-cybersecurity"><img src="https://img.shields.io/badge/Study-Google%20Cybersecurity-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google Cybersecurity" /></a>
  <a href="https://www.linkedin.com/in/luiz-felipe-grochevski"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</div>

## Sumário

- [Sobre mim](#sobre-mim)
- [Tecnologias](#tecnologias)
- [Projetos em Destaque](#projetos-em-destaque)
- [Objetivo](#objetivo)
- [Contato](#contato)

## Sobre mim

- 3+ anos de experiência prática com desenvolvimento e manutenção de aplicações backend e mobile.
- Stack principal: **Java, Spring Boot, Flutter/Dart, PostgreSQL e APIs REST**.
- Desenvolvo ferramentas de **Security Engineering em Rust**, explorando network scanning, SAST, API security e honeypots.
- Engenharia de Software — Universidade Positivo.
- Google Cybersecurity Certificate — em andamento.
- Tenho interesse especial em sistemas backend, networking, concorrência assíncrona e segurança aplicada.

## Tecnologias

| Categoria | Principal | Em desenvolvimento |
| :--- | :--- | :--- |
| **Linguagens** | Java, Rust, Dart/Flutter | Python |
| **Frameworks** | Spring Boot, Quarkus, Flutter | FastAPI |
| **Fundamentos** | REST, TCP/IP, HTTP, Sockets | Engenharia assíncrona |
| **Segurança** | OWASP Top 10, SAST, Nmap, SQLMap | AppSec, Enumeração |
| **Ambiente** | Linux, Git, Docker, Maven | Termux / Android |

## Projetos em Destaque

Meus projetos estão organizados em dois eixos principais: **Network Security** e **Application Security**.

### 🌐 Network Security

```text
Sentinel-RS (scan) → netwatch-api (orquestra) → cve-lookup (CVEs) → netwatch-dashboard (visualiza)
                             ↑
        traprs (detecção de ataques, roda em paralelo, alimenta via webhook)
```

- **[Sentinel-RS](https://github.com/LuizGrochevski/Sentinel-RS)** — Scanner assíncrono em Rust com TCP/UDP/SYN scanning, 64+ service fingerprints, TLS/JA3S e Nmap XML.
- **[netwatch-api](https://github.com/LuizGrochevski/netwatch-api)** — API FastAPI + JWT que orquestra o Sentinel-RS.
- **[netwatch-dashboard](https://github.com/LuizGrochevski/netwatch-dashboard)** — Dashboard web em React + Vite para visualização de scans em tempo real.
- **[cve-lookup](https://github.com/LuizGrochevski/cve-lookup)** — CLI em Python para consulta de vulnerabilidades usando NVD/CPE.
- **[traprs](https://github.com/LuizGrochevski/traprs)** — Honeypot TCP para SSH/HTTP/HTTPS com alertas em tempo real.
- **[syswatch-tui](https://github.com/LuizGrochevski/syswatch-tui)** — Dashboard TUI em Rust/Ratatui para monitoramento em Termux/Android.

### 🔐 Application Security

```text
javasast-rs / apisec-rs / secretscan-rs
                     ↓
plugins Maven/Gradle + insecure-java-lab
                     ↓
        JSON / Markdown / SARIF
```

- **[javasast-rs](https://github.com/LuizGrochevski/javasast-rs)** — SAST para Java com 12 regras OWASP, SARIF, baseline e integração com Maven/Gradle.
- **[javasast-maven-plugin](https://github.com/LuizGrochevski/javasast-maven-plugin)** — Plugin Maven para executar javasast-rs durante o build.
- **[javasast-gradle-plugin](https://github.com/LuizGrochevski/javasast-gradle-plugin)** — Plugin Gradle integrado à task `check`.
- **[insecure-java-lab](https://github.com/LuizGrochevski/insecure-java-lab)** — Aplicação Java deliberadamente vulnerável para testes de segurança.
- **[apisec-rs](https://github.com/LuizGrochevski/apisec-rs)** — Testes de segurança de APIs a partir de especificações OpenAPI.
- **[secretscan-rs](https://github.com/LuizGrochevski/secretscan-rs)** — Detecção de secrets em histórico Git usando padrões e análise de entropia.

## Objetivo

Atuar como **Backend Developer**, principalmente com **Java/Spring Boot**, usando Security Engineering como diferencial técnico e aprofundando minha especialização em **AppSec e segurança de sistemas**.

Aberto a oportunidades **remotas ou híbridas**, no Brasil ou internacionalmente.

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
