<p align="center">
  <img src="assets/banner-pt.svg" alt="n8n Automation Portfolio — Automações com IA documentadas como cases de negócio" width="100%"/>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT"/></a>
  <img src="https://img.shields.io/badge/n8n-2.x_self--hosted-051221?style=flat&logo=n8n&logoColor=EA4B71" alt="n8n 2.x self-hosted"/>
  <img src="https://img.shields.io/badge/cases-2-051221?style=flat" alt="2 cases"/>
  <img src="https://img.shields.io/badge/workflows-5-051221?style=flat" alt="5 workflows"/>
  <img src="https://img.shields.io/badge/n%C3%B3s-61-051221?style=flat" alt="61 nós"/>
  <img src="https://img.shields.io/badge/docs-PT_%7C_EN-051221?style=flat" alt="Docs PT | EN"/>
</p>

<p align="center">
  <b>Português</b> · <a href="README.en.md">English</a>
</p>

---

## 👋 Sobre este repositório

Este é o meu portfólio de automações em **n8n self-hosted**. Cada pasta é um case completo: o problema de negócio, a solução em uma frase, a arquitetura, as integrações, o resultado e o workflow pronto para importar.

Venho de 14 anos em BI e gestão de projetos de dados, e trago essa lente para a automação: começo pelo processo e pelo dado, desenho o fluxo com pontos de controle claros e documento cada decisão para que outra pessoa consiga operar, auditar e evoluir a solução.

---

## 🚀 Cases

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="spanish-class-automation/README.md">
        <img src="spanish-class-automation/docs/canvas-2-enviar-exercicio.png" alt="Canvas n8n do envio diário de exercícios"/>
      </a>
      <h3>📚 Exercícios diários · Espanhol A1</h3>
      <p>Da aula da semana a 9 exercícios gerados com IA, aprovados pelo professor numa planilha e entregues um por dia no WhatsApp da turma, com desafio web, áudio narrado e registro anônimo das respostas.</p>
      <p><b>4 workflows · 39 nós · em uso desde ago/2026</b></p>
      <p>
        <img src="https://img.shields.io/badge/OpenAI-gpt--4o-051221?style=flat&logo=openai" alt="OpenAI"/>
        <img src="https://img.shields.io/badge/Google_Sheets-051221?style=flat&logo=googlesheets" alt="Google Sheets"/>
        <img src="https://img.shields.io/badge/WhatsApp-051221?style=flat&logo=whatsapp" alt="WhatsApp"/>
        <img src="https://img.shields.io/badge/ElevenLabs-051221?style=flat&logo=elevenlabs" alt="ElevenLabs"/>
        <img src="https://img.shields.io/badge/GitHub_Pages-051221?style=flat&logo=githubpages" alt="GitHub Pages"/>
      </p>
      <p><a href="spanish-class-automation/README.md"><b>Ler o case →</b></a> &nbsp;·&nbsp; <a href="spanish-class-automation/README.en.md">English</a> &nbsp;·&nbsp; <a href="spanish-class-automation/workflows/">JSON</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="ugc-video-factory/README.md">
        <img src="ugc-video-factory/docs/canvas-ugc-factory-hub.png" alt="Canvas n8n do UGC Video Factory"/>
      </a>
      <h3>🎬 UGC Video Factory</h3>
      <p>Uma foto e uma legenda no Telegram viram um vídeo vertical de 8 segundos no estilo UGC, com fala em português: análise visual, agentes de prompt e geração de imagem e vídeo em filas assíncronas.</p>
      <p><b>1 workflow · 22 nós · projeto de formação</b></p>
      <p>
        <img src="https://img.shields.io/badge/OpenAI-GPT--5.4_vision-051221?style=flat&logo=openai" alt="OpenAI"/>
        <img src="https://img.shields.io/badge/AI_Agents-051221?style=flat" alt="AI Agents"/>
        <img src="https://img.shields.io/badge/Fal.ai-SeeDream_%C2%B7_Veo_3.1-051221?style=flat" alt="Fal.ai"/>
        <img src="https://img.shields.io/badge/Telegram-051221?style=flat&logo=telegram" alt="Telegram"/>
      </p>
      <p><a href="ugc-video-factory/README.md"><b>Ler o case →</b></a> &nbsp;·&nbsp; <a href="ugc-video-factory/README.en.md">English</a> &nbsp;·&nbsp; <a href="ugc-video-factory/workflows/">JSON</a></p>
    </td>
  </tr>
</table>

---

## 🧭 O que estes cases demonstram

| Competência | Onde aparece |
|---|---|
| **IA com humano no circuito** | A IA gera a semana e o professor aprova na planilha; o envio considera apenas o que foi aprovado · *Espanhol* |
| **Engenharia de prompt** | Regras explícitas, contraexemplos, saída em JSON e Structured Output Parser · *Espanhol, UGC* |
| **Orquestração multimodal** | Visão computacional, texto, imagem, vídeo e áudio no mesmo fluxo · *UGC, Espanhol* |
| **Integração com APIs** | Google Drive e Sheets, WhatsApp, Telegram, GitHub, ElevenLabs e Fal.ai · *ambos* |
| **Padrões assíncronos** | Fila → consulta de status → busca do resultado, com espera controlada · *UGC, Espanhol* |
| **Dados com privacidade** | Respostas anônimas viram base de acertos por pergunta e por semana · *Espanhol* |
| **Operação** | Retentativas, fuso horário explícito, chave geral de pausa e alerta de erro no WhatsApp · *Espanhol* |
| **Governança e documentação** | JSON sanitizado, log de sanitização, diagramas gerados a partir das conexões · *ambos* |

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

## 🗂️ Estrutura

```
n8n-automation-portfolio/
├── README.md · README.en.md        ← esta vitrine
├── LICENSE                         ← MIT
├── assets/                         ← banner do repositório
│
├── spanish-class-automation/       ← um case por pasta
│   ├── README.md · README.en.md    ← case completo em PT e EN
│   ├── workflows/                  ← JSON sanitizado, pronto para importar
│   └── docs/
│       ├── canvas-*.png            ← prints do canvas no n8n
│       ├── diagramas/              ← diagramas Mermaid (.mmd + .png)
│       └── diagramas-workflows.md  ← diagrama nó a nó de cada workflow
│
└── ugc-video-factory/              ← mesma estrutura
```

---

## ⚡ Como importar um workflow

1. No n8n, abra **Workflows → Import from File** e selecione o JSON na pasta `workflows/` do case.
2. Crie as credenciais listadas no README do case e selecione cada uma nos nós correspondentes.
3. Troque os placeholders `YOUR_…` pelos seus valores (planilha, domínio, número, repositório).
4. Ative o workflow.

Cada README de case traz a lista completa de credenciais, placeholders, community nodes e a ordem de ativação.

---

## 🔒 Padrão de publicação

Todo workflow passa pelo mesmo tratamento antes de entrar aqui:

- **Credenciais** com nomes genéricos e ID placeholder, prontas para você associar as suas.
- **Identificadores da instância** removidos: `id`, `versionId`, `meta.instanceId`, `pinData` e workflow de erro.
- **Placeholders `YOUR_…`** no lugar de domínio, paths de webhook, IDs de planilha e Drive, números de telefone e repositórios.
- **webhookIds regenerados**, para que cada importação crie URLs próprias.
- **Diagramas gerados a partir do bloco `connections`** do JSON, então refletem exatamente o que está no workflow.

---

## 📄 Licença

Distribuído sob a licença [MIT](LICENSE): use, adapte e distribua livremente, mantendo o aviso de copyright.

---

## 👤 Autor

**Juan Antonio Morales** · PM & Lead BI · Data & Analytics · AI Automation

14 anos em Data & Analytics na Arcos Dorados (McDonald's LATAM), liderando BI e projetos de dados em escala regional, incluindo a automação do P&L de 12 mercados no Databricks com redução de 63% nos processos manuais. Hoje construo agentes e automações de IA em produção pela [Kailor](https://kailor.com.br).

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juanantoniomorales)
[![GitHub](https://img.shields.io/badge/GitHub-juanidives-181717?style=flat-square&logo=github)](https://github.com/juanidives)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:juan.morales@outlook.com.br)

---

<p align="center">
  <sub>Construído em São Paulo com n8n, dados e curiosidade · Argentina e Brasil sempre no coração</sub>
</p>
