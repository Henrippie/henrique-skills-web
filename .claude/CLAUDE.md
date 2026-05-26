# Henrique Skills Web

## Visão geral do projeto
Site de marketing para os 6 pacotes de skills Claude do Henrique Santos (@souhenriquesantos).
Marketplace editorial de skills curadas: Marketing Digital, SDR & Vendas, Produto de Ativação,
WhatsApp & Automação IA, Copywriting & Persuasão, IA para Mentorias.

---

## Stack técnica

| Camada | Tecnologia |
|--------|-----------|
| Framework | Next.js 15 App Router (TypeScript) |
| Estilo | Tailwind CSS v4 + shadcn/ui |
| Animações | Framer Motion |
| Componentes premium | 21st.dev (Magic MCP) |
| Deploy | Vercel (orgId: team_YpugW9kg4kQulXcgeQKEDADY) |
| Projeto Vercel | prj_aAjtpgiYtFxUIwyAyFFgSwAmxn0P |

---

## Design system

| Token | Valor |
|-------|-------|
| Background | `#050505` |
| Card | `#0d0d0d` |
| Border | `#1a1a1a` |
| Accent | `#7c3aed` (purple) |
| Accent light | `#a78bfa` |
| Green | `#22c55e` |
| Text | `#e8e8e8` |
| Text muted | `#555` |
| Mono font | SF Mono / Cascadia Code |

---

## Pacotes do site

| # | Slug | Página |
|---|------|--------|
| 01 | marketing-digital | /marketing-digital |
| 02 | sdr-vendas | /sdr-vendas |
| 03 | produto-ativacao | /produto-ativacao |
| 04 | whatsapp-automacao | /whatsapp-automacao |
| 05 | copywriting-persuasao | /copywriting-persuasao |
| 06 | ai-mentorias | /ai-mentorias |

---

## Estrutura de pastas (Next.js)

```
henrique-skills-web/
├── app/
│   ├── (marketing)/
│   │   ├── page.tsx            # Home — lista de pacotes
│   │   ├── marketing-digital/  # Página do pacote 01
│   │   ├── sdr-vendas/         # Página do pacote 02
│   │   ├── produto-ativacao/   # Página do pacote 03
│   │   ├── whatsapp-automacao/ # Página do pacote 04
│   │   ├── copywriting-persuasao/ # Pacote 05
│   │   └── ai-mentorias/       # Pacote 06
│   ├── reels/page.tsx          # Biblioteca de reels
│   ├── globals.css
│   └── layout.tsx
├── components/
│   ├── nav.tsx                 # Navbar fixed
│   ├── package-card.tsx        # Card de pacote
│   ├── skill-row.tsx           # Linha de skill com tier
│   └── footer.tsx              # Footer com foto
└── lib/
    └── packages.ts             # Data dos 6 pacotes
```

---

## Regras de desenvolvimento

1. Sempre usar App Router (não Pages Router)
2. Componentes com interatividade = `"use client"`
3. Server Components por padrão
4. shadcn/ui para componentes base
5. Framer Motion para animações de entrada
6. 21st.dev MCP para componentes premium de UI
7. Foto do Henrique: `public/assets/henrique-perfil.png`

---

## Comandos AIOX disponíveis

- `@architect` — decisões de arquitetura, tech stack, estrutura
- `@dev` — implementação de componentes e páginas
- `@ux` — design system, experiência do usuário, acessibilidade
- `@qa` — review de qualidade antes de deploy
- `@devops` — deploy na Vercel, configuração de domínio

## Comandos rápidos

- `/ui [descrição]` — gera componente premium via 21st.dev Magic MCP
- `*deploy` — deploy na Vercel via @devops

---

## Links importantes

- Site: https://henrique-skills-web.vercel.app
- Skills repo: https://github.com/souhenriquesantos/henrique-skills
- Instagram: @souhenriquesantos
- E-mail: blessadmarketing@gmail.com
