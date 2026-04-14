# Marktrisiko-Kompass BASIC

Verständliche Markt- und Risikosignale für Privatanleger – klar, regelbasiert und ohne Terminal-Overload.

## Ordnerstruktur

- `index.html` – Dashboard
- `documentation.html` – Endnutzerfreundliche Dokumentation
- `manifest.json` – PWA-Manifest
- `data/latest.json` – vom Dashboard geladene Datendatei
- `scripts/fetch_data.py` – Datenfetch für FRED + Google News RSS
- `.github/workflows/update-market-data.yml` – automatisches GitHub-Update

## GitHub-Upload

1. Repository-Inhalt durch diese Dateien ersetzen.
2. In GitHub unter `Settings > Secrets and variables > Actions` das Secret `FRED_API_KEY` anlegen.
3. GitHub Pages auf Root veröffentlichen.
4. Workflow einmal manuell ausführen, damit `data/latest.json` mit echten Daten überschrieben wird.

## Hinweis

Das Produkt dient der allgemeinen Marktphasen-Einordnung. Es ist keine Anlageberatung.
