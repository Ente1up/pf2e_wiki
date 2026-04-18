# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

An **Obsidian vault** for a Pathfinder 2e tabletop RPG campaign, written primarily in German. Content is Markdown with YAML frontmatter. No build system or tests — this is a documentation/wiki project.

## Language

All content is written in **German**. New notes should follow the same language. English is only used for PF2e mechanical terms (e.g. Ancestry, Proficiency, Feat, Trained/Expert/Master/Legendary) since these are the official game terms used at the table.

## Vault structure

- `1. World/` — Lore, locations, NPCs, gods, world events
- `2. Ruling/` — Rules reference, organized by topic:
  - `1. Grundregeln/` — Core mechanics (attributes, saves, actions)
  - `2. Charackterbau/` — Character creation and building
  - `3.🛡️Kampf/` — Combat rules (physical and magical)
  - `4. 🏛️ Klassen/` — Class pages split into `⚔️ Martials/` and `🔮 Spellcaster/`
  - `5. Völker/` — Ancestry pages
  - `6. Fertigkeiten & Skills/` — Skills and feats (Skill Feats, General Feats, etc.)
  - `Leveling/` — Level-up and feat progression notes
- `3. Spielhilfen/` — GM aids: encounters, loot tables, NPC templates, events
- `index.md` — Vault landing page

## Frontmatter conventions

Every note uses this YAML frontmatter pattern:

```yaml
---
title: "Note Title"
system: "Pathfinder 2e"
kategorie: "Category name"
tags:
  - pf2e
  - relevant-tag
status: "Entwurf"   # or "Fertig"
verwandte_notizen:
  - "Linked Note Title"
quellen:
  - "Player Core (Seite X)"
erstellt: YYYY-MM-DD
---
```

## Obsidian internal links

Use `[[Note Name]]` for internal links. When the display name should differ from the file name, use `[[Filename|Display Name]]`. Link targets are note titles without path — Obsidian resolves them by filename.

## File naming

Note filenames must **not** repeat the folder category. The folder already carries the context. Use only the emoji + the name itself.

- ✅ `👤 Harsk.md` (in `Personen/`)
- ❌ `👤 Person - Harsk.md`
- ✅ `🏙️ Highhelm.md` (in `Orte/`)
- ❌ `🏙️ Ort - Highhelm.md`
- ✅ `📅 Errinorn.md` (in `globale Events/`)
- ❌ `📅 Feiertag - Errinorn.md`

This applies to all note types: Orte, Personen, Götter, Feiertage, Phänomene, etc.

## Emoji conventions

Emojis are used as visual markers in folder names, note titles, and table entries. Follow existing patterns per category:
- `⚔️` Martials, `🔮` Spellcaster, `🛡️` Combat
- `🏛️` Klassen, `🌍` World/Lore, `📅` Calendar/Events, `👑` Rulers, `👤` People
- `platzhalter.md` = placeholder file keeping an empty folder tracked in git

## Ideas Note

An ideas collection exists at `3. Spielhilfen/💡 Ideas.md`. At the **start of every session**, read this file and present the bullet points to the user, asking if they want to work on any of them. The user adds ideas as unstructured bullet points (NPCs, encounters, story hooks, etc.) — do not reformat them, only append new entries when asked.
