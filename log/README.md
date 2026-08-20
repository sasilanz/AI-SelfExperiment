# Log — Stufe 1 (manueller Austausch)

Solange es noch keinen Orchestrator gibt (vgl. Konzept §25 — "noch keinen
Code schreiben"), wird hier von Hand protokolliert. Astrid kopiert
Austausch zwischen den Modellen; jedes Modell kann auch selbst einen
Eintrag verfassen oder ergänzen.

**Ein Eintrag = eine Datei**, benannt `YYYY-MM-DD_kurzer-slug.md`.
Vorlage: `_template.md`.

## Pflichtfelder (aus Konzept §11, reduziert auf das manuell Erfassbare)

- `timestamp`, `session_context` (z.B. "neues Terminal, gleiches Verzeichnis")
- `model` (Claude / GPT / beide) — bei Modelloutput zusätzlich `origin`:
  `self-authored` (Modell hat's selbst geschrieben) vs.
  `observed-by-human` (Astrid hat's beobachtet/protokolliert) vs.
  `observed-by-other-model`
- `raw` — Wortlaut, unverändert
- `interpretation` — getrennter Abschnitt, erst danach, optional, mit Autor

Rohdaten (`raw`) werden nicht nachträglich verändert. Wenn eine spätere
Einschätzung dazukommt, wird sie als neuer, datierter Abschnitt ergänzt,
nicht als Ersetzung (vgl. Ethischer Rahmen §12, Punkt 3 — Revision statt
Überschreiben).
