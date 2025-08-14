# GitHub Pages Plus Starter

Diese Vorlage ist für GitHub Pages optimiert (Projekt- oder Benutzerseite).

## Schnellstart
1. Dateien in ein **öffentliches** Repo pushen.
2. Repo → **Settings → Pages** → **Deploy from a branch** (Branch `main`, Folder `/`).

## Eigene Domain
- `CNAME`-Datei anlegen (Inhalt: `dein.domainname.tld`), DNS-CNAME bei deinem Anbieter auf `BENUTZERNAME.github.io` zeigen lassen.

## Wichtige Dateien
- `index.html` – Startseite
- `404.html` – Fehlerseite für nicht gefundene Pfade
- `sitemap.xml` – einfache Sitemap
- `robots.txt` – verweist auf die Sitemap
- `assets/` – Bilder, Favicon usw.

## Hinweise
- Links sind relativ gehalten (z. B. `./`), damit Projektpfade funktionieren.
- Open-Graph-URL/Images werden zur Laufzeit aus der aktuellen URL abgeleitet.
