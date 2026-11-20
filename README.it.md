<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=180&section=header&text=AI%20Software%20House&fontSize=40&fontColor=ffffff&fontAlignY=36&desc=Una%20software%20house%20completa%20fatta%20di%20agenti%20AI&descSize=18&descAlignY=58" alt="AI Software House" width="100%" />
</p>

<p align="center"><a href="README.md">🇬🇧 English</a> · <b>🇮🇹 Italiano</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/codice-privato-555555?style=for-the-badge&logo=github" alt="Codice privato" />
  <img src="https://img.shields.io/badge/vetrina-progetto-36BCF7?style=for-the-badge" alt="Vetrina del progetto" />
</p>

> [!NOTE]
> Questo repository è una **vetrina del progetto**: il codice sorgente è privato. Una demo è disponibile su richiesta.

## 🧭 Panoramica

Una **software house virtuale** in cui ogni dipendente è un agente AI con un ruolo preciso: product owner, architetto, sviluppatori, QA, security engineer, DPO, compliance officer e altri.

Ogni richiesta (una nuova app, una modifica a un progetto esistente o una semplice domanda) segue lo stesso percorso di un'azienda vera: **analisi → specifica funzionale → sviluppo → controlli → consegna**.

Il principio guida: oggi chiunque scrive codice con l'AI. La differenza la fa **come** è scritto. Sicurezza e conformità legale hanno **potere di veto**: niente viene consegnato finché entrambe non sono a posto.

## ✨ Funzionalità principali

- 👥 **21 ruoli AI specializzati**, ognuno con le sue skill, i suoi strumenti e le sue regole
- 🧭 **Smistamento intelligente**: un agente coordinatore chiama solo i ruoli che servono davvero e scrive chi ha coinvolto e perché
- 🛡️ **Controlli obbligatori** che non si possono saltare: scansione dei segreti a ogni commit, revisione di sicurezza su autenticazione e API, DPO sui dati personali, compliance su cookie, pagamenti e funzioni AI, accessibilità sulle interfacce pubbliche
- 🧠 **Modello per ruolo**: Opus per le decisioni ad alto rischio, Sonnet per il lavoro di tutti i giorni, Haiku per i compiti ripetitivi, con un modello minimo imposto dal codice
- 🏢 **Dashboard 3D in tempo reale**: un ufficio virtuale in cui guardi gli agenti lavorare
- ✅ **Sviluppata con TDD**: oltre 400 test Python automatici più test end-to-end nel browser

## 🏗️ Come funziona

```mermaid
flowchart TD
    R([Richiesta]) --> C{Coordinatore}
    C --> A[Analisi<br/>prodotto · architettura · dati]
    A --> S[Specifica funzionale]
    S --> D[Sviluppo<br/>backend · frontend · mobile]
    D --> K{Controlli}
    K -->|sicurezza · legale · QA| D
    K -->|tutto ok| OK([Consegna])
```

## 🧰 Tecnologie

![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=claude&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Three.js](https://img.shields.io/badge/Dashboard_3D-000000?style=flat&logo=threedotjs&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat)
![Gitleaks](https://img.shields.io/badge/Scansione_segreti-gitleaks-red?style=flat)

## 📬 Contatti

Realizzato da **Salvatore Cutaia**, ingegnere informatico specializzato in agenti AI e automazioni.

[![GitHub](https://img.shields.io/badge/GitHub-Salvo1583-181717?style=flat&logo=github)](https://github.com/Salvo1583)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Salvatore_Cutaia-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salvatore-cutaia-6047b0155/)
[![Website](https://img.shields.io/badge/Website-neuralform.it-111111?style=flat&logo=googlechrome&logoColor=white)](https://neuralform.it/)
