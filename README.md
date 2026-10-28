# ZOLEO für Buena Vista Crew

Statische One-Page-Seite, alle Bilder und Videos liegen lokal in `assets/`. Keine Build-Schritte, kein Framework.

## Deploy mit Vercel

1. Diesen Ordner als Repository auf GitHub pushen (`git init`, `git add .`, `git commit -m "Buena Vista Crew"`, Remote setzen, `git push`).
2. In Vercel „Add New Project“, das Repository wählen, Framework Preset „Other“, Build Command leer lassen, Output Directory leer lassen, Deploy.
3. Link testen (Desktop und iPhone), dann an Buena Vista schicken.

Die Seite ist per `noindex` und `robots.txt` für Suchmaschinen gesperrt.

## Struktur

| Pfad | Inhalt |
|---|---|
| index.html | Seite, Texte und Preise direkt im HTML |
| assets/logo-black.png, logo-white.png | ZOLEO-Logo für Navigation und Footer |
| assets/hero/ | 7 Header-Bilder, laufen als Überblendung |
| assets/partner/ | Logos für den Logo-Slider |
| assets/foto/ | Referenzen: Mallorca, Agnesstraße 50, Meraki, The Gardens, Hav og Fjell, Haus Zweineun |
| assets/film/ | Objektfilm, 3 Reels, Composing, dazu je ein Standbild als Poster |
| assets/web/ | Screen-Video merakistudios.gr |
| assets/team/ | Porträts |
| assets/fonts/ | Optional: gotham-book.woff2, gotham-medium.woff2, gotham-bold.woff2. Ohne Dateien läuft Montserrat |
