# Bahn 4

Persönliches Wettkampf-Logbuch fürs Schwimmen. Bahn 4 dokumentiert die Ergebnisse **einer** Person:
Wettkämpfe, Zeiten, Platzierungen, Zwischenzeiten, persönliche Bestzeiten und deren Entwicklung.

- läuft als Web-App auf dem iPhone (Home-Bildschirm, Vollbild, offline)
- keine Anmeldung, kein Server: alle Daten bleiben auf dem Gerät
- Import von LENEX-Ergebnisdateien (.lxf / .lef) aus EasyWk oder SPLASH Meet Manager
- Sicherung als JSON-Datei (z. B. in iCloud Drive), Export als CSV

## Installation auf dem iPhone

1. Die App-Adresse in **Safari** öffnen (GitHub Pages, siehe unten).
2. Unten auf **Teilen** tippen, dann **Zum Home-Bildschirm** → **Hinzufügen**.

## Veröffentlichen mit GitHub Pages

1. Repository auf **public** stellen: *Settings → General → Danger Zone → Change visibility*.
2. *Settings → Pages → Build and deployment*: **Deploy from a branch**, Branch mit diesen Dateien wählen, Ordner **/ (root)**.
3. Nach ein bis zwei Minuten ist die App unter `https://<benutzername>.github.io/<repository>/` erreichbar.

## Datenschutz

Das Repository enthält nur den Programmcode. Ergebnisse und Profil werden ausschließlich im Speicher
des Browsers auf dem jeweiligen Gerät abgelegt und nirgendwohin übertragen.

## Entwicklung

Reines HTML/CSS/JavaScript ohne Build-Schritt. Nach Änderungen an Dateien in `sw.js` die Konstante
`VERSION` erhöhen, damit installierte Apps die neue Version laden.

Schriften: Barlow, Barlow Condensed (SIL OFL), IBM Plex Mono (SIL OFL). Bibliothek: JSZip (MIT/GPLv3).
