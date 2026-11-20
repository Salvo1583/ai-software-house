<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=180&section=header&text=AI%20Software%20House&fontSize=40&fontColor=ffffff&fontAlignY=36&desc=A%20full%20software%20company%20made%20of%20AI%20agents&descSize=18&descAlignY=58" alt="AI Software House" width="100%" />
</p>

<p align="center"><b>🇬🇧 English</b> · <a href="README.it.md">🇮🇹 Italiano</a></p>

<p align="center">
  <img src="https://img.shields.io/badge/source-private-555555?style=for-the-badge&logo=github" alt="Source private" />
  <img src="https://img.shields.io/badge/project-showcase-36BCF7?style=for-the-badge" alt="Project showcase" />
</p>

> [!NOTE]
> This repository is a **project showcase**: the source code is private. A demo is available on request.

## 🧭 Overview

A **virtual software house** where every employee is an AI agent with a precise role: product owner, architect, developers, QA, security engineer, DPO, compliance officer and more.

Any request (a new app, a change to an existing project, or a simple question) goes through the same path as in a real company: **analysis → functional spec → development → controls → delivery**.

The guiding principle: today anyone can write code with AI. The difference is **how** it is written. Security and legal compliance have **veto power**: nothing ships until both are clean.

## ✨ Key features

- 👥 **21 specialized AI roles**, each with its own skills, tools and rules
- 🧭 **Smart routing**: a coordinator agent picks only the roles a request really needs, and writes down who was called and why
- 🛡️ **Mandatory controls** that can never be skipped: secret scanning on every commit, security review on auth and APIs, DPO on personal data, compliance on cookies, payments and AI features, accessibility on public UI
- 🧠 **Model per role**: Opus for high-risk decisions, Sonnet for everyday work, Haiku for repetitive tasks, with a minimum model enforced in code
- 🏢 **3D live dashboard**: a virtual office where you watch the agents work in real time
- ✅ **Built with TDD**: 400+ automated Python tests plus end-to-end browser tests

## 🏗️ How it works

```mermaid
flowchart TD
    R([Request]) --> C{Coordinator}
    C --> A[Analysis<br/>product · architecture · data]
    A --> S[Functional spec]
    S --> D[Development<br/>backend · frontend · mobile]
    D --> K{Controls}
    K -->|security · legal · QA| D
    K -->|all clear| OK([Delivery])
```

## 🧰 Tech stack

![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=claude&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Three.js](https://img.shields.io/badge/3D_dashboard-000000?style=flat&logo=threedotjs&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat)
![Gitleaks](https://img.shields.io/badge/Secret_scanning-gitleaks-red?style=flat)

## 📬 Contact

Built by **Salvatore Cutaia**, Computer Engineer specialized in AI agents & automations.

[![GitHub](https://img.shields.io/badge/GitHub-Salvo1583-181717?style=flat&logo=github)](https://github.com/Salvo1583)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Salvatore_Cutaia-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salvatore-cutaia-6047b0155/)
[![Website](https://img.shields.io/badge/Website-neuralform.it-111111?style=flat&logo=googlechrome&logoColor=white)](https://neuralform.it/)
