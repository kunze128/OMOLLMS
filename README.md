# OMOLLMS
Offline Multi Open-source Large Language Model System. A system to input a prompt and let 5 LLMs to generate code for it, improve it, test it and update it. Made for Linux Fedora 41

huggingface-offline-ai/
├── app/
│   ├── api/
│   │   ├── autonomous-ai/
│   │   │   ├── artifact/
│   │   │   │   └── route.ts
│   │   │   ├── download/
│   │   │   │   └── route.ts
│   │   │   └── route.ts
│   │   └── check-token/
│   │       └── route.ts
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── job-status.tsx
│   ├── model-info.tsx
│   └── ui/
│       ├── button.tsx
│       ├── card.tsx
│       └── ... (other UI components)
├── lib/
│   ├── agents/
│   │   ├── agent-definitions.ts
│   │   ├── orchestration-service.ts
│   │   └── types.ts
│   ├── llm/
│   │   ├── inference-engine.ts
│   │   ├── local-models.ts
│   │   └── model-manager.ts
│   └── utils.ts
├── models/
│   └── .gitkeep
├── public/
│   └── favicon.ico
├── scripts/
│   ├── download-models.sh
│   └── setup-offline.sh
├── .env.example
├── .gitignore
├── next.config.js
├── package.json
├── README.md
└── tsconfig.json
