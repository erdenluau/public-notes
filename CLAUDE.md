# CLAUDE.md — public-notes

Kontext für Claude Code. Bitte zu Beginn jeder Sitzung beachten.

## Was dieses Repo ist

Öffentliche HTML-Linksammlung ("Lesezeichen"), veröffentlicht über **GitHub Pages**.
Die Seite ist bewusst **nicht für Suchmaschinen bestimmt**: Jede HTML-Seite trägt ein
noindex-Robots-Meta-Tag. Dieses Signal ist kritisch und darf bei Änderungen niemals
entfernt oder abgeschwächt werden.

Inhaltlicher Schwerpunkt der Sammlung: datensouveräne und europäische Alternativen.
Vorschläge für neue Links sollen dieser Ausrichtung folgen.

## Struktur

- `*.html` — die Linksammlung selbst (statisches HTML, kein Build-Schritt, kein Framework)
- `.github/workflows/` — GitHub-Actions-Workflow zur Linkprüfung mit **lychee**
- `wissen/` — Wissens-/Notizordner mit eigener README
- `README.md` — Projektübersicht

## Sprache & Stil

- Inhalte und Commit-Messages auf **Deutsch**.
- HTML valide und semantisch halten.
- **Keine externen Tracker, Analytics, CDN-Fonts oder Fremd-CDNs** einbinden
  (Datensouveränität). Werden Ressourcen benötigt, lokal ablegen und relativ einbinden.
- Bestehendem Muster folgen: gemeinsame CSS-Datei nutzen statt Inline-Styles,
  wo bereits vorhanden.

## Linkprüfung (lychee)

- Neue oder geänderte Links müssen die lychee-Prüfung bestehen.
- Den Workflow unter `.github/workflows/` **nicht umbenennen und nicht in seiner
  Struktur brechen**. Änderungen an der lychee-Konfiguration nur gezielt und mit
  kurzer Begründung im Commit.
- Als tot gemeldete Links **nicht stillschweigend entfernen** — erst kennzeichnen bzw.
  nachfragen. Hinter der Sammlung steht eine rechtliche Prüfung der Links nach
  deutschem Recht; Entfernungen sind bewusste Entscheidungen, keine Automatik.

## Deployment

- Veröffentlichung über GitHub Pages aus diesem Repo.
- Pages-relevante Dateien (z. B. `.nojekyll`, ggf. `CNAME`) nicht ohne Rückfrage ändern.

## Arbeitsweise

- Änderungen als kleine, nachvollziehbare Commits vorschlagen — keine
  Massen-Umformatierung bestehender HTML-Dateien ohne ausdrücklichen Auftrag.
- Im Zweifel Plan-Modus nutzen und das Vorhaben vor Datei-Edits zur Freigabe vorlegen.

## Kurz-Checkliste

Erwünscht:
- noindex-Signal in jeder Seite erhalten
- bei neuen Links EU-/souveränitätsfreundliche Optionen bevorzugen
- kleine, erklärte Commits auf Deutsch

Vermeiden:
- Tracker, Analytics, externe Fonts/CDNs
- Brechen des lychee-Workflows
- stilles Löschen gemeldeter Links
- ungefragte Massen-Reformatierung
