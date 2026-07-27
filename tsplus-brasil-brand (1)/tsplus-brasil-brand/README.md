# TSplus Brasil — Brand & Design System

Repositório de referência da identidade visual e de conteúdo da **TSplus Brasil**, subsidiária oficial da TSplus (acesso remoto, virtualização, segurança cibernética e monitoramento de servidores).

Este repositório serve como fonte para o **sistema de design no Claude Design**, garantindo que qualquer apresentação comercial, post de rede social, landing page ou material de vendas siga o mesmo padrão visual e de voz de marca.

## Estrutura

```
tsplus-brasil-brand/
├── 01-diretrizes/            → Guia oficial de arte e design (fundação de tudo)
├── 02-identidade-visual/      → Logos, paleta de cores e tipografia (tokens)
│   └── logos/                 → Variações do logotipo (a preencher)
├── 03-referencias-aprovadas/  → Peças reais já publicadas, aprovadas, no padrão atual
│   ├── dark-theme/            → Security, Monitoring, Remote Access
│   └── light-theme/           → Remote Support, Software Houses, mobilidade
├── 04-institucional/          → Quem somos, missão, visão, valores, produtos
├── 05-apresentacoes/          → Apresentações comerciais (comprimidas + revisadas)
└── 06-fontes/                 → Arquivos de fonte Red Hat Display (a preencher)
```

## Como usar no Claude Design

Ao configurar o sistema de design, aponte este repositório como fonte de código/referência.
Os arquivos em `03-referencias-aprovadas/` são o padrão visual mais atual e confiável —
priorize-os sobre a apresentação antiga em `05-apresentacoes/ACBR_Day_2024.pdf`,
que está desatualizada e será revisada. (Arquivo comprimido de 27,5 MB para 5,6 MB via
Ghostscript, mantendo a qualidade visual, para caber no limite de upload do GitHub.)

## Regras inegociáveis de marca (resumo rápido)

- Fonte única: **Red Hat Display**
- Grid: **55% texto / 45% visual** (50/50 em banners horizontais)
- Tema Dark (`#242424`) → Security, Monitoring, Remote Access
- Tema Light (branco/cinza claro) → Support, mobilidade, Software Houses
- Laranja `#ff9106`: glow difuso no dark, sólido em ícones/botões no light — **nunca fundo chapado**
- CTA sempre consultivo: "Fale com um consultor", "Teste grátis por 15 dias" — nunca "Compre agora"
- Logo: canto superior direito (ou topo-centro em Stories)
- Rodapé: `tsplusbrasil.com.br`
- Proibido: hacker cartunizado, monitor CRT, selos de desconto/Black Friday

Ver `01-diretrizes/DESIGN_AGENTES_tsplus.pdf` para o guia completo.
