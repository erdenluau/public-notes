# CLAUDE.md — public-notes

Kontext für Claude Code. Bitte zu Beginn jeder Sitzung beachten.

## Was dieses Repo ist

Öffentliches Repo, veröffentlicht über **GitHub Pages**. Kern ist eine HTML-Linksammlung
("Lesezeichen"), bewusst **nicht für Suchmaschinen bestimmt**: Die Seiten tragen ein
noindex-Robots-Meta-Tag, das bei Änderungen niemals entfernt oder abgeschwächt werden darf.
Inhaltlicher Schwerpunkt: datensouveräne und europäische Alternativen.

Die veröffentlichten HTML-Dateien liegen unter **`wissen/wissen/`**.

## Struktur

Festes Ordnergerüst (identisch mit dem privaten `wissen`-Repo):

- `projekte/` — laufende Projekte/Inhalte
- `wissen/` — Kernnotizen; enthält unter `wissen/wissen/` die veröffentlichte HTML-Linksammlung
- `vorlagen/` — Vorlagen/Templates
- `archiv/` — Abgeschlossenes / Altbestände
- `_meta/` — Repo-eigene Meta-Infos (Unterstrich sortiert nach oben)
- `.github/` — GitHub-Actions-Workflow zur Linkprüfung mit **lychee**
- `README-public-notes.md` — Projektübersicht

## Sprache & Stil

- Inhalte und Commit-Messages auf **Deutsch**.
- HTML valide und semantisch halten.
- **Keine externen Tracker, Analytics, CDN-Fonts oder Fremd-CDNs** einbinden
  (Datensouveränität). Werden Ressourcen benötigt, lokal ablegen und relativ einbinden.
- Bestehendem Muster folgen (gemeinsame CSS-Datei statt Inline-Styles, wo vorhanden).

## Linkprüfung (lychee)

- Neue oder geänderte Links müssen die lychee-Prüfung bestehen.
- Den Workflow unter `.github/workflows/` **nicht umbenennen und nicht in seiner
  Struktur brechen**. Änderungen an der lychee-Konfiguration nur gezielt und mit
  kurzer Begründung im Commit.
- Als tot gemeldete Links **nicht stillschweigend entfernen** — erst kennzeichnen bzw.
  nachfragen. Hinter der Sammlung steht eine rechtliche Prüfung der Links nach
  deutschem Recht.

## Deployment

- Veröffentlichung über GitHub Pages; die ausgelieferten Seiten stammen aus `wissen/wissen/`.
- Pages-relevante Dateien (z. B. `.nojekyll`, ggf. `CNAME`) nicht ohne Rückfrage ändern.
- Beim Verschieben/Umbenennen von Dateien in `wissen/wissen/` daran denken, dass sich
  dadurch veröffentlichte URLs ändern können.

## Arbeitsweise

- Änderungen als kleine, nachvollziehbare Commits vorschlagen — keine
  Massen-Umformatierung bestehender Dateien ohne ausdrücklichen Auftrag.
- Im Zweifel Plan-Modus nutzen und das Vorhaben vor Datei-Edits zur Freigabe vorlegen.
