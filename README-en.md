# Luiz Felipe Grochevski

**Backend Developer · Java / Spring Boot · Flutter · Security Engineering**

[🇧🇷 Português](./README.md) · 🇺🇸 **English**

I turn study into real software. I like starting with a technical question or a concrete problem and turning what I learn into tools that can be tested and actually used.

> **Current focus:** Backend Development with Java/Spring Boot, while deepening my work in Security Engineering and AppSec.

<div align="center">
  <a href="https://github.com/LuizGrochevski"><img src="https://img.shields.io/badge/OS-Linux-A81D33?style=flat-square&logo=linux&logoColor=white" alt="Linux" /></a>
  <a href="https://www.coursera.org/professional-certificates/google-cybersecurity"><img src="https://img.shields.io/badge/Study-Google%20Cybersecurity-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google Cybersecurity" /></a>
  <a href="https://www.linkedin.com/in/luiz-felipe-grochevski"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</div>

## Contents

- [About me](#about-me)
- [Technologies](#technologies)
- [Featured Projects](#featured-projects)
- [Goals](#goals)
- [Contact](#contact)

## About me

- 3+ years of hands-on experience developing and maintaining backend and mobile applications.
- Main stack: **Java, Spring Boot, Flutter/Dart, PostgreSQL, and REST APIs**.
- I build **Security Engineering tools in Rust**, exploring network scanning, SAST, API security, and honeypots.
- Software Engineering — Universidade Positivo.
- Google Cybersecurity Certificate — in progress.
- Particularly interested in backend systems, networking, asynchronous concurrency, and applied security.

## Technologies

| Category | Main | Developing |
| :--- | :--- | :--- |
| **Languages** | Java, Rust, Dart/Flutter | Python |
| **Frameworks** | Spring Boot, Quarkus, Flutter | FastAPI |
| **Fundamentals** | REST, TCP/IP, HTTP, Sockets | Async engineering |
| **Security** | OWASP Top 10, SAST, Nmap, SQLMap | AppSec, Enumeration |
| **Environment** | Linux, Git, Docker, Maven | Termux / Android |

## Featured Projects

My projects are organized around two main areas: **Network Security** and **Application Security**.

### 🌐 Network Security

```text
Sentinel-RS (scan) → netwatch-api (orchestrates) → cve-lookup (CVEs) → netwatch-dashboard (visualizes)
                             ↑
        traprs (attack detection, runs in parallel, feeds data via webhook)
```

- **[Sentinel-RS](https://github.com/LuizGrochevski/Sentinel-RS)** — Asynchronous Rust network scanner with TCP/UDP/SYN scanning, 64+ service fingerprints, TLS/JA3S, and Nmap XML.
- **[netwatch-api](https://github.com/LuizGrochevski/netwatch-api)** — FastAPI + JWT API that orchestrates Sentinel-RS.
- **[netwatch-dashboard](https://github.com/LuizGrochevski/netwatch-dashboard)** — React + Vite web dashboard for real-time scan visualization.
- **[cve-lookup](https://github.com/LuizGrochevski/cve-lookup)** — Python CLI for vulnerability lookup using NVD/CPE.
- **[traprs](https://github.com/LuizGrochevski/traprs)** — TCP honeypot for SSH/HTTP/HTTPS with real-time alerts.
- **[syswatch-tui](https://github.com/LuizGrochevski/syswatch-tui)** — Rust/Ratatui TUI dashboard for monitoring on Termux/Android.

### 🔐 Application Security

```text
javasast-rs / apisec-rs / secretscan-rs
                     ↓
Maven/Gradle plugins + insecure-java-lab
                     ↓
        JSON / Markdown / SARIF
```

- **[javasast-rs](https://github.com/LuizGrochevski/javasast-rs)** — Java SAST with 12 OWASP rules, SARIF, baseline support, and Maven/Gradle integration.
- **[javasast-maven-plugin](https://github.com/LuizGrochevski/javasast-maven-plugin)** — Maven plugin for running javasast-rs during the build.
- **[javasast-gradle-plugin](https://github.com/LuizGrochevski/javasast-gradle-plugin)** — Gradle plugin integrated with the `check` task.
- **[insecure-java-lab](https://github.com/LuizGrochevski/insecure-java-lab)** — Deliberately vulnerable Java application used for security testing.
- **[apisec-rs](https://github.com/LuizGrochevski/apisec-rs)** — API security testing based on OpenAPI specifications.
- **[secretscan-rs](https://github.com/LuizGrochevski/secretscan-rs)** — Secret detection in Git history using pattern matching and entropy analysis.

## Goals

Work as a **Backend Developer**, primarily with **Java/Spring Boot**, using Security Engineering as a technical differentiator while deepening my specialization in **AppSec and systems security**.

Open to **remote or hybrid opportunities**, in Brazil or internationally.

## Contact

<a href="https://br.linkedin.com/in/luiz-felipe-grochevski" target="_blank">
  <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://www.threads.com/@luiz.grochevski" target="_blank">
  <img src="https://img.shields.io/badge/-Threads-000000?style=for-the-badge&logo=threads&logoColor=white" alt="Threads" />
</a>
<a href="https://www.instagram.com/luiz.grochevski" target="_blank">
  <img src="https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
</a>
