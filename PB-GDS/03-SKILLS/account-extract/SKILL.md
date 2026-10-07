# account-extract

Extrahiert ein Quellrepo in den Vault, einen Schritt pro Lauf.

## Wann

Wenn ein PromptBrainless-Repo nach `OBSIDIAN/20-Spielwelt` oder `OBSIDIAN/30-Studio` soll.

## Schritte

1. Branch `chore/vault-structure` lesen. Nicht auf main arbeiten.
2. Ein Repo wählen. Issue oder TODO-Zeile nennen.
3. Branch `extract/<quelle>` von `chore/vault-structure`.
4. Nur beabsichtigte Dateien kopieren. Keine node_modules, keine Zips.
5. Zeile in `OBSIDIAN/20-Spielwelt/HERKUNFT.md` oder Studio-README: Pfad, Quellrepo, Commit, Datum.
6. Draft-PR. Nach Sichtprüfung mergen. Quellrepo archivieren, nicht löschen.

## Verboten

Force-Push. Löschen vor gesehenem Extrakt. FamilySpace aus `archive/familyspace` verschieben.
