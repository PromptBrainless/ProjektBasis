---
type: plan
status: active
date: 2026-10-07
---

# Plan — nach dem Merge

`main` ist `0c4abe85`, Merge von PR #3. `archive/familyspace` hält `56d6ff63`. Canva-Deckblatt hängt im README.

## Nächste Schritte

1. Vorfahren-Branches löschen: `chore/pb-gds-foundation`, `chore/obsidian-knowledge-system`, `docs/conversation-archive-obsidian`, `chore/vault-structure`, `copilot/archivefamilyspace`. Commits bleiben im Merge.
2. Lindendorf: Kanon ist `lindendorf-rpg-alpha-V.1.3` (zuletzt 29. September). Ältere Stände nur als Herkunft notieren, nicht kopieren: `Lindendorf`, `SpielVersion1.0`, `htbah-lindendorf`, `V.1`, `V.1.1`, `V.1.2`.
3. Drosselau: `Drosselau-Spielwelt` als Textkanon, `Drosselau-Haeuserbilder` als Bildkatalog, `Spielwelt` nur wenn es kein Duplikat ist.
4. Aschenkrone: `Aschenkronev2` als Kanon, `Aschenkrone` als Altstand.
5. Studio: `worldforge-studio` zuerst, ohne Spieldaten. Danach rpgmaker, Fokus-Dokus, Feldwerk.
6. Quellrepo erst archivieren, wenn die Herkunftszeile auf `main` liegt.

Kein Schritt kopiert `node_modules` oder Zips. Kein Schritt löscht ein Quellrepo.
