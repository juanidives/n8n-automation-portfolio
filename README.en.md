# n8n Automation Portfolio

[Português](README.md) · **English**

Automations built on self-hosted n8n by **Juan Antonio Morales**, a Data & Analytics professional with 14 years in BI and data project management. Each project is documented as a case: the business problem, the solution, the architecture, the integrations and the result, with the workflow ready to import.

## Projects

| Project | Problem it solves | Stack | Workflows |
|---|---|---|---|
| [**Daily Exercise Automation · Spanish A1**](spanish-class-automation/README.en.md) | Daily language practice between weekly lessons, with AI generating the content and the teacher approving it in a spreadsheet | gpt-4o · Google Sheets · Google Drive · WhatsApp · ElevenLabs · GitHub Pages | 4 |
| [**UGC Video Factory**](ugc-video-factory/README.en.md) | A short UGC-style video from a single photo sent on Telegram | GPT-5.4 vision · AI Agents · Fal.ai · SeeDream 4.5 · Veo 3.1 · Telegram | 1 |

## Project layout

```
<project>/
├── README.md          ← case in Portuguese
├── README.en.md       ← case in English
├── workflows/         ← sanitized JSON, ready to import into n8n
└── docs/              ← Mermaid diagrams and canvas screenshots
```

- **Sanitization:** generic credential names, instance IDs removed and `YOUR_…` placeholders for domains, webhooks, spreadsheets and phone numbers.
- **Diagrams:** generated from each JSON's `connections` block, so they mirror the workflow exactly.
- **Import:** each README lists credentials, placeholders and activation order.

## Contact

[LinkedIn](https://www.linkedin.com/in/juanantoniomorales) · [GitHub](https://github.com/juanidives)
