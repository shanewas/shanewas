![Shanewas Ahmed — backend systems engineer, Miyazaki, Japan](assets/banner.png)

**Backend systems engineer at 株式会社スカイコム (SkyCom), R&D センター宮崎.** C++, C#, and Linux.

[![Portfolio](https://img.shields.io/badge/portfolio-shanewas.github.io-0ea5e9?style=flat-square)](https://shanewas.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ahmedshanewas-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahmedshanewas)
[![X](https://img.shields.io/badge/X-@S__A__Nabil-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/S_A_Nabil)
[![Email](https://img.shields.io/badge/email-shanewasahmed@gmail.com-ef4444?style=flat-square)](mailto:shanewasahmed@gmail.com)
[![Open to work](https://img.shields.io/badge/open%20to-Senior%20%2F%20Lead%20·%20Tokyo%20or%20remote-10b981?style=flat-square)](mailto:shanewasahmed@gmail.com)

My day job is SkyPDF: low-level PDF parsing and cryptographic signing in C++ and C# on RHEL, along with the WebAPI, RPM packaging, and CI/CD wrapped around it. Chasing down a single API bottleneck doubled throughput in production. The My Number Card signing work turned into a patent, filed jointly with SkyCom in 2025.

Outside of that I build automation that has to survive the open internet, which in practice means anti-bot systems and agents that run unattended for hours. Several of those are packaged and public rather than sitting in a private repo, so you can read the source and install them from PyPI, npm or NuGet.

Currently on a Japan Engineer visa in Miyazaki, looking for senior or lead backend, platform, or automation work in Tokyo or remote.

## Shipped

| Project | | What it is |
|---|---|---|
| **[agentic-stealth-browser](https://github.com/shanewas/agentic-stealth-browser)** | [![PyPI](https://img.shields.io/pypi/v/agentic-stealth-browser?style=flat-square&label=)](https://pypi.org/project/agentic-stealth-browser/) | Stealth browser automation for autonomous agents, on Playwright. Coherent fingerprints across TLS, navigator, WebGL and Canvas; behaviour simulation; block detection with recovery; an MCP server so agents drive it directly. MIT. |
| **[edge-agent-bridge](https://github.com/shanewas/edge-agent-bridge)** | [![PyPI](https://img.shields.io/pypi/v/edge-agent-bridge?style=flat-square&label=)](https://pypi.org/project/edge-agent-bridge/) | Drives the Edge tab you already have open, so logged-in sessions, enterprise VPNs and saved credentials survive. CDP events over a local RFC 6455 WebSocket, P50 round trip 9.09 ms, batching 50 actions runs 7.9× faster than firing them one at a time. Binds to 127.0.0.1:18999 only, no telemetry, no dependencies beyond Python 3.10. MIT. |
| **[GhostScrape](https://ghostscrape.online)** | live | The hosted API built on that engine. FastAPI with key auth, usage metering and quota billing, PostgreSQL 16 behind Alembic, rotating proxies, deployed on hardened Linux under systemd and a Cloudflare Tunnel. |
| **[posix-ipc-dotnet](https://github.com/shanewas/posix-ipc-dotnet)** | [![NuGet](https://img.shields.io/nuget/v/Shanewas.PosixIpc?style=flat-square&label=)](https://www.nuget.org/packages/Shanewas.PosixIpc/) | System V shared memory and semaphores for .NET on Linux (x64, glibc). No native payload, just P/Invoke into libc, for low-latency IPC between processes on one host. Targets .NET 6 and 8. MIT. |
| **[engram](https://github.com/shanewas/engram)** | | Memory for coding agents where a private git repo *is* the store and the audit log. Every fact is an attributed, revertible commit; no database, no service. Session hooks sync it across machines. |
| **[@shanewas/form-validation](https://github.com/shanewas/ValidationEngine)** | [![npm](https://img.shields.io/npm/v/@shanewas/form-validation?style=flat-square&label=)](https://www.npmjs.com/package/@shanewas/form-validation) | Rule-driven form validation for Node and the browser: cross-field dependencies, conditional rules, custom validators, per-field error reporting. Written for PDF form data originally. GPL-3.0. |
| **[ats-resume-analyzer](https://github.com/shanewas/ats-resume-analyzer)** | | Scores a CV the way an applicant tracking system would: keyword matching, skill-gap detection, targeted rewrites. |
| **SkyPDF** | proprietary | The day job. C++/C# PDF and signing infrastructure on RHEL, running in enterprise document workflows. |

Smaller things that might be useful: [rpm-package](https://github.com/shanewas/rpm-package) (RPM packaging reference), [tunnelfox](https://github.com/shanewas/tunnelfox), [oci-defender](https://github.com/shanewas/oci-defender), [StructProbe](https://github.com/shanewas/StructProbe).

## Experience

**株式会社スカイコム (SkyCom Corporation)** — Software Engineer II → I · 2022 – present · Miyazaki, Japan  
Core developer on SkyPDF, the low-level PDF library and cryptographic signing infrastructure, in C++ and C# on RHEL. Designed the WebAPI surface for signing, rendering and conversion. Built the RPM packaging and CI/CD pipeline. Resolved a critical API bottleneck for a 2× throughput gain in production, and filed [JP 2025-169170 A](https://www.j-platpat.inpit.go.jp/) on electronic signatures using the My Number Card. Promoted to Grade I in April 2026.

**Ferntech Solutions** — Software Architect & Project Manager · 2019 – 2021 · Bangladesh  
Architected AIW Core, a hyper-automation platform deployed to major banks, then built the automation studio over it for desktop (Electron) and web against one shared engine. Led a five-person team through the full delivery lifecycle.

**Neonsofts** — Co-founder & Lead Developer · 2014 – 2017 · Bangladesh  
Started it while at BRAC University. ERP systems and Unity3D game prototypes for clients.

## Credentials

**Patent** · [JP 2025-169170 A](https://www.j-platpat.inpit.go.jp/) — Electronic signature system using the My Number Card. Japan Patent Office, filed 2025 with 株式会社スカイコム.

**Publications** · [Alzheimer's prediction via CNN on OCT retinal images](https://ieeexplore.ieee.org/document/9306649) (IEEE, 2019) · Arduino crop and fertilizer recommendation system (East West University Journal, 2018)

**Hackathon** · 1st place, National Hackathon, IDEB Bangladesh (2014)

## Stack

**Systems** C++ · C# / .NET Core · RHEL · systemd · RPM · P/Invoke · Docker  
**Backend** FastAPI · Node.js · PostgreSQL · Redis · SQLite · REST  
**Automation & AI** Playwright · MCP · autonomous agents · multi-agent orchestration · NLP  
**Also** Python · TypeScript · React · Bash · GitHub Actions

## Education

**BSc Computer Science** · BRAC University, Dhaka · 2013 – 2019  
**B-JET Advanced Course** · University of Miyazaki · 2021 – 2022  
**Microsoft Student Partner** · 2013 – 2016
