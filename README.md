# Luiz Felipe de Mello Grochevski

Desenvolvedor focado em **Backend** e em transição estratégica para **Cybersecurity**, com foco em **Pentest**, **AppSec** e ferramentas de automação de rede.
<div align="center">
  <img src="https://img.shields.io/badge/OS-Linux-A81D33?style=flat-square&logo=linux&logoColor=white" alt="Linux OS" />
  <img src="https://img.shields.io/badge/Study-Google%20Cybersecurity-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google Cybersecurity" />
</div>

## 📌 Sobre mim

- 🎯 Desenvolvendo ferramentas robustas de segurança cibernética e automação com **Rust** e **Tokio Async**.
- 🔐 Estudando **segurança ofensiva**, **pentest** e **AppSec** através de laboratórios práticos e desafios reais.
- 🎓 Atualmente cursando Engenharia de Software e o **Google Cybersecurity Certificate**.
- 🌐 Sólidos conhecimentos em arquitetura de redes, análise de tráfego, enumeração de portas e comportamento de protocolos.

## 🛠️ Tecnologias e Fundamentos

| Categoria | Tecnologias dominadas e em estudo |
| :--- | :--- |
| **Linguagens** | Rust, Java, Spring Boot, Python, JavaScript, Dart/Flutter |
| **Fundamentos** | Arquitetura TCP/IP, Sockets, Cabeçalhos HTTP, Modelo OSI, APIs REST |
| **Segurança** | Reconhecimento Ativo/Passivo, Enumeração, Banner Grabbing, Nmap, Gobuster, SQLMap |
| **Ambiente** | Linux (Terminal Avançado), Git/GitHub, Docker, Engenharia Assíncrona |

## 🚀 Projetos em Destaque

Oito projetos que formam um pipeline completo — do scan de rede ao relatório de vulnerabilidades de API e código, com detecção ativa de atacantes:

**Pipeline de auditoria de rede**
- **[Sentinel-RS](https://github.com/LuizGrochevski/Sentinel-RS)** 🛡️ → Scanner de rede assíncrono em Rust, com paralelismo via Tokio, SYN scanning, fingerprinting de serviços (64+ assinaturas), TLS fingerprinting via JA3S e exportação para Nmap XML.
- **[netwatch-api](https://github.com/LuizGrochevski/netwatch-api)** 🔌 → API REST em Python/FastAPI integrada ao sentinel-rs, com autenticação JWT, scan de portas em paralelo, persistência em SQLite e exportação de relatórios (CSV/Markdown), containerizada com Docker.
- **[cve-lookup](https://github.com/LuizGrochevski/cve-lookup)** 🔎 → CLI em Python para consulta de vulnerabilidades na NVD, com matching via CPE (`virtualMatchString`) e fallback para busca por keyword, severidade calculada por CVSS v3.1/v3.0/v2 e saída colorida em terminal.
- **[netwatch-dashboard](https://github.com/LuizGrochevski/netwatch-dashboard)** 🖥️ → Painel web em React + Vite para visualização de scans em tempo real, integrando Sentinel-RS, Netwatch-API e CVE Lookup num único fluxo — do scan de rede à vulnerabilidade conhecida, construído inteiramente em ambiente mobile (Termux).
- **[traprs](https://github.com/LuizGrochevski/traprs)** 🪤 → Honeypot TCP em Rust (SSH + HTTP + HTTPS) com dashboard WebSocket em tempo real, alertas por threshold, integração via webhook com a Netwatch-API e notificações no Telegram.
- **[syswatch-tui](https://github.com/LuizGrochevski/syswatch-tui)** 📊 → Dashboard de terminal em Rust (Ratatui/Crossterm) para monitoramento de CPU, memória, processos e rede, com coleta de métricas adaptada para ambientes Android/Termux.

**Pipeline de AppSec**
- **[apisec-rs](https://github.com/LuizGrochevski/apisec-rs)** 🔓 → Ferramenta em Rust que lê uma spec OpenAPI/Swagger e testa uma API real em busca de falhas: autenticação quebrada (OWASP API2) com requisições reais schema-válidas, IDOR/BOLA (OWASP API1), headers de segurança ausentes e rate limiting ausente — com exportação de relatório em JSON/Markdown.
- **[javasast-rs](https://github.com/LuizGrochevski/javasast-rs)** 🔍 → Ferramenta SAST em Rust para código Java: 7 regras de detecção (SQL injection, secrets hardcoded, deserialização insegura, criptografia fraca, path traversal, XXE, CORS permissivo), varredura .gitignore-aware, supressão inline e exit code configurável para uso em CI.

## 🎯 Objetivo Atual

Consolidar um posicionamento como **Security Software Engineer** — combinando backend robusto (FastAPI, Rust assíncrono, Spring Boot) com ferramentas de auditoria ofensiva/defensiva próprias que cobrem tanto rede quanto aplicação (APIs e código-fonte), cada projeto servindo como evidência prática dessa transição de Backend Developer para AppSec/Security Engineering.

## 🤝 Contato

<a href="https://br.linkedin.com/in/luiz-felipe-grochevski" target="_blank">
  <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Luiz Felipe de Mello Grochevski" />
</a>
