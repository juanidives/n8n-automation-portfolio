<p align="center">
  <img src="assets/banner-en.svg" alt="n8n Automation Portfolio — AI automations documented as business cases" width="100%"/>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT"/></a>
  <img src="https://img.shields.io/badge/n8n-2.x_self--hosted-051221?style=flat&logo=n8n&logoColor=EA4B71" alt="n8n 2.x self-hosted"/>
  <img src="https://img.shields.io/badge/cases-2-051221?style=flat" alt="2 cases"/>
  <img src="https://img.shields.io/badge/workflows-5-051221?style=flat" alt="5 workflows"/>
  <img src="https://img.shields.io/badge/nodes-61-051221?style=flat" alt="61 nodes"/>
  <img src="https://img.shields.io/badge/docs-PT_%7C_EN-051221?style=flat" alt="Docs PT | EN"/>
</p>

<p align="center">
  <a href="README.md">Português</a> · <b>English</b>
</p>

---

## 👋 About this repository

This is my portfolio of automations built on **self-hosted n8n**. Each folder is a complete case: the business problem, the one-sentence solution, the architecture, the integrations, the result and the workflow ready to import.

As a Data Project Manager, I bring to automation the same lens I used leading Data & Analytics in multi-market environments: I start from the process and the data, design the flow with clear control points, and document every decision so someone else can operate, audit and evolve the solution.

---

## 🚀 Cases

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="spanish-class-automation/README.en.md">
        <img src="spanish-class-automation/docs/canvas-2-enviar-exercicio.png" alt="n8n canvas of the daily exercise sender"/>
      </a>
      <h3>📚 Daily Exercises · Spanish A1</h3>
      <p>From the week's lesson to 9 AI-generated exercises, approved by the teacher in a spreadsheet and delivered one per day to the class WhatsApp group, with a web challenge, narrated audio and anonymous answer logging.</p>
      <p><b>4 workflows · 39 nodes · in use since Aug 2026</b></p>
      <p>
        <img src="https://img.shields.io/badge/OpenAI-gpt--4o-051221?style=flat&logo=openai" alt="OpenAI"/>
        <img src="https://img.shields.io/badge/Google_Sheets-051221?style=flat&logo=googlesheets" alt="Google Sheets"/>
        <img src="https://img.shields.io/badge/WhatsApp-051221?style=flat&logo=whatsapp" alt="WhatsApp"/>
        <img src="https://img.shields.io/badge/ElevenLabs-051221?style=flat&logo=elevenlabs" alt="ElevenLabs"/>
        <img src="https://img.shields.io/badge/GitHub_Pages-051221?style=flat&logo=githubpages" alt="GitHub Pages"/>
      </p>
      <p><a href="spanish-class-automation/README.en.md"><b>Read the case →</b></a> &nbsp;·&nbsp; <a href="spanish-class-automation/README.md">Português</a> &nbsp;·&nbsp; <a href="spanish-class-automation/workflows/">JSON</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="ugc-video-factory/README.en.md">
        <img src="ugc-video-factory/docs/canvas-ugc-factory-hub.png" alt="n8n canvas of UGC Video Factory"/>
      </a>
      <h3>🎬 UGC Video Factory</h3>
      <p>A photo and a caption on Telegram become an 8-second vertical UGC-style video with a spoken line in Portuguese: visual analysis, prompt agents, and image and video generation through async queues.</p>
      <p><b>1 workflow · 22 nodes · training project</b></p>
      <p>
        <img src="https://img.shields.io/badge/OpenAI-GPT--5.4_vision-051221?style=flat&logo=openai" alt="OpenAI"/>
        <img src="https://img.shields.io/badge/AI_Agents-051221?style=flat" alt="AI Agents"/>
        <img src="https://img.shields.io/badge/Fal.ai-SeeDream_%C2%B7_Veo_3.1-051221?style=flat" alt="Fal.ai"/>
        <img src="https://img.shields.io/badge/Telegram-051221?style=flat&logo=telegram" alt="Telegram"/>
      </p>
      <p><a href="ugc-video-factory/README.en.md"><b>Read the case →</b></a> &nbsp;·&nbsp; <a href="ugc-video-factory/README.md">Português</a> &nbsp;·&nbsp; <a href="ugc-video-factory/workflows/">JSON</a></p>
    </td>
  </tr>
</table>

---

## 🧭 What these cases demonstrate

| Skill | Where it shows |
|---|---|
| **Human-in-the-loop AI** | AI generates the week and the teacher approves it in the spreadsheet; delivery picks up only approved rows · *Spanish* |
| **Prompt engineering** | Explicit rules, counter-examples, JSON output and Structured Output Parser · *Spanish, UGC* |
| **Multimodal orchestration** | Vision, text, image, video and audio in the same flow · *UGC, Spanish* |
| **API integration** | Google Drive and Sheets, WhatsApp, Telegram, GitHub, ElevenLabs and Fal.ai · *both* |
| **Async patterns** | Queue → status check → fetch result, with controlled waits · *UGC, Spanish* |
| **Privacy-aware data** | Anonymous answers become a per-question, per-week accuracy base · *Spanish* |
| **Operations** | Retries, explicit timezone, a global pause switch and WhatsApp error alerts · *Spanish* |
| **Governance and documentation** | Sanitized JSON, sanitization log, diagrams generated from the connections · *both* |

---

## 🛠️ Stack

[![n8n](https://img.shields.io/badge/n8n-051221?style=flat&logo=n8n)](https://n8n.io)
[![OpenAI](https://img.shields.io/badge/OpenAI-051221?style=flat&logo=openai)](https://openai.com)
[![Google Sheets](https://img.shields.io/badge/Google_Sheets-051221?style=flat&logo=googlesheets)](https://workspace.google.com/products/sheets/)
[![Google Drive](https://img.shields.io/badge/Google_Drive-051221?style=flat&logo=googledrive)](https://workspace.google.com/products/drive/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp_%28Evolution_API%29-051221?style=flat&logo=whatsapp)](https://github.com/EvolutionAPI/evolution-api)
[![Telegram](https://img.shields.io/badge/Telegram-051221?style=flat&logo=telegram)](https://core.telegram.org/bots)
[![ElevenLabs](https://img.shields.io/badge/ElevenLabs-051221?style=flat&logo=elevenlabs)](https://elevenlabs.io)
[![Fal.ai](https://img.shields.io/badge/Fal.ai-051221?style=flat)](https://fal.ai)
[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-051221?style=flat&logo=githubpages)](https://pages.github.com)
[![JavaScript](https://img.shields.io/badge/JavaScript-051221?style=flat&logo=javascript)](https://developer.mozilla.org/docs/Web/JavaScript)
[![Mermaid](https://img.shields.io/badge/Mermaid-051221?style=flat&logo=mermaid)](https://mermaid.js.org)

---

## 🗂️ Structure

```
n8n-automation-portfolio/
├── README.md · README.en.md        ← this showcase
├── LICENSE                         ← MIT
├── assets/                         ← repository banner
│
├── spanish-class-automation/       ← one case per folder
│   ├── README.md · README.en.md    ← full case in PT and EN
│   ├── workflows/                  ← sanitized JSON, ready to import
│   └── docs/
│       ├── canvas-*.png            ← n8n canvas screenshots
│       ├── diagramas/              ← Mermaid diagrams (.mmd + .png)
│       └── diagramas-workflows.md  ← node-level diagram of each workflow
│
└── ugc-video-factory/              ← same structure
```

---

## ⚡ How to import a workflow

1. In n8n, open **Workflows → Import from File** and pick the JSON from the case's `workflows/` folder.
2. Create the credentials listed in the case README and select each one in the matching nodes.
3. Replace the `YOUR_…` placeholders with your own values (spreadsheet, domain, phone number, repository).
4. Activate the workflow.

Each case README lists every credential, placeholder, community node and the activation order.

---

## 🔒 Publishing standard

Every workflow goes through the same treatment before it lands here:

- **Credentials** with generic names and placeholder IDs, ready for you to attach your own.
- **Instance identifiers** removed: `id`, `versionId`, `meta.instanceId`, `pinData` and error workflow.
- **`YOUR_…` placeholders** for domain, webhook paths, spreadsheet and Drive IDs, phone numbers and repositories.
- **Regenerated webhookIds**, so each import creates its own URLs.
- **Diagrams generated from the JSON `connections` block**, so they mirror the workflow exactly.

---

## 📄 License

Released under the [MIT](LICENSE) license: use, adapt and distribute freely, keeping the copyright notice.

---

## 👤 Author

**Juan Antonio Morales**  
Data Project Manager | Data & Analytics · BI · Portfolio Management | Squad Leadership & LATAM Rollout | Databricks · Power BI · Generative AI

I led the Data & Analytics agenda for Arcos Dorados' (McDonald's) Latin American operations, heading cross-functional squads across C-level sponsored programs with rollout in up to 12 markets. Highlights include the Segment P&L across 12 markets, cutting manual processes by 63%, and the Meu Méqui loyalty program, from pilot to rollout across 11 markets.

Today I apply the same logic to Generative AI, building AI agents and automations that run in production at [Kailor](https://kailor.com.br), while pursuing an MBA in Project Management at FGV.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juanantoniomorales)
[![GitHub](https://img.shields.io/badge/GitHub-juanidives-181717?style=flat-square&logo=github)](https://github.com/juanidives)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:juan.morales@outlook.com.br)

---

<p align="center">
  <sub>Built in São Paulo with n8n, data and curiosity · Argentina and Brazil always at heart</sub>
</p>
