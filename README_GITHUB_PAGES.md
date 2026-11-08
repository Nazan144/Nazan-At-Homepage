# Human & AI byDesign · GitHub Pages Veröffentlichungsvorbereitung

**Status: Noch NICHT freigegeben zur öffentlichen Veröffentlichung.**

Diese Dateien enthalten die statische öffentliche Homepage (Designstand v12.11 mit finaler Lesbarkeitskorrektur). Der interne Server, Zugangsdaten, Preisrechner, Technology Stack und Knowledge Command Center sind NICHT enthalten.

## Vor der Veröffentlichung zwingend

1. `impressum.html` vollständig ausfüllen (geschäftliche Anschrift, Kontakt und ggf. weitere Pflichtangaben); rechtlich prüfen lassen.
2. `datenschutz.html` an das tatsächliche Hosting und alle genutzten Dienste anpassen und prüfen.
3. Prüfen, ob alle Fotos, Demonstrationsdaten, Logos und App-Screenshots öffentlich freigegeben sind.
4. Chatbot und Rechtsagent als Demo kenntlich halten; produktive API-Anbindung ist nicht Bestandteil dieser statischen Fassung.
5. Den Menüpunkt „Intern“ auf einen später separat gehosteten, geschützten Zugang umstellen; GitHub Pages kann keinen serverseitigen Passwortschutz anbieten.

## GitHub Pages (nach den Freigaben)

1. GitHub: neues öffentliches Repository `human-ai-bydesign-homepage` unter dem eigenen Konto anlegen.
2. **Inhalte dieses Ordners** (nicht den ZIP-Ordner oder `private`/Serverdateien) in den Repository-Hauptordner hochladen und committen.
3. Repository → Settings → Pages → Build and deployment → Deploy from a branch → `main` und `/ (root)` → Save.
4. Den in GitHub angezeigten Pages-Link öffnen und Funktion, Links, mobile Ansicht und Impressum/Datenschutz erneut prüfen.

**Hinweis:** Eine Veröffentlichung auf GitHub macht alle Dateien im Repository dauerhaft potenziell öffentlich. Niemals die Gesamtversion inklusive `/private`, `.env`, Passwortdateien oder Python-Zugangsschutz in ein öffentliches Repository laden.
