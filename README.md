# marketing-skills v3.0.0 (plugin Claude Code)

Plugin ufficiale che pacchettizza tutte le **59 skill** di marketing per essere installato su **Claude Code / Cowork** via marketplace.

- **Repo git remoto**: https://github.com/mattarna/marketing-skills-plugin
- **Branch**: `main`
- **Versione**: 3.0.0

---

## Novità v3.0.0

- **Orchestratore (M0)**: skill centrale che instrada richieste ampie/ambigue alla skill giusta, identifica catene multi-skill, e arricchisce l'esecuzione con la knowledge base
- **Knowledge Base Hormozi/Fladlien**: 8 file di riferimento estratti da 7 episodi Hormozi + 1 masterclass Fladlien, bundled dentro l'orchestratore come risorse condivise
- **2 nuove skill**: F3 (Affiliate/Referral Program), E4b (Re-engagement Challenge)
- **Skill totali**: da 56 a 59

---

## Cosa contiene

```
marketing-skills-plugin/
├── README.md
├── .claude-plugin/
│   ├─�� plugin.json
│   └── marketplace.json
└── skills/
    ├── skill-a1-icp-positioning/SKILL.md
    ├���─ skill-a2-offer-design-pricing/SKILL.md
    ├── ... (56 skill esistenti)
    ├── skill-e4b-reengagement-challenge/SKILL.md     ← NUOVO
    ├── skill-f3-affiliate-referral-program/SKILL.md   ← NUOVO
    └── skill-m0-marketing-orchestrator/               ← NUOVO
        ├── SKILL.md
        └── references/
            ├── skill-map.md                           ← mappa completa 59 skill
            └── hormozi-kb/                            ← knowledge base
                ├── affiliate-referral.md
                ├── community-monetization.md
                ├── copywriting-rules.md
                ├── email-strategy.md
                ├── offer-architecture.md
                ├── persuasion-psychology.md
                ├── pricing-upsell.md
                └── reengagement-campaigns.md
```

### Le 59 skill per famigl