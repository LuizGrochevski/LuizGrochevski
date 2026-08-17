# Luiz Felipe de Mello Grochevski

**Backend Developer** (Java/Spring Boot + Flutter) | Security Engineering  
3+ anos em produção • Ferramentas próprias de AppSec em Rust

> **TL;DR** — Desenvolvo backends robustos com foco em segurança aplicada e construo ferramentas de AppSec em Rust.

<div align="center">
  <a href="https://github.com/LuizGrochevski"><img src="https://img.shields.io/badge/OS-Linux-A81D33?style=flat-square&logo=linux&logoColor=white" alt="Linux" /></a>
  <a href="https://www.coursera.org/professional-certificates/google-cybersecurity"><img src="https://img.shields.io/badge/Study-Google%20Cybersecurity-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google Cybersecurity Certificate" /></a>
  <a href="https://github.com/LuizGrochevski?tab=repositories&q=java"><img src="https://img.shields.io/badge/Java-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Java Spring Boot" /></a>
  <a href="https://github.com/LuizGrochevski?tab=repositories&q=rust"><img src="https://img.shields.io/badge/Rust-Security%20Tools-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust Security Tools" /></a>
</div>

## Sumário

- [Sobre mim](#sobre-mim)
- [Tecnologias](#tecnologias)
- [Projetos em Destaque](#projetos-em-destaque)
- [Como rodar](#como-rodar)
- [Objetivo](#objetivo)
- [Contato](#contato)
- [Acessibilidade](#acessibilidade)
- [Licença](#licença)

## Sobre mim

- 3+ anos construindo e mantendo apps backend e mobile em produção (TX Fuel, Evo Sistemas, DIXI Soluções).
- Stack principal: **Java, Spring Boot, Flutter/Dart, PostgreSQL, APIs REST**.
- Diferencial: ferramentas de segurança ofensiva/defensiva em **Rust** (scanner de rede, SAST, API security, honeypot).
- Engenharia de Software (Universidade Positivo) + Google Cybersecurity Certificate (em andamento).

## Tecnologias

| Categoria | Dominadas | Em estudo / Uso frequente |
| :--- | :--- | :--- |
| **Linguagens** | Java, Dart/Flutter | Rust, Python |
| **Frameworks** | Spring Boot | Quarkus, FastAPI |
| **Fundamentos** | APIs REST, TCP/IP, HTTP, Sockets | Modelo OSI, Engenharia Assíncrona |
| **Segurança** | OWASP Top 10, SAST, Nmap, SQLMap | Banner Grabbing, Enumeração |
| **Ambiente** | Linux, Git, Docker, Maven | Termux / Android |

## Projetos em Destaque

Pipeline completo de auditoria e AppSec:

**Rede & Monitoramento**
- **[Sentinel-RS](https://github.com/LuizGrochevski/Sentinel-RS)** — Scanner assíncrono em Rust (TCP/UDP/SYN, fingerprinting 64+, TLS/JA3S, Nmap XML).
- **[netwatch-api](https://github.com/LuizGrochevski/netwatch-api)** — API FastAPI + JWT que orquestra o Sentinel-RS.
- **[traprs](https://github.com/LuizGrochevski/traprs)** — Honeypot TCP (SSH/HTTP/HTTPS) com alertas em tempo real.

**AppSec**
- **[javasast-rs](https://github.com/LuizGrochevski/javasast-rs)** — SAST para Java (12 regras OWASP, SARIF, baseline, plugins Maven/Gradle).
- **[apisec-rs](https://github.com/LuizGrochevski/apisec-rs)** — Testes de API a partir de OpenAPI (auth quebrada, IDOR, headers, rate limit).
- **[secretscan-rs](https://github.com/LuizGrochevski/secretscan-rs)** — Detecção de secrets (incluindo histórico git + entropia).

## Como rodar

Cada projeto tem instruções no próprio repositório. Exemplos rápidos:

```bash
# Ferramentas em Rust
cargo build --release

# netwatch-api (Docker + FastAPI)
# ver README do projeto
```

Links diretos:
- [Sentinel-RS](https://github.com/LuizGrochevski/Sentinel-RS#instalação)
- [javasast-rs](https://github.com/LuizGrochevski/javasast-rs#instalação)
- [apisec-rs](https://github.com/LuizGrochevski/apisec-rs#instalação)
- [secretscan-rs](https://github.com/LuizGrochevski/secretscan-rs#instalação)

## Objetivo

Atuar como **Backend Developer** (Java/Spring Boot e Flutter), aplicando Security Engineering como diferencial técnico. Aberto a oportunidades remotas ou híbridas.

## Contato

<a href="https://br.linkedin.com/in/luiz-felipe-grochevski" target="_blank">
  <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn de Luiz Felipe de Mello Grochevski" />
</a>

## Acessibilidade

- Headings semânticos e sumário para navegação por teclado/leitores de tela.
- Badges com `alt` descritivo.
- Links com texto significativo (não apenas “clique aqui”).
- Estrutura clara e escaneável para facilitar leitura.

## Licença

Projetos educacionais e open-source. Consulte o arquivo `LICENSE` de cada repositório (recomendado: MIT).
