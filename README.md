# Luiz Felipe de Mello Grochevski

Desenvolvedor **Backend** (Java/Spring Boot) e **Flutter**, com 3+ anos
de experiência em produção e um diferencial forte em Security Engineering.
<div align="center">
  <img src="https://img.shields.io/badge/OS-Linux-A81D33?style=flat-square&logo=linux&logoColor=white" alt="Linux OS" />
  <img src="https://img.shields.io/badge/Study-Google%20Cybersecurity-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google Cybersecurity" />
</div>

## 📌 Sobre mim

- 💼 3+ anos construindo e mantendo aplicações backend e mobile em
  produção (TX Fuel, Evo Sistemas, DIXI Soluções).
- 🛠️ Stack principal: Java, Spring Boot, Flutter/Dart, APIs REST,
  PostgreSQL, arquitetura de microsserviços.
- 🔐 Como diferencial, desenvolvo ferramentas próprias de segurança
  ofensiva/defensiva em Rust (scanner de rede, honeypot, CVE lookup,
  SAST, teste de API) — aplicando na prática o que estudo em AppSec
  e pentest.
- 🎓 Engenharia de Software (Universidade Positivo) + Google
  Cybersecurity Certificate em andamento.

## 🛠️ Tecnologias e Fundamentos

| Categoria | Tecnologias dominadas e em estudo |
| :--- | :--- |
| **Linguagens** | Rust, Java, Spring Boot, Python, JavaScript, Dart/Flutter |
| **Fundamentos** | Arquitetura TCP/IP, Sockets, Cabeçalhos HTTP, Modelo OSI, APIs REST |
| **Segurança** | Reconhecimento Ativo/Passivo, Enumeração, Banner Grabbing, Nmap, Gobuster, SQLMap, SAST, OWASP Top 10 |
| **Ambiente** | Linux (Terminal Avançado), Git/GitHub, Docker, Maven, Engenharia Assíncrona |

## 🚀 Projetos em Destaque

Dez projetos que formam um pipeline completo — do scan de rede ao relatório de vulnerabilidades de API e código, com detecção ativa de atacantes:

**Pipeline de auditoria de rede**
- **[Sentinel-RS](https://github.com/LuizGrochevski/Sentinel-RS)** 🛡️ → Scanner de rede assíncrono em Rust, com paralelismo via Tokio, SYN scanning, fingerprinting de serviços (64+ assinaturas), TLS fingerprinting via JA3S e exportação para Nmap XML.
- **[netwatch-api](https://github.com/LuizGrochevski/netwatch-api)** 🔌 → API REST em Python/FastAPI integrada ao sentinel-rs, com autenticação JWT, scan de portas em paralelo, persistência em SQLite e exportação de relatórios (CSV/Markdown), containerizada com Docker.
- **[cve-lookup](https://github.com/LuizGrochevski/cve-lookup)** 🔎 → CLI em Python para consulta de vulnerabilidades na NVD, com matching via CPE (`virtualMatchString`) e fallback para busca por keyword, severidade calculada por CVSS v3.1/v3.0/v2 e saída colorida em terminal.
- **[netwatch-dashboard](https://github.com/LuizGrochevski/netwatch-dashboard)** 🖥️ → Painel web em React + Vite para visualização de scans em tempo real, integrando Sentinel-RS, Netwatch-API e CVE Lookup num único fluxo — do scan de rede à vulnerabilidade conhecida, construído inteiramente em ambiente mobile (Termux).
- **[traprs](https://github.com/LuizGrochevski/traprs)** 🪤 → Honeypot TCP em Rust (SSH + HTTP + HTTPS) com dashboard WebSocket em tempo real, alertas por threshold, integração via webhook com a Netwatch-API e notificações no Telegram.
- **[syswatch-tui](https://github.com/LuizGrochevski/syswatch-tui)** 📊 → Dashboard de terminal em Rust (Ratatui/Crossterm) para monitoramento de CPU, memória, processos e rede, com coleta de métricas adaptada para ambientes Android/Termux.

**Pipeline de AppSec**
- **[apisec-rs](https://github.com/LuizGrochevski/apisec-rs)** 🔓 → Ferramenta em Rust que lê uma spec OpenAPI/Swagger e testa uma API real em busca de falhas: autenticação quebrada (OWASP API2) com requisições reais schema-válidas, IDOR/BOLA (OWASP API1), headers de segurança ausentes e rate limiting ausente — com exportação de relatório em JSON/Markdown.
- **[javasast-rs](https://github.com/LuizGrochevski/javasast-rs)** 🔍 → Ferramenta SAST em Rust para código Java: 12 regras de detecção (SQL injection, secrets hardcoded, deserialização insegura, criptografia fraca, path traversal, XXE, CORS permissivo, command injection, insecure random, TLS mal configurado, log de dado sensível, SSRF), varredura .gitignore-aware paralelizada, modo baseline, exportação SARIF/JSON/Markdown e 35 testes automatizados.
- **[javasast-maven-plugin](https://github.com/LuizGrochevski/javasast-maven-plugin)** 🔌 → Plugin Maven que roda o javasast-rs como parte do build, falhando o build automaticamente quando encontra vulnerabilidades acima da severidade configurada.
- **[insecure-java-lab](https://github.com/LuizGrochevski/insecure-java-lab)** 🧪 → Código Java deliberadamente vulnerável, usado como alvo de teste em tempo real para o javasast-rs e outras ferramentas SAST — cobre todas as 12 regras de detecção com exemplos reais.

## 🎯 Objetivo Atual

Atuar como **Backend Developer** (Java/Spring Boot e Flutter),
aplicando também conhecimentos de segurança ofensiva/defensiva como
diferencial técnico — cada projeto do pipeline serve como evidência
prática dessa combinação backend + security.

## 🤝 Contato

<a href="https://br.linkedin.com/in/luiz-felipe-grochevski" target="_blank">
  <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Luiz Felipe de Mello Grochevski" />
</a>

