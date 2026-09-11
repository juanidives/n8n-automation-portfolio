# n8n Automation Portfolio

**Português** · [English](README.en.md)

Automações construídas em n8n self-hosted por **Juan Antonio Morales**, profissional de Data & Analytics com 14 anos de trajetória em BI e gestão de projetos de dados. Cada projeto aqui é documentado como um case: o problema de negócio, a solução, a arquitetura, as integrações e o resultado, com o workflow pronto para importar.

## Projetos

| Projeto | Problema que resolve | Stack | Workflows |
|---|---|---|---|
| [**Automação de exercícios diários · Espanhol A1**](spanish-class-automation/) | Prática diária de idioma entre aulas semanais, com IA gerando o conteúdo e o professor aprovando em uma planilha | gpt-4o · Google Sheets · Google Drive · WhatsApp · ElevenLabs · GitHub Pages | 4 |
| [**UGC Video Factory**](ugc-video-factory/) | Vídeo curto no estilo UGC a partir de uma única foto enviada no Telegram | GPT-5.4 vision · AI Agents · Fal.ai · SeeDream 4.5 · Veo 3.1 · Telegram | 1 |

## Padrão de cada projeto

```
<projeto>/
├── README.md          ← case em português
├── README.en.md       ← case em inglês
├── workflows/         ← JSON sanitizado, pronto para importar no n8n
└── docs/              ← diagramas Mermaid e prints do canvas
```

- **Sanitização:** credenciais com nomes genéricos, IDs de instância removidos e placeholders `YOUR_…` no lugar de domínios, webhooks, planilhas e números de telefone.
- **Diagramas:** gerados a partir do bloco `connections` de cada JSON, então refletem exatamente o que está no workflow.
- **Importação:** cada README lista credenciais, placeholders e a ordem de ativação.

## Contato

[LinkedIn](https://www.linkedin.com/in/juanantoniomorales) · [GitHub](https://github.com/juanidives)
