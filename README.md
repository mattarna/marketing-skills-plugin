# marketing-skills (plugin Claude Code)

Plugin ufficiale che pacchettizza tutte le 56 skill di marketing per essere installato su **Claude Code / Cowork** via marketplace.

- **Repo git remoto**: https://github.com/mattarna/marketing-skills-plugin
- **Branch**: `main`
- **Versione**: 2.0.0

---

## Cosa contiene

```
plugin/
├── README.md                  ← questo file
├── .claude-plugin/
│   ├── plugin.json            ← manifesto del plugin (nome, versione, autore)
│   └── marketplace.json       ← entry per Cowork marketplace
└── skills/
    └── skill-XX-nome/
        └── SKILL.md           ← una skill (38 cartelle in totale)
```

Sono **56 skill** organizzate in 13 famiglie (P, A, BR, F, L, C, B/W, LI, N, E, S, W, R). Mappa completa nel [README master](../README.md).

---

## Come si installa via Cowork

1. Apri **Cowork → Customize → +**
2. Incolla l'URL del repo: `https://github.com/mattarna/marketing-skills-plugin`
3. Premi **Add**
4. Cowork rileva `.claude-plugin/plugin.json` e registra le 56 skill

Per aggiornare dopo un push:

- **Cowork → Customize → marketing-skills-plugin → Sync**

(Riferimento: [docs/CHEATSHEET.md](../docs/CHEATSHEET.md), [docs/INSTALL.md](../docs/INSTALL.md).)

---

## Workflow di aggiornamento (per chi modifica le skill)

Da questa cartella:

```bash
# modifica un SKILL.md dentro skills/skill-XX-…/SKILL.md
git add skills/skill-XX-…/SKILL.md
git commit -m "update: <descrizione>"
git push origin main
```

Dopo il push, **Sync** dentro Cowork tira la nuova versione.

---

## Struttura di una skill

Ogni `SKILL.md` ha un frontmatter YAML con i trigger di auto-attivazione + il corpo della skill:

```yaml
---
name: skill-XX-nome
description: ...
triggers:
  - keyword: ...
  - intent: ...
---

# Corpo della skill in markdown
```

Manifesto esteso (con `chains`, `conflicts`, `categories`): vedi [docs/PLUGIN_MANIFEST.md](../docs/PLUGIN_MANIFEST.md).
